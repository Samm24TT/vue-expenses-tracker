<template>
    <h4>Your balance</h4>
    <p id="balance">${{ total }}</p>
</template>

<script setup> 
    import { defineProps } from 'vue';

    const props = defineProps ({
        total: {
            type: Number,
            requried: true,
        }
    });
</script>