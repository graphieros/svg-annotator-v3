<script setup>
  import SvgAnnotator from './components/SvgAnnotator.vue';
</script>

<template>
  <main>
    <SvgAnnotator showPrint>
     <slot></slot>
    </SvgAnnotator>
  </main>
</template>
