<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque maiores rem voluptatem aliquam totam quidem, omnis veniam nam aliquid ipsum.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque maiores rem voluptatem aliquam totam quidem, omnis veniam nam aliquid ipsum.</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
    const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }

    p {
        margin: 20px 0;
    }

</style>