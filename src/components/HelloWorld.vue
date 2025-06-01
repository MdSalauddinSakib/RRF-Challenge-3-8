<template>
  <!-- Header Section -->
  <header>
    <!-- Navbar -->
    <nav class="bg-white shadow-xs">
      <div class="container mx-auto flex justify-between items-center py-4 font-roboto">

        <!-- logo -->
        <div class="flex items-center gap-2">
          <img class="w-11" src="../assets/img/logo.png" alt="">
          <div class="flex flex-col items-end">
            <p class="text-lg font-bold">Plumber Point</p>
            <p class="text-[#DD3142] font-bold text-sm leading-tight">Company</p>
          </div>
        </div>

        <!-- menu -->
        <ul class="flex items-center gap-6 text-sm font-medium">
          <li>
            <a class="nav" href="#">Home</a>
          </li>
          <li>
            <a class="nav" href="#">About us</a>
          </li>
          <li>
            <a class="nav" href="#">Services</a>
          </li>
          <li>
            <a class="nav" href="#">Project</a>
          </li>
          <li>
            <a class=" nav" href="#">Blogs</a>
          </li>
          <li class="">
            <a class="nav" href="#">Contact</a>
          </li>
          <li>
            <a href="#"
              class="bg-[#DD3142] text-white font-bold uppercase text-xs px-2 py-3 rounded-md hover:bg-red-600 transition">Request
              a call Back</a>
          </li>
        </ul>
      </div>
    </nav>
    <!-- Navbar end -->

    <!-- Hero Section -->
    <div class="container mx-auto flex items-center justify-between pt-12">
      <!-- left side -->
      <div class="font-Bricolage w-1/2">
        <h2 class="font-bold text-[44px] leading-12">Call us For Any <br>
          <span class="font-light">Plumbing Needs</span>
        </h2>
        <p class="font-extrabold text-[34px] my-4">+1800-9938-2839 </p>
        <button
          class="bg-[#DD3142] text-white uppercase text-base px-4 py-3 rounded-4xl hover:bg-red-600 transition cursor-pointer font-Roboto">See
          All Service</button>
      </div>

      <!-- right side -->
      <div class="flex items-center gap-4 w-1/2">
        <img class="w-full object-contain max-w-[302px]" src="../assets/img/image1.png" alt="">
        <img class="w-full object-contain max-w-[390px]" src="../assets/img/image2.png" alt="">
      </div>
    </div>
  </header>



</template>

<style scoped></style>