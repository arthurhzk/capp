<template>
  <div class="flex flex-col">
    <slot></slot>
    <h2 class="text-gray-600 font-bold text-2xl text-center" v-html="text"></h2>
  </div>
</template>

<script>
export default {
  name: "TheIconGrid",
  props: {
    text: {
      type: String,
      required: true,
    },
  },
};
</script>
