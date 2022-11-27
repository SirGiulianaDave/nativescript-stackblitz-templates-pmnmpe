<template>
  <Page>
    <ActionBar>
      <Label text="UnwantedTherapy" class="font-bold text-lg" />
    </ActionBar>

    <GridLayout>
      <Label
        class="text-xl align-middle text-center text-black-500"
        :text="message"
        @tap="logMessage"
      />
    </GridLayout>
  </Page>
</template>

<script lang="ts">
import Vue from 'nativescript-vue';

export default Vue.extend({
  computed: {
    message() {
      return 'Click here to create your profile!';
    },
  },

  methods: {
    logMessage() {
      console.log('Get fucked Linus');
    },
  },
});
</script>

<style>
/* .info {
    font-size: 20;
  } */
</style>
