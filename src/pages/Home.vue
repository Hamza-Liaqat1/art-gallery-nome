<script setup lang="ts"></script>

<template>
  <div class="relative h-screen w-screen">
    <video
      src="/gallery-gradient.mp4"
      muted
      playsinline
      loop
      autoplay
      preload="auto"
      class="min-w-full min-h-full object-cover fixed z-0"
    ></video>

    <div
      class="w-full h-full z-10 relative flex flex-col items-center justify-center"
    >
      <div class="relative flex flex-col items-center">
        <h1
          class="absolute -top-16 uppercase text-white text-4xl text-center flex justify-between w-3/4 max-w-[24rem] sm:w-full mx-auto"
        >
          <span v-for="item in 'Gallery'.split('')">{{ item }}</span>
        </h1>
        <img
          src="../assets/images/logo-white.png"
          alt=""
          class="w-3/4 max-w-[24rem] sm:w-full mx-auto mt-8 hover:opacity-0 transition-all ease-in"
        />
      </div>
      <div
        class="fixed bottom-0 w-full flex justify-between pb-10 text-white text-xl px-4 sm:px-12 flex-wrap"
      >
        <div class="capitalize">Dec 2023</div>
        <div class="capitalize">Miami art basel</div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
