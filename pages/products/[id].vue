<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc congue suscipit auctor. Ut suscipit turpis vel convallis vulputate. Quisque sem enim, congue non luctus quis, euismod nec massa.</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
</script>

<style scoped>

</style>