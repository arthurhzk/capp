<template>
  <div class="my-gradient flex flex-col justify-center">
    <div class="ml-40">
      <slot></slot>
      <h1 class="text-4xl font-bold pt-5" v-html="title"></h1>
      <p class="pt-5" v-html="description"></p>
      <p class="pt-5 font-semibold">Leia mais...</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "TheGradientCard",
  props: {
    title: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.my-gradient {
  background: radial-gradient(circle, #00e1ff -20%, #000000a9 100%);
  width: 600px;
  height: 400px;
}
</style>
