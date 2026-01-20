<template>
  <div class="">
    <div class="relative pt-22">
      <span id="number" class="absolute top-0 -z-1 text-9xl text-[#02996e3d]"
        >0{{ props.num }}</span
      >

      <h3 class="font-black text-2xl flex justify-center">{{ props.title }}</h3>

      <p class="my-13">
        {{ props.description }}
      </p>
    </div>
    <div>
      <img :src="props.img" alt="{{ img }}" />
    </div>
  </div>
</template>

<script lang="ts" setup>
const props = defineProps({
  num: {
    type: Number,
    required: false,
    default: 0,
  },
  title: {
    type: String,
    required: false,
    default: "Very original title!",
  },
  description: {
    type: String,
    required: false,
    default: "Something interesting...",
  },
  img: {
    type: String,
    required: false,
    default: "bg_step1.png",
  },
});
</script>

<style></style>
