<template>
  <div v-if="toogle" class=" w-[300px] min-h-screen shadow-lg">
      <a href="#" class="text-2xl font-bold bg-white text-center block text-indigo-600">
        ADMIN DASHBOARD
      </a>

      <ul class="list mt-8">
        <li class="list__item py-1 px-2" v-for="item in navlink" :key="item.id">
          <a :href="item.link" class="flex list__item--link min-w-full items-center bg-white p-4 rounded-lg text-lg shadow border hover:bg-indigo-50 duration-300 font-bold">
            <i class='bx  text-indigo-500 text-2xl mr-3' :class="item.icon"></i> <span class="">{{ item.title }}</span>
          </a>
        </li>
      </ul>
  </div>
</template>

<script>
import navLinks from '../../constants/navlinks';
export default {
     name:'Sidebar',
     props:{
      toogle:{
        type:Boolean,
        required:true
      }
     },
     data() {
      return {
        navlink:navLinks
      }
     }
};
</script>

<style scoped lang="css">
  .active {
    background-color: rgb(107,8,177) !important;
    color: #fff !important;
    font-weight: 600 !important;
  }
</style>
