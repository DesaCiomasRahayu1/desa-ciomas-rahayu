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
      <p class="text-3xl font-semibold">Visi & Misi Desa Ciomas Rahayu</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Terwujudnya Masyarakat Desa Ciomas Rahayu yang Sehat, Maju, Mandiri dan  Aman Melalui Pelayanan Yang Menyeluruh Secara Optimal”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Memingkatkan Penyelenggaraan dan Pelayanan Pemerintah Desa yang Trasparan, Akuntabilitas, Bertanggung Jawab di berbagai Sektor;
        </li>
        <li>
          2. Menjalin Kerjasama dengan Pihak Ke tiga guna mengembangkan potensi wilayah Desa Ciomas Rahayu baik bidang Usaha Kecil Menengah, Ketahanan Pangan, Bumdesa, Pada sekala yang lebih besar;
        </li>
        <li>
          3. Kolaburasi dan Mendorong Peran serta para Alim Ulam guna membina dan meningkatkan pada bidang kerohanian;
        </li>
        <li>
          4. Meningkatkan peran serta Pemuda dan Pemudi dibidang Seni, Budaya, Olah Raga dan Kreatifitas dalam wadah Karang Taruna;
        </li>
        <li>
          5. Meningkatkan Peran Serta Kader Kesehatan Masyarakat dalam mewujudkan Desa Ciomas Rahayu Sehat;
        </li>
        <li>
          6. Menciptakan Keamanan dan Ketentraman Warga Desa Ciomas Rahayu melalui Peningkatan Kewaspadaan dan tolenransi;
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
