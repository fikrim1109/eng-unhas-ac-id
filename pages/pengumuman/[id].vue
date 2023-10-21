<template>
    <div>
        <p>Pengumuman {{ id }}</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Animi, at laudantium. Quam, commodi ex. Ratione unde, quas nisi provident cupiditate voluptates! Voluptatum vel corporis blanditiis, sint earum ea amet minus.</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
</script>

<style lang="scss" scoped>

</style>