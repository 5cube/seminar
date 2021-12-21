<script setup>
const props = defineProps({
  href: String,
  target: {
    type: String,
    default: '_blank',
  },
})
</script>

<template>
  <a
    :href="href"
    :target="target"
    class="text-blue-500 active:text-blue-400 hover:text-blue-600 cursor-pointer"
  >
    <slot />
  </a>
</template>
