<template>
  <div class="md:container md:mx-auto xl:px-60 px-5 xl:pt-20 py-10">
    <div class="grid sm:grid-cols-[3fr_4fr]">
      <div>
        <h1>How it works</h1>
        <h2 class="text-4xl text-[#01996d] font-bold leading-normal">
          Understand & Release the stress in 3 steps
        </h2>
      </div>

      <div class="py-8 md:pl-6 lg:pl-20">
        <p>
          Alivio offers as many journals it takes, tackling different areas such
          as anxiety, overwhelmedness, sadness, or anger, and a variety of
          personal causes, to help you become aware of your emotions, and guide
          you in how to manage stress.
        </p>
      </div>
    </div>

    <div class="grid md:grid-cols-3 gap-10 md:gap-20">
      <Step
        :num="1"
        title="Personalize"
        description="Answer a quick survey about how you express yourself, what causes you stress, 
                        and what area would you like to work on. This way, we can fully personalize your journal!"
        img="bg/bg_step1.png"></Step>
      <Step
        class="xl:mt-40 md:mt-20"
        :num="2"
        title="Write & Understand"
        description="Write, draw, reflect, understand. Alivio will guide you through the prompts and
                        will help you manage your stress!"
        img="bg/bg_step2.png"></Step>
      <Step
        :num="3"
        title="Alivio!"
        description="Now you are aware, and have a way to manage and overcome your own stress.
                        What are you waiting for? Alivio today!"
        img="bg/bg_step3.png"></Step>
    </div>
  </div>
</template>

<script lang="ts" setup>
import Step from "../blocks/Step.vue";
</script>

<style></style>
