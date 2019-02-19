<template>
    <Page>
        <ActionBar title="Set the choices right here!!!"/>
        <GridLayout columns="*" rows="*">
            <Label class="message" :text="msg" col="0" row="0"/>
        </GridLayout>
    </Page>
</template>

<script>
	export default {
		name: "ChoiceSettings",
		data() {
			return {
				msg: 'Work to be done by someone. This is where user will choose his settings!'
			}
		}
	}
</script>

<style scoped>

</style>