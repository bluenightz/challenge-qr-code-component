<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup

import qrcode from "./assets/image-qr-code.png";
</script>

<template>
  <div class="min-h-[100vh] flex justify-center items-center">
    <div class="bg-white p-5 rounded-3xl max-w-sm text-center shadow-2xl">
      <div class="relative w-full pt-[100%]">
        <img
          :src="qrcode"
          alt=""
          class="rounded-xl absolute w-full h-full top-0 object-fill"
        />
      </div>
      <div class="px-3 space-y-3 my-5">
        <h1 class="text-brand-dark-blue font-bold text-xl">
          Improve you front-end skills by building projects
        </h1>
        <p class="text-brand-grayish-blue text-base">
          Scan the QR code to visit Frontend Mentor and take your coding skills
          to the next level
        </p>
      </div>
    </div>
  </div>
</template>
