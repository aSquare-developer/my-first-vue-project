<script setup>
import { useFlash } from "@/composables/useFlash";

let { flash } = useFlash();
</script>
<template>
  <div>
    <p>
      <button @click="flash('Ops!', 'It Works on the About Page!', 'info')">Click me!</button>
    </p>
  </div>
</template>