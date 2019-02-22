<template>
    <Page>
        <ActionBar title="Welcome to NativeScript-Vue!"/>
        <GridLayout columns="*" rows="*">
        </GridLayout>
    </Page>
</template>

<script>
  export default {
    data() {
      return {
        msg: 'Hello World!',
      }
    },
    created() {
        // initializeFirebase();
        
    },
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
