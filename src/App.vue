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
  <div class="flex max-w-screen overflow-hidden w-full h-full flex-col ">
    <Header />
    <!-- nav bar -->
    <NavBar />

    <!-- Hero section -->
    <HeroSection />


    <div class="bg-white pb-20 md:pb-0">

      <div class=" flex items-start gap-x-7 md:flex-row flex-col justify-start px-4 py-6 md:px-10  md:py-8 w-full max-w-[1400px]">

        <div class=" relative w-full ">

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

        <div class="md:min-w-[260px] text-black md:w-[260px] w-full flex flex-col">

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
    <footer class="bg-background flex flex-col justify-center gap-y-8 w-full  px-4 py-20 text-foreground">
        <nav class=" flex md:flex-row flex-col w-full md:mx-auto justify-start items-start gap-y-4 md:gap-x-20" >
          <div class=" flex md:w-1/3 md:items-end md:gap-y-8 flex-col md:justify-between mb-10">
            <img class="hidden md:block" src="https://www.themoviedb.org/assets/2/v4/logos/v2/blue_square_2-d537fb228cf3ded904ef09b136fe3fec72548ebc1fea3fbbd1ad9e36364db38b.svg" alt="The Movie Database (TMDB)" width="130" height="94">
  
              <a class="rounded-lg h-fit bg-white text-[#235ea7] font-semibold text-lg px-8 py-4" href="/signup">Join the Community</a>
          </div>
  
          <div class=" flex  md:flex-row gap-x-8 flex-col w-full  justify-start items-start gap-y-4" >

            <div class="flex flex-col gap-y-2">
              <h3 class="text-lg font-bold">The Basics</h3>
              <ul>
                <li><a href="/about">About TMDB</a></li>
                <li><a href="/about/staying-in-touch">Contact Us</a></li>
                <li><a href="/talk">Support Forums</a></li>
                  <li><a href="https://developer.themoviedb.org/docs" target="_blank">API</a></li>
                <li><a href="https://status.themoviedb.org/" target="_blank" rel="noopener">System Status</a></li>
              </ul>
            </div>

            <div class="flex flex-col gap-y-2">
              <h3 class="text-lg font-bold">Get Involved</h3>
              <ul>
                <li><a href="/bible"><span class="glyphicons glyphicons-asterisk"></span> Contribution Bible</a></li>
                <li><a href="/movie/new">Add New Movie</a></li>
                <li><a href="/tv/new">Add New TV Show</a></li>
              </ul>
            </div>
            <div class="flex flex-col gap-y-2">
              <h3 class="text-lg font-bold">Community</h3>
              <ul>
                <li><a href="/documentation/community/guidelines">Guidelines</a></li>
                <li><a href="/discuss">Discussions</a></li>
                <li><a href="/leaderboard">Leaderboard</a></li>
              </ul>
            </div>
            <div class="flex flex-col gap-y-2">
              <h3 class="text-lg font-bold">Legal</h3>
              <ul>
                <li><a href="/terms-of-use">Terms of Use</a></li>
                <li><a href="/api-terms-of-use">API Terms of Use</a></li>
                <li><a href="/privacy-policy">Privacy Policy</a></li>
                <li><a href="/dmca-policy">DMCA Policy</a></li>
              </ul>
            </div>
          </div>
        </nav>
  
        <section class=" self-center ">Build 85e6c70 (8179)</section>
      </footer>

  </div>

</template>
