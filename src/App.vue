<script setup lang="ts">
import CollectionSection from './components/CollectionSection.vue';
import Header from './components/Header.vue';
import HeroSection from './components/HeroSection.vue';
import MediaReviewSection from './components/MediaReviewSection.vue';
import NavBar from './components/NavBar.vue';
import RecommendationsSection from './components/RecommendationsSection.vue';
import SocialMediaReviewSection from './components/SocialMediaReviewSection.vue';
import TopBillingCastSection from './components/TopBillingCastSection.vue';
// import TopBilledCast from './components/topBilledCast/TopBilledCast.vue';
</script>

<template>
  <div class="flex w-full h-full flex-col ">
    <Header />
    <!-- nav bar -->
    <NavBar />

    <!-- Hero section -->
    <HeroSection />


    <div class="bg-white">

      <div class=" flex items-start gap-x-7 justify-start px-10 py-8 w-full max-w-[1400px]">

        <div class=" relative  ">

          <!-- top billed cast -->
          <TopBillingCastSection />

          <!-- social reviews -->
          <SocialMediaReviewSection />

          <!-- media reviews -->
          <MediaReviewSection />

          <!-- Video slider section
          <section class="flex flex-col mt-5 border-1 border-gray-200 w-full ">
           

          </section> -->

          <!-- collection section -->
          <CollectionSection />

          <!-- Recommendations section -->
          <RecommendationsSection />

        </div>

        <div class="min-w-[260px] text-black w-[260px] flex flex-col">

          <div class="flex gap-x-4 items-center mt-24 mb-5">
            <span class="text-black">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-instagram"><rect width="20" height="20" x="2" y="2" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/><line x1="17.5" x2="17.51" y1="6.5" y2="6.5"/></svg>
            </span>
            
            <span class="text-black">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-twitter"><path d="M22 4s-.7 2.1-2 3.4c1.6 10-9.4 17.3-18 11.6 2.2.1 4.4-.6 6-2C3 15.5.5 9.6 3 5c2.2 2.6 5.6 4.1 9 4-.9-4.2 4-6.6 7-3.8 1.1 0 3-1.2 3-1.2z"/></svg>
            </span>
            <span class="text-black">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-facebook"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"/></svg>
            </span>
            <span class="text-black">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"/><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"/></svg>
            </span>
          </div>

          <div class="flex flex-col gap-y-4">

            <p class="flex flex-col text-sm">
              <strong>Status</strong> Released
            </p>

            <p class="flex flex-col text-sm"><strong>Original Language</strong> English</p>

            <p class="flex flex-col text-sm"><strong>Budget</strong> $200,000,000.00</p>
            <p class="flex flex-col text-sm"><strong>Revenue</strong> $863,756,051.00</p>

          </div>

        </div>

      </div>



    </div>

  </div>
</template>
