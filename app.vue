<template>
  <div class="flex flex-col gap-16">
    <Header></Header>
    <router-view></router-view>
  </div>
</template>

<script>
import AppAlert from './components/Header.vue';

export default {
  name: "App",
};
</script>