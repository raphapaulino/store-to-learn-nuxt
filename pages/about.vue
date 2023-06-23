<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/">Nuxt Dojo</NuxtLink>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
                <a href="/about">normal link -- about page</a>
            </nav>
        </header>
        
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc congue suscipit auctor. Ut suscipit turpis vel convallis vulputate. Quisque sem enim, congue non luctus quis, euismod nec massa.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc congue suscipit auctor. Ut suscipit turpis vel convallis vulputate. Quisque sem enim, congue non luctus quis, euismod nec massa.</p>
    </div>
</template>

<script setup>

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