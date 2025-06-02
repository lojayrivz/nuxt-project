<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quos, quam dolore delectus quo excepturi impedit explicabo itaque accusamus illum ipsam?</p>
    </div>
</template>

<script setup>
    // export default {
        
    // }
    const { id } = useRoute().params

    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>