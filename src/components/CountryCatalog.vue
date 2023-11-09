<script setup>
    import { ref } from "vue";
    const count = ref(0);
    async function increase() {
        count.value++
    }
</script>

<template>
    <button @click="increase">{{ count }}</button>
</template>

<style>

</style>