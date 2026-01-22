<template>
  <div
    :style="{ backgroundImage: `url(${bgImage})` }"
    class="w-full min-h-170 bg-size-[auto_100%] bg-position-[60%_35%] sm:bg-cover sm:bg-center bg-no-repeat">
    <div class="md:container md:mx-auto xl:px-60 px-5 xl:pt-32 pt-10">
      <div class="grid gap-10">
        <h2 class="text-5xl sm:text-6xl text-[#01996d] font-bold mb-40 sm:mb-0">
          Be aware, <br />
          Manage well.
        </h2>

        <div class="bg-[#ffffff96] p-4 sm:bg-transparent sm:p-0">
          <p>Everyone experiences stress in different ways.</p>
          <p>
            Let Alivio guide you, in a personalized journal <br />
            experience, to overcome your stress.
          </p>
        </div>

        <DefaultButton class="py-3 w-48">Find Your Way</DefaultButton>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import DefaultButton from "../buttons/DefaultButton.vue";
import bgImage from "../../assets/bg_hero.png";
</script>

<style></style>
