<template>
  <button class="my-gradient font-semibold p-3">{{ text }}<slot></slot></button>
</template>

<script>
export default {
  name: "TheButton",
  props: {
    text: {
      type: String,
    },
  },
};
</script>

<style>
.my-gradient {
  background: radial-gradient(circle, #00e1ff -20%, #000000a9 100%);
  color: white;
}
</style>
