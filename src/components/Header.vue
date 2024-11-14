<script setup lang="ts">
// import HeaderMenu from './ui/HeaderMenu.vue';
</script>

<template>
    <header class="flex static top-0 w-full justify-center h-16 bg-brand text-brand-foreground">
        <div class="flex w-full justify-between max-w-[1400px] h-full px-10">
            <div class="flex items-center gap-x-8">
                <div>
                    <a href="https://www.themoviedb.org/">
                        <img src="https://www.themoviedb.org/assets/2/v4/logos/v2/blue_short-8e7b30f73a4020692ccca9c88bafe5dcb6f8a62a4c6bc55cd9ba82bb2cd95f6c.svg" alt="The Movie Database (TMDB)" width="154" height="20"/>
                    </a>
                </div>
                <ul class="flex items-center gap-x-8">
                    <!-- <HeaderMenu/> -->
                    <li class="font-semibold cursor-pointer ">Movies</li>
                    <li class="font-semibold cursor-pointer ">TV Shop</li>
                    <li class="font-semibold cursor-pointer ">People</li>
                    <li class="font-semibold cursor-pointer ">More</li>
                </ul>
            </div>
            <ul class="flex items-center gap-x-8">
                <li class="text-white font-semibold">
                    <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="6" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-plus"><path d="M5 12h14"/><path d="M12 5v14"/></svg>
                
                </li>
                <li class="  p-1 px-2 h-8 flex items-center justify-center border border-white rounded-[4px]">en </li>
                <li class="font-semibold">Login</li>
                <li class="font-semibold ">Join TMDB</li>
                <li class="font-semibold text-[#06b4e4] ">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-search"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.3-4.3"/></svg>
                </li>
            </ul>

        </div>
    </header>
</template>