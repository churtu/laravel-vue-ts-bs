<template>
    <h1>Hola {{ nombre }}</h1>
    <button class="btn btn-primary">hola</button>
</template>

<script lang="ts" setup>
    import { ref } from 'vue';
    const nombre = ref<string>('Hola gato');

</script>
