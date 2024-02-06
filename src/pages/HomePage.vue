<template>
  <div class="h-auto text-center space-y-20">
    <!-- the navbar  -->
    <NavBar />

    <!-- the header  -->
    <div class="space-y-5 mt-20 mx-auto">
      <h1 class="text-2xl font-bold">
        Build The Community Your Fans Will Love
      </h1>
      <p class="text-sm max-w-sm mx-auto">
        Huddle re-imagines the way we build communities. You have a voice, but
        so does your audience. Create connects with your user as you engage in
        genuine discussions.
      </p>
      <button
        class="bg-pink-500 text-white px-[60px] py-2 rounded-full shadow-lg mt-5"
      >
        Get Started For Free
      </button>
    </div>

    <!-- Image mockup  -->
    <div class="">
    <img src="@/assets/screen-mockups.svg" alt="" class="mx-auto md:max-w-2xl" />

    </div>
    <!-- data  -->
    <div class="flex justify-between max-w-2xl mx-auto">
      <div class="flex flex-col items-start gap-y-4">
        <img
          src="@/assets/icon-communities.svg"
          alt="icon"
          class="max-w-[30px]"
        />
        <h1 class="text-5xl font-bold">1.4k+</h1>
        <p class="text-md text-gray-400">Communities Formed</p>
      </div>

      <div class="flex flex-col items-start gap-y-4">
        <img src="@/assets/icon-messages.svg" alt="icon" class="max-w-[30px]" />
        <h1 class="text-5xl font-bold">1.4k+</h1>
        <p class="text-md text-gray-400">Message Sent</p>
      </div>
    </div>

    <!-- image  -->

    <div>
      <img src="@/assets/bg-section-top-desktop-1.svg" alt="" />
      <div class="bg-blue-100/30">
        <img
          src="@/assets/illustration-grow-together.svg"
          alt="image"
          class="md:max-w-2xl mx-auto"
        />
      </div>
      <img src="@/assets/bg-section-bottom-desktop-1.svg" alt="" />
    </div>

    <!-- image  -->
    <div>
      <img
      src="@/assets/illustration-flowing-conversation.svg"
      alt=""
      class="md:max-w-2xl mx-auto"
    />
    </div>

    <!-- img3 -->
    <div class="">
      <img src="@/assets/bg-section-top-desktop-1.svg" alt="" />
      <div class="bg-blue-100/30">
        <img
          src="@/assets/illustration-your-users.svg"
          alt="image"
          class="md:max-w-2xl mx-auto"
        />
      </div>
      <img src="@/assets/bg-section-bottom-desktop-1.svg" alt="" />
    </div>

    <!-- bottom  -->
    <div>
      <h1 class="text-2xl font-bold">Ready To Build Your Community?</h1>
      <button
        class="bg-pink-500 text-white px-[60px] py-2 rounded-full shadow-lg mt-5"
      >
        Get Started For Free
      </button>
    </div>

    <!-- the footer  -->
    <div class="">
      <img src="@/assets/bg-footer-top-desktop.svg" alt="image " />
      <div class=" bg-slate-800 md:grid grid-cols-2 px-5 space-y-5">
        <div class="md:ml-20 space-y-3">
          <img src="@/assets/logo.svg" alt="logo" class="text-white">
          <p class="text-sm text-white max-w-xs text-start">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris nulla quam, hendrenrit lacinia vesibulum a, ultirces quis sem.</p>
          <div class="flex gap-5 text-white text-sm">
            <img src="@/assets/icon-phone.svg" alt="">
            <p>Phone: +1-543-123-4567</p>
          </div>
          <div class="flex gap-5 text-white text-sm">
            <img src="@/assets/icon-email.svg" alt="">
            <p>hak.vichet19@kit.edu.kh</p>
          </div>

          <!-- icons -->
          <div>
            <img src="" alt="">
            <img src="" alt="">
            <img src="" alt="">
          </div>
        </div>

        <div class="flex flex-col text-white items-start gap-y-4 max-w-lg">
          <h1 class="font-bold">NEWSLETTER</h1>
          <p class="max-w-xs text-start">To reviece tips on how to grow your community. sign up to our weekly newsletter. We'll never send your spam or pass on your email address.</p> 
          <!-- <div class="flex flex-1"></div> -->
          <div class="flex gap-x-10 w-full mb-10">
            <div class="flex flex-1 p-2 bg-white rounded-sm"></div>
            <button class="px-5 py-2 bg-pink-500 rounded-sm">Subscribe</button>
          </div>
        </div>
        
      </div>
    </div>
  </div>
</template>

<script setup>
import NavBar from "@/components/NavBar.vue";
</script>
