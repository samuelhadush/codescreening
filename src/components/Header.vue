<script setup lang="ts">
import MobileMenu from './MobileMenu.vue';

import HeaderMenu from './ui/HeaderMenu.vue';
</script>

<template>
    <header class=" hidden md:flex static top-0 w-full justify-center h-16 bg-brand text-brand-foreground">
        <div class="flex w-full justify-between max-w-[1400px] h-full px-10">
            <div class="flex items-center gap-x-8">
                <div>
                    <a href="https://www.themoviedb.org/">
                        <img src="https://www.themoviedb.org/assets/2/v4/logos/v2/blue_short-8e7b30f73a4020692ccca9c88bafe5dcb6f8a62a4c6bc55cd9ba82bb2cd95f6c.svg"
                            alt="The Movie Database (TMDB)" width="154" height="20" />
                    </a>
                </div>
                <ul class="flex items-center gap-x-8">
                    <HeaderMenu />
                    
                </ul>
            </div>
            <ul class="flex items-center gap-x-8">
                <li class="text-white font-semibold">
                    <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-plus">
                        <path d="M5 12h14" />
                        <path d="M12 5v14" />
                    </svg>

                </li>
                <li class="  p-1 px-2 h-8 flex items-center justify-center border border-white rounded-[4px]">en </li>
                <li class="font-semibold">Login</li>
                <li class="font-semibold ">Join TMDB</li>
                <li class="font-semibold text-[#06b4e4] ">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-search">
                        <circle cx="11" cy="11" r="8" />
                        <path d="m21 21-4.3-4.3" />
                    </svg>
                </li>
            </ul>

        </div>

    </header>
    <div class=" block md:hidden">
        <header
            class=" md:hidden flex static top-0 w-full items-center justify-between h-16 px-5 bg-brand text-brand-foreground">
            <MobileMenu side="left" class="" />
            <a class="text-sm" href="https://www.themoviedb.org/">
                <img src="https://www.themoviedb.org/assets/2/v4/logos/v2/blue_square_2-d537fb228cf3ded904ef09b136fe3fec72548ebc1fea3fbbd1ad9e36364db38b.svg"
                    alt="The Movie Database (TMDB)" width="55" height="40" />
            </a>
            <div class="flex gap-x-2 items-center ">
                <a class="text-white text-xs" href="https://www.themoviedb.org/">
                    <img class=" invert-[1] "
                        src="https://www.themoviedb.org/assets/2/v4/glyphicons/basic/glyphicons-basic-4-user-7de7dfcae838579a18f4eebc5b8847230d154718e481c5cd01c477cfcbc85993.svg"
                        alt="The Movie Database (TMDB)" width="30" height="27" />
                </a>

                <a class="font-semibold text-[#06b4e4] ">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-search">
                        <circle cx="11" cy="11" r="8" />
                        <path d="m21 21-4.3-4.3" />
                    </svg>
                </a>


            </div>
        </header>
    </div>
</template>