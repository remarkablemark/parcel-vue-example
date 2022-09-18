<template>
  <h1>Hello {{ name }}!</h1>
  <Button />
</template>

<style scoped>
h1 {
  color: hotpink;
  font-family: cursive;
}
</style>

<script>
import Button from './Button.vue';

export default {
  components: {
    Button,
  },

  data() {
    return {
      name: 'Vue',
    };
  },
};
</script>
