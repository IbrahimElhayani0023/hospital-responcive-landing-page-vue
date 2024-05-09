<script setup lang="ts">
import Service from "@/components/Service.vue";
import Contact from "@/components/Contact.vue";
import Dcategory from "@/components/Dcategory.vue";
import Footer from "@/components/Footer.vue";
import Home from "@/components/Home.vue";
import Doctors from "@/components/Doctors.vue";
import TopNav from "@/components/TopNav.vue";
</script>

<template>
  <header class="header">
    <TopNav />
    <Home />
  </header>
  <main>
    <section class="p-5 md:p-0">
      <Service />
    </section>
   <section >
     <Doctors />
   </section>
    <Dcategory />
    <Contact />
  </main>
  <footer>
   <Footer />
  </footer>
</template>
