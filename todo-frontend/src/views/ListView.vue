<template>
  <!-- views folder sluzi da se objedini nekoliko komponenti u celoviti prikaz -->
  <div>
    <!--3. Renderujemo komponentu -->
    <span>TEST 123</span>
    <navbar />
    <list />
  </div>
</template>

<script>
// Redosled ukljucivanja komponentni je sledeci:
// 1. importujemo komponentu
import navbar from "@/components/Navbar.vue";
import list from "@/components/List.vue";
export default {
  // 2. registrujemo komponentu
  components: {
    navbar,
    list
  }
};
</script>

<style scoped>
</style>
