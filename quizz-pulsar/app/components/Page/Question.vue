<template>
    <Page>
        <ActionBar title="Set the question right here!!!"/>
        <GridLayout columns="*" rows="*">
            <Label class="message" :text="msg" col="0" row="0"/>
        </GridLayout>
    </Page>
</template>

<script>
	export default {
		name: "Question",
		data() {
			return {
				msg: 'Work to be done by a third person. This is where user will answer the questions!'
			}
		}
	}
</script>

<style scoped>

</style>