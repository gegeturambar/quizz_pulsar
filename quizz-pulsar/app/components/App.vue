<template>
    <LegalInformations/>
    <!-- choose the Page component on which you work here. Transitions between components will be made later. -->
</template>

<script >
  import ChoiceSettings from "./Page/ChoiceSettings";
  import LegalInformations from "./Page/LegalInformations";
  export default {
	  components: {LegalInformations, ChoiceSettings}
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
