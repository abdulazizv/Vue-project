<template>
  <div>
    <h1 class="text-center text-black">Form elements</h1>
    <Input />
    <Input />
    <Button />
  </div>
</template>

<script>
import Input from '../../ui/Input.vue'
import Button from '../../ui/Button.vue'
export default {
  name: "Form",
  components: {
    Input,
    Button,
  },
};
</script>

<style></style>
