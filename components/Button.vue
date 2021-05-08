<template>
  <b-button class="button">
    {{ text }}
  </b-button>
</template>
<script>
export default {
  name: 'Button',
  props: {
    text: {
      type: String,
      required: true,
    },
  },
}
</script>
<style lang="css" scoped>
.button {
  width: 236px;
  height: 55px;
  background: #ff1a1a;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 30px;
  display: flex;
  justify-content: center;
  margin: auto;
  font-size: 30px;
  color: #000000;
  line-height: 34px;
}
</style>
