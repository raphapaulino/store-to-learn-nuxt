<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc congue suscipit auctor. Ut suscipit turpis vel convallis vulputate. Quisque sem enim, congue non luctus quis, euismod nec massa.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc congue suscipit auctor. Ut suscipit turpis vel convallis vulputate. Quisque sem enim, congue non luctus quis, euismod nec massa.</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
    // const { data } = await useFetch('/api/ninja?name=mario', {
    //     method: 'post',
    //     body: { age: 30 }
    // })
    const { data } = await useFetch('/api/currency/BRL')
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