<template>
    <Page>
        <ActionBar title="Set the legal infos right here!!!"/>
        <GridLayout columns="*" rows="*">
            <Label class="message" :text="msg" col="0" row="0"/>
        </GridLayout>
    </Page>
</template>

<script>
	export default {
		name: "LegalInformations",
		data() {
			return {
				msg: 'Work to be done by person2. This is where user will see the legal mentions!'
			}
		}
	}
</script>

<style scoped>

</style>