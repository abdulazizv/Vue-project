<template>
  <Header />
  <main>
    <aside>
      <Sidebar />
      <div class="main">
        <!-- View pages -->
      </div>
    </aside>
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
