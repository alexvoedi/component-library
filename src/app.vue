<script lang="ts">
import { defineComponent } from 'vue'
import BaseButton from './BaseButton.vue'

export default defineComponent({
  name: 'App',
  components: {
    BaseButton,
  },
})
</script>

<template>
  <BaseButton>test</BaseButton>
</template>
