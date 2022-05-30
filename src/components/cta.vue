<template>
    <div class="flex container mx-auto items-center mt-20 justify-between relative min-h-[400px]">
<div class="flex flex-col">
    <p class="text-6xl font-bold capitalize">
        Let’s get you where <br>
        <span class="text-red-500">you need to be</span> 
    </p>
    <p class="max-w-[718px] mt-5 text-[#2D2D2D] text-lg leading-tight">Buy train tickets easily without needing to leave your home. You can either book a single one way ticket or get a returnt ticket wit your order. </p>

<div class="flex items-center gap-5 mt-10">
    <label class="flex items-center cursor-pointer select-none">
      <div class="box flex items-center justify-center w-5 h-5 rounded border mr-2 ">
         <span class="bg-[#3B89FF] w-[10px] h-[10px] rounded-sm"></span>
      </div>
 single
</label>
    <label class="flex items-center cursor-pointer select-none">
      <div class="box flex items-center justify-center w-5 h-5 rounded border mr-2 ">
         <span class="bg-[#fff] w-[10px] h-[10px] rounded-sm"></span>
      </div>
 Return
</label>
</div>

<div class="flex items-stretch sha py-8 px-5 mt-5 gap-5 ">
    <div class="bg-[#F1F1F1] px-4 flex items-center py-1.5 w-full cursor-pointer">
        <div>
            <span class="text-xs mt-3 font-light">From ?</span>
            <p>Oyo</p>
        </div>
      <img src="../assets/down.svg" alt="icon" class="ml-auto">
    </div>
    <div class="bg-[#F1F1F1] px-4 flex items-center py-1.5 w-full cursor-pointer">
        <div>
            <span class="text-xs mt-3 font-light">To ?</span>
            <p>Lagos</p>
        </div>
      <img src="../assets/down.svg" alt="icon" class="ml-auto">
    </div>

    <div class="bg-[#F1F1F1] px-5 pr-3 flex flex-col items-start pb-2 w-full">
        <select name="" id="" aria-placeholder="From" class="bg-transparent text-black pr-6 m-0 p-0">
            <option value="">Today</option>
        </select>
    </div>
    <div class="bg-[#F1F1F1] px-5 pr-3 flex flex-col items-start pb-2 w-full">
        <select name="" id="" aria-placeholder="From" class="bg-transparent text-black pr-6 m-0 p-0">
            <option value="">1 Adult</option>
        </select>
    </div>
</div>

</div>

<img src="../assets/hero.png" alt="hero image" class="absolute -right-20"/>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.sha{
background: #FCFCFC;
box-shadow: 0px 1px 17px rgba(0, 22, 40, 0.15);
}
</style>