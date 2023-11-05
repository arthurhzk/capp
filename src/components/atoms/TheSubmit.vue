<template>
  <div>
    <button :class="styledButton"><slot></slot>{{ text }}</button>
  </div>
</template>

<script>
export default {
  name: "TheSubmit",
  props: {
    text: {
      type: String,
    },
    styledButton: {
      type: String,
    },
  },
};
</script>
