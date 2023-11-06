<script setup>
  // import Styles
  import './css/main.css';

  // Import Components
  import TestComponent from './components/TestComponent.vue';
  import Count from './components/Count.vue';
</script>

<template>
    <h1>Test</h1>
    <TestComponent :number="4" />
    <Count />
</template>
