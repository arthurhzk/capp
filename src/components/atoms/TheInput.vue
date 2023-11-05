<template>
  <div>
    <input
      :class="inputStyle"
      :placeholder="placeholder"
      :type="type"
      v-model="inputValue"
      @input="updateValue"
    />
  </div>
</template>

<script>
export default {
  name: "TheInput",
  props: {
    value: {
      type: String,
      default: "",
    },
    type: {
      type: String,
      default: "text",
    },
    placeholder: {
      type: String,
      default: "",
    },
    inputStyle: {
      type: String,
      default: "",
    },
  },
  methods: {
    updateValue() {
      this.$emit("input", this.inputValue);
    },
  },
  data() {
    return {
      inputValue: "",
    };
  },
};
</script>

<style>
input {
  text-align: left;
  vertical-align: top;
}
</style>
