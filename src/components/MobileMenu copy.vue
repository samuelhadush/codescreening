<script setup lang="ts">
import {
  Sheet,
  SheetContent,
  SheetTrigger,
} from '@/components/ui/sheet'
</script>

<template>
    <Sheet>
        <SheetTrigger as-child>
            <div class="p-2 text-white">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                    stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                    class="lucide lucide-align-justify">
                    <path d="M3 12h18" />
                    <path d="M3 18h18" />
                    <path d="M3 6h18" />
                </svg>
            </div>
        </SheetTrigger>
        <SheetContent :showCloseButton="false" side="left" class=" bg-[#032541e6]  border-r-0 ring-offset-0 ring-0 backdrop-blur-lg top-16 w-[calc(100vw-40px)]">
            <!-- <SheetHeader>
                <SheetTitle>Edit profile</SheetTitle>
                <SheetDescription>
                    Make changes to your profile here. Click save when you're done.
                </SheetDescription>
            </SheetHeader> -->
            <div class="flex flex-col justify-start items-start">

                <ul class="flex flex-col gap-y-4">
                    <li class="flex flex-col gap-y-4">
                        <a class="text-white font-medium text-lg" href="/movie" aria-label="Movies">Movies</a>
                        <ul class="text-gray-400 flex flex-col gap-y-1">
                            <li><a href="/movie" aria-label="Popular">Popular</a></li>
                            <li><a href="/movie/top-rated" aria-label="Top Rated">Top Rated</a></li>
                            <li><a href="/movie/upcoming" aria-label="Upcoming">Upcoming</a></li>
                            <li><a href="/movie/now-playing" aria-label="Now Playing">Now Playing</a></li>
                        </ul>
                    </li>
                    <li class="flex flex-col gap-y-4">
                        <a class="text-white font-medium text-lg" href="/tv" aria-label="TV Shows">TV Shows</a>
                        <ul class="text-gray-400 flex flex-col gap-y-1">
                            <li><a href="/tv" aria-label="Popular">Popular</a></li>
                            <li><a href="/tv/top-rated" aria-label="Top Rated">Top Rated</a></li>
                            <li><a href="/tv/on-the-air" aria-label="On TV">On TV</a></li>
                            <li><a href="/tv/airing-today" aria-label="Airing Today">Airing Today</a></li>
                        </ul>
                    </li>
                    <li class="flex flex-col gap-y-4">
                        <a class="text-white font-medium text-lg" href="/person" aria-label="People">People</a>
                        <ul class="sub_menu person hide">
                            <li><a class="text-gray-400 font-medium "  href="/person" aria-label="Popular People">Popular People</a></li>
                        </ul>
                    </li>
                </ul>
                <div class="grid grid-cols-4 items-center gap-4">
                </div>
                <div class="grid grid-cols-4 items-center gap-4">

                </div>
            </div>
        </SheetContent>
    </Sheet>
</template>