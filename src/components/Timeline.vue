<template>
    <v-timeline direction="horizontal" line-inset="12">
      <v-timeline-item>
        <template v-slot:opposite>
          Opposite
        </template>
        Content
      </v-timeline-item>
  
      <v-timeline-item>
        <template v-slot:opposite>
          Opposite
        </template>
        Content
      </v-timeline-item>
  
      <v-timeline-item>
        <template v-slot:opposite>
          Opposite
        </template>
        Content
      </v-timeline-item>
      <v-timeline-item>
        <template v-slot:opposite>
          Opposite
        </template>
        Content
      </v-timeline-item>
    </v-timeline>
  </template>

<script lang="ts">

import { defineComponent } from "vue";

export default defineComponent({

});
</script>

<style ></style>