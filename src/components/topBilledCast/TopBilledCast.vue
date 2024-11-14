<script setup lang="ts">
import { Carousel, CarouselContent, CarouselItem, CarouselNext, CarouselPrevious } from '@/components/ui/carousel'
</script>

<template>
  <Carousel class="relative w-full max-w-full" :opts="{
      align: 'start',
    }">
    <CarouselContent>
      <CarouselItem v-for="(_, index) in 5" :key="index" class="md:basis-1/2 lg:basis-1/3">

        <div class="card  w-[140px] min-w-[140px] border border-slate-400 rounded-lg overflow-hidden text-black">
          <a class="h-[175px] w-[138px] min-w-[138px]" href="/person/73457-chris-pratt">
            <div class="glyphicons_v2 picture grey profile no_image_holder two">
              <img loading="lazy" class="h-full w-full"
                src="https://media.themoviedb.org/t/p/w138_and_h175_face/6DdoTgW9jdJwDmVFZRP8D0AtVFs.jpg"
                alt="Chris Pratt">

            </div>
          </a>

          <p class="pt-2.5 px-2.5 font-semibold"><a href="/person/73457-chris-pratt">Chris Pratt</a></p>
          <p class="px-2.5 font-light text-sm">Peter Quill / Star-Lord</p>
        </div>
      </CarouselItem>
    </CarouselContent>
    <CarouselPrevious />
    <CarouselNext />
  </Carousel>
</template>