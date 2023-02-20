<template>
  <div>
    <h1 class="text-center text-black">Form elements</h1>
    <Input inputType="text" placeholder="Enter username" labelId="username" />
    <Input
      inputType="password"
      placeholder="Enter password"
      labelId="userpassword"
    />
    <Button
      btnType="button"
      textContent="Signup"
      class="bg-green-500 text-white"
    />
    <Card>
      <img src="https://picsum.photos/id/356/320/210" alt="cover" />
      <div class="card-body p-3">
        <h1 class="card-title font-semibold text-xl my-2">Card title lorem ipsum . . .</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis, quo
          adipisci. Eaque reiciendis a ratione 
        </p>
        <div class="flex gap-x-2 my-2">
            <Button btnType="button" textContent="DIS LIKE" class="bg-red-500 text-white"/>
            <Button btnType="button" textContent="LIKE" class="bg-green-500 text-white"/>
        </div>
      </div>
    </Card>
  </div>
</template>

<script>
import Input from "../../ui/Input.vue";
import Button from "../../ui/Button.vue";
import Card from "../../ui/Card.vue";
export default {
  name: "Form",
  components: {
    Input,
    Button,
    Card,
  },
};
</script>

<style></style>
