<template>
  <q-page class="column">
  <div class="q-pa-md">
    <q-video
      :ratio="16/9"
      src="https://www.youtube.com/embed/wS2EZwynFdo?si=g3TruwtRTQpOvZ7D"
    />
  </div>
</q-page>
</template>

<script setup>
import { ref } from 'vue';

const count = ref(0);

const min = -5;
const max = 5;
</script>
