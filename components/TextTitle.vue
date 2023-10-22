<template>
    <div class="border-l-[#EB2629] border-l-[10px] border-solid w-[400px]">
        <p class="bg-[#E3E4E6] text-[24px] font-bold text-[#063556] p-[15px] w-[400px] pl-[37px]">{{ textTitle }}</p>
    </div>
</template>

<script>
    export default {
        props: {
            textTitle: String,
        },
    }
</script>

<style lang="scss" scoped>

</style>