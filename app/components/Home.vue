<template>
  <Page>
    <GridLayout>
      <Button>Test</Button>
    </GridLayout>
  </Page>
</template>

<script lang="ts">
import Vue from 'nativescript-vue';

export default Vue.extend({
  computed: {
    message() {
      return 'Blank {N}-Vue app!';
    },
  },

  methods: {
    logMessage() {
      console.log('You have tapped the message!23');
    },
  },
});
</script>

<style>
/* .info {
    font-size: 20;
  } */
</style>
