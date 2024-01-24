<template>
  <header class="header flex justify-between px-20 py-6">
    <h1 class="text-[#3563E9] text-[32px] font-bold">DM</h1>
    <input type="text" />
    <p>heart icon</p>
  </header>
</template>

<script setup lang="ts">
</script>

<style scoped>
.logo {
  color: var(--Primary-500, #3563e9);

  /* Bold/Type@32 */
  font-family: "Plus Jakarta Sans";
  font-size: 32px;
  font-style: normal;
  font-weight: 700;
  line-height: 150%; /* 48px */
  letter-spacing: -0.96px;
}

.header {
  border: 1px solid rgba(195, 212, 233, 0.4);
  background: var(--Primary-0, #fff);
}
</style>