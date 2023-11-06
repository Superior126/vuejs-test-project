<script setup>
    // Import Libraries 
    import { ref } from 'vue';
</script>

<script>
    // Declare count ref
    const count = ref(0); 

    // Function to update count
    function update_count() {
        count.value++ 
    }
</script>

<template>
    <h1>Count: {{ count }}</h1>
    <button @click="update_count"> +1 </button>
</template>