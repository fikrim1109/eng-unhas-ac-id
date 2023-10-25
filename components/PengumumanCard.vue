<template>
    <div>
        <div class="{{ class }} w-[380px] pr-5 pl-5">
            <div class="head flex justify-between items-center pb-3">
                <p class="text-[#EB2629] font-bold text-[20px]"> {{ title }} </p>
                <p class="text-[11px] text-[#063556] font-medium "> {{ date }} </p>
            </div>
            <div class="content text-[11px] pb-3">
                <p>Lorem Ipsum is simply dummy text of the printing and
                typesetting industry. Lorem Ipsum has been the industry's 
                standard dummy text ever since the 1500s, when an 
                unknown printer took a galley of type and scrambled it to
                make a type specimen book. It has survived not only
                five centuries</p>
            </div>
            <div class="more flex items-center justify-end">
                <a href="" class="text-[#063D63] flex font-bold pr-3">Selengkapnya</a>
                <svg class="w-4 h-5" xmlns="http://www.w3.org/2000/svg" id="Bold" viewBox="0 0 24 24">
                    <path style="fill: #063D63;" d="M1.51,6.079a1.492,1.492,0,0,1,1.06.44l7.673,7.672a2.5,2.5,0,0,0,3.536,0L21.44,6.529A1.5,1.5,0,1,1,23.561,8.65L15.9,16.312a5.505,5.505,0,0,1-7.778,0L.449,8.64A1.5,1.5,0,0,1,1.51,6.079Z"/>
                </svg>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            class: String,
            title: String,
            date: String,
        },
    }
</script>

<style scoped>

</style>