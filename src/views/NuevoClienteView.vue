<script setup>
    import RouterLink from '@/components/UI/RouterLink.vue';
    import Heading from './Heading.vue';
</script>


<template>
    <div>
        <div class="flex justify-end">
            <RouterLink to="/">
                Volver
            </RouterLink>
        </div>

        <Heading>Agregar Clientes</Heading>
    </div>
</template>


<style scoped>
</style>