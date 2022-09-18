<template>
  <div>Hello {{ name }}!</div>
  <Button />
</template>

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
