<script setup>
import {RouterView } from 'vue-router'
import NavbarMenu from './components/NavbarMenu.vue';

</script>

<template>
  <header>
     <NavbarMenu />
  </header>

  <RouterView class="px-2" />
</template>
