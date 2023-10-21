<template>
    <div>
        <div class="{{ className }} border-l-[6px] border-l-red-700 border-solid h-full">
            <span class="font-bold text-[#063556] text-[24px] bg-[#E3E4E6] pt-3 pb-3 pl-[50px] pr-[150px] h-full"> {{ title }} </span>
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            className: String,
            title: String,
        },
    }
</script>

<style scoped>

</style>