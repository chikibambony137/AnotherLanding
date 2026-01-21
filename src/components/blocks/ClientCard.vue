<template>
  <div class="flex flex-col justify-center items-center gap-5 min-w-75 min-h-75 py-8 shadow-lg p-4 bg-white rounded-md">
    <h1 class=" border-b-2 border-black px-2 py-2">{{ props.title }}</h1>
    <div :style="{ backgroundImage: `url(${props.img})`, backgroundSize: '210% auto', backgroundPosition: '50% 35%' }" 
     class="w-20 h-20 bg-no-repeat rounded-[100%]">

    </div>
    <p>{{ props.clientName }}</p>

    <slot> </slot>
  </div>
</template>

<script lang="ts" setup>
const props = defineProps({
  title: {
    type: String,
    required: false,
    default: "Best Client",
  },
  img: {
    type: String,
    required: true,
  },
  clientName: {
    type: String,
    required: true,
  },
});
</script>

<style></style>
