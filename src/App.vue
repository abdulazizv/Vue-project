<template>
  <Header />
  <main>
    <aside class="sticky z-20 top-0">
      <Sidebar />
    </aside>
      <div class="main">
        <!-- View pages -->
      </div>
    
  </main>
  <Footer />
</template>

<script>
  import Header from './components/Header/Header.vue';
  import Sidebar from './components/Sidebar/Sidebar.vue';
  import Footer from './components/Footer/Footer.vue';
export default {
  name: "App",
  components:{
    Header,
    Sidebar,
    Footer
  }
};
</script>

<style></style>
