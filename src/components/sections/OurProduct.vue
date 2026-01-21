<template>
  <div class="lg:pb-50 xl:pb-50 2xl:pb-40">
    <div class="px-5 py-10 md:container md:mx-auto lg:pt-20 xl:px-60">
      <div
        class="flex lg:grid lg:grid-cols-[4fr_3fr] gap-x-10 flex-col-reverse">
        <div class="block lg:relative">
          <img src="../../assets/client1.png" alt="client" />
          <ClientCard
          class=" lg:absolute lg:-left-10 lg:top-70"
            title="Customized For"
            img="clients/client1.png"
            clientName="Mikayla">
            <h3 class="text-xl font-bold">Your custom contents</h3>
            <ul class="list-disc grid gap-3">
              <li>Understand Your Stress</li>
              <li>Anger Management</li>
            </ul>
          </ClientCard>
        </div>

        <div class="py-5">
          <h1 class="text-xl mb-4">Our product</h1>
          <h2 class="text-4xl text-[#01996d] font-bold leading-normal">
            You tell us your stress, We make your diary
          </h2>
          <p class="xl:pr-30 mb-10">
            Everyone experiences it, and in different ways. Let Alivio guide
            you, in a personalized journal experience, to overcome your stress.
          </p>
          <DefaultButton class="py-3">Find Your Way</DefaultButton>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import DefaultButton from "../buttons/DefaultButton.vue";
import ClientCard from "../blocks/ClientCard.vue";
</script>

<style></style>
