<script setup>
import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue"
</script>

<template>

  <div class="flex flex-col min-h-screen">

      <Header />


  <main>

    <div class="hero min-h-screen bg-base-200">
      <div class="hero-content text-center">
        <div class="max-w-md">
          <h1 class="text-5xl font-bold">Welcome to Hollaa!</h1>
          <p class="py-6">This is a simple example of a Vue.js application with a header and footer.</p>
          <p class="py-6">You can add your own content here.</p>
        </div>
      </div>
    </div>
  </main>
  <Footer />
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
  display: block;
  width: 100%;
}

main {
  display: block;
  margin-top: 1rem; /* Adds space below the header */
  padding: 1rem;
}
</style>