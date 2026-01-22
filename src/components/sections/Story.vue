<template>
  <div
    class="bg-[#255953] ">
    <div class="md:container md:mx-auto xl:px-60 px-5 lg:py-40 py-20">
        <div class="grid lg:grid-cols-[2fr_3fr] gap-x-4">
          <div class="text-white pb-10">
            <h2 class="text-4xl font-bold leading-relaxed">
              Let's hear about Kayla's success story
            </h2>
            <p class="mt-5 mb-10">
              See how well Alivio works in a real customer’s life.
            </p>
            <DefaultButton class="py-3">Let’s get started</DefaultButton>
          </div>
    
          <div>
            <video class=" rounded-2xl" controls src="../../assets/video.mp4" type="video/mp4"></video>
          </div>
        </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import DefaultButton from "../buttons/DefaultButton.vue";
</script>

<style></style>
