<template>
  <span
    class="mt-1 flex items-center justify-center py-1 rounded-full text-xs font-medium leading-4 bg-green-400 font-semibold text-white"
  >{{messages}}</span>
</template>

<script>
export default {
  name: "MessageBadge",
  props: {
    messages: Number
  }
};
</script>

<style>
</style>