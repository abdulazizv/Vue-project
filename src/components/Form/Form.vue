<template>
  <div>
    <h1 class="text-center text-black">Form elements</h1>
    <Input inputType="text" placeholder="Enter username" labelId="username"/>
    <Input inputType="password" placeholder="Enter password" labelId="userpassword"/>
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
