<template>
  
</template>

<script setup>
import {computed, onMounted, reactive, ref} from "vue";

onMounted(() => {
  if (typeof cef != "undefined") {
    cef.emit("game:hud:setComponentVisible", "interface", false);

  }
})

</script>

<style lang="scss">
</style>
