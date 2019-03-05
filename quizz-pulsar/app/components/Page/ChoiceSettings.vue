<template>
    <Page>
        <!--<ActionBar title="Set the choices right here!!!"/>-->
        <StackLayout>
            <Label class="message" :text="msg" col="0" row="0"/>
            <ListPicker :items="categoryList" selectedIndex="0"
                        v-model="selectedCategory" />
            <ListPicker :items="difficultyList" selectedIndex="0"
                        v-model="selectedDifficulty" />
            <Button text="click" @tap="displaySelectionedValues" />
        </StackLayout>
    </Page>
</template>

<script>
	export default {
		name: "ChoiceSettings",
		data() {
			return {
				msg: 'configuration du quizz',
				categoryList: ["toto", "tata", "titi"],//todo get category from https://opentdb.com/api_category.php
                difficultyList: ["easy", "medium", "hard"]
			}
		},
        methods: {
			displaySelectionedValues() {
				// console.log(this.categoryList)
				console.log(this.categoryList[this.selectedCategory]);
				console.log(this.difficultyList[this.selectedDifficulty]);
			}
		},
	}
</script>

<style scoped>

</style>