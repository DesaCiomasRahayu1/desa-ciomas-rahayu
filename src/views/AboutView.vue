<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />
  <main class="flex">
    <Sidebar />
    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img srchttps://github.com/DesaCiomasRahayu1/desa-ciomas-rahayu/blob/main/src/assets/struktur%20desa%20ciomas%20rahayu.png alt=" />
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
