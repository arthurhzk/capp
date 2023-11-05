<template>
  <div
    class="w-[300px] h-[200px] border-2 border-t-4 border-cyan-500 flex flex-col items-center gap-4 py-2"
  >
    <slot></slot>
    <h1 class="text-7xl text-white font-semibold">{{ text }}</h1>
    <p class="text-cyan-500 font-semibold">{{ description }}</p>
  </div>
</template>

<script>
export default {
  name: "TheSmallCard",
  props: {
    text: {
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
