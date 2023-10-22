<template>
    <div class="text-[#353535] w-[360px]">
        <p class="font-bold text-[24px]">{{ judul }}</p>
        <p class="date text-[11px] font-normal"> {{ date }}</p>
        <p class="content text-[11px] mt-[10px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque nulla minima mollitia vitae non corrupti consectetur ratione expedita, provident impedit ad doloribus unde sunt quos labore quibusdam cumque vel quia!</p>
        <div class="more flex items-center justify-end mt-[10px]">
            <p class="font-semibold text-[12px] mt-0 ml-2">Selengkapnya</p>
            <svg class="w-5 ml-2" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg">
                <g data-name="Layer 2" id="Layer_2">
                    <path class="cls-1" d="M16.88,15.53,7,5.66A1,1,0,0,0,5.59,7.07l9.06,9.06-8.8,8.8a1,1,0,0,0,0,1.41h0a1,1,0,0,0,1.42,0l9.61-9.61A.85.85,0,0,0,16.88,15.53Z"/>
                    <path class="cls-1" d="M26.46,15.53,16.58,5.66a1,1,0,0,0-1.41,1.41l9.06,9.06-8.8,8.8a1,1,0,0,0,0,1.41h0a1,1,0,0,0,1.41,0l9.62-9.61A.85.85,0,0,0,26.46,15.53Z"/>
                </g>
            </svg>
        </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
        judul: String,
        date: String,
        image: String,
    },
  };
  </script>
  