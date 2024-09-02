<template>
    <div>
        <h2>Product Details for {{ id }}</h2>
        <p>Lorem ipsum dolor sit amet</p>
    </div>
</template>

<script setup>
    const {id} = useRoute().params

    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>

