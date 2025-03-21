<script setup lang="ts">
import Clarity from "@microsoft/clarity";

onMounted(() => {
  Clarity.init("qr36jhd7tr");
});
</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
