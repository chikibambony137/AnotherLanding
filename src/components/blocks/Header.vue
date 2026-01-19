<template>
  <div class="w-full outline-1 outline-gray-300">
    <div class="md:container md:mx-auto xl:px-60 px-5 py-4 flex justify-between items-center gap-x-8">
        <a id="logo" class=" text-2xl text-[#02996e] font-bold" href="/">Alivio</a>
    
        <div class="flex gap-x-16 flex-wrap">
            <a href="/">Why Alivio</a>
            <a href="/">Solutions</a>
            <a href="/">Community</a>
            <a href="/">Pricing</a>
        </div>
    
        <div class="flex gap-x-10 flex-wrap items-center">
            <a href="/">Sign in</a>
            <DefaultButton class=" rounded-sm">Start Trial</DefaultButton>
        </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import DefaultButton from '../buttons/DefaultButton.vue';
</script>

<style>

</style>