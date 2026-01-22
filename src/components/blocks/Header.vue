<template>
  <div class="w-full outline-1 outline-gray-300">
    <div class="grid grid-cols-[1fr_2fr] py-6 px-6 gap-y-4 gap-x-6
                    sm:grid-cols-[1fr_5fr_2fr] md:container md:mx-auto xl:px-60">
        <a id="logo" class="flex justify-center items-center text-2xl text-[#02996e] font-bold" href="/">Alivio</a>
    
        <div class="grid items-center justify-center grid-cols-2 lg:grid-flow-col gap-x-12 gap-y-2 md:grid-cols-4">
            <a href="/">Why Alivio</a>
            <a href="/">Solutions</a>
            <a href="/">Community</a>
            <a href="/">Pricing</a>
        </div>
    
        <div class="flex gap-x-10 gap-y-4 justify-center items-center col-span-2 sm:col-span-1 sm:flex-col lg:flex-row">
            <a href="/">Sign in</a>
            <DefaultButton>Start Trial</DefaultButton>
        </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import DefaultButton from '../buttons/DefaultButton.vue';
</script>

<style>

</style>