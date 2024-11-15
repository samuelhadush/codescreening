<script setup lang="ts">

import { type HTMLAttributes } from 'vue'
interface PropsType {
    class?: HTMLAttributes['class']
    scorePercentage?: number

}
const props = defineProps<PropsType>()
const { class: _, scorePercentage = 0 } = props

</script>
<template>

    <div class=" md:hidden flex px-4 items-center gap-x-2 w-full justify-between">
        <div class="flex items-center text-white justify-start w-full ">

            <!-- user score progress bar -->
            <div class="relative w-20 h-20 rounded-full p-1">
                <div class="rounded-full bg-[#081c22]">
                    <svg class="w-full h-full" viewBox="0 0 100 100">
                        <!-- Background circle -->
                        <circle class="text-[#204529] stroke-current" stroke-width="6" cx="50" cy="50" r="40"
                            fill="transparent"></circle>
                        <!-- Progress circle -->
                        <circle class="text-[#21d07a]  progress-ring__circle stroke-current" stroke-width="4"
                            stroke-linecap="round" cx="50" cy="50" r="40" fill="transparent" stroke-dasharray="251.2"
                            :stroke-dashoffset="`calc(251.2 - (251.2 * ${scorePercentage}) / 100)`"
                            transform="rotate(-90 50 50)"></circle>
                        <!-- Rotate to start at the top -->
                    </svg>
                    <span
                        class=" absolute top-0 right-0 left-0 bottom-0 inset-0 flex items-center justify-center font-bold text-white">{{
                            scorePercentage }}%</span>
                </div>
            </div>


            <span class="font-bold ml-1">
                User <br> Score
            </span>



        </div>

        <div>
            <ul class="flex items-center">
                <li class="bg-[#032541] h-8 w-8 flex rounded-full text-white items-center text-3xl justify-center ">
                    😄
                </li>
                <li
                    class="bg-[#032541] h-8 w-8 -ml-3 flex rounded-full text-white items-center text-3xl justify-center ">
                    😍
                </li>
            </ul>
        </div>

        <div
            class=" flex bg-[#032541] rounded-l-full  font-bold p-2 pl-3 text-white cursor-pointer items-center rounded-r-full py-1.5 px-2 hover:scale-105 transition ease-in-out duration-150 ">
            <div class="flex flex-nowrap items-center whitespace-nowrap">
                what's your
                <span class="flex pl-1 underline underline-offset-2 decoration-2 decoration-sky-400">
                    vibe
                </span>
                ? <span class=" pl-1 text-[#032541]">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="white"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-info">
                        <circle cx="12" cy="12" r="10" />
                        <path d="M12 16v-4" />
                        <path d="M12 8h.01" />
                    </svg>
                </span>
            </div>
        </div>

    </div>

    <!-- score -->
    <div class=" hidden md:flex items-center gap-x-2 justify-start">
        <div class="flex items-center text-white justify-start ">

            <!-- user score progress bar -->
            <div class="relative w-20 h-20 rounded-full p-1">
                <div class="rounded-full bg-[#081c22]">
                    <svg class="w-full h-full" viewBox="0 0 100 100">
                        <!-- Background circle -->
                        <circle class="text-[#204529] stroke-current" stroke-width="6" cx="50" cy="50" r="40"
                            fill="transparent"></circle>
                        <!-- Progress circle -->
                        <circle class="text-[#21d07a]  progress-ring__circle stroke-current" stroke-width="4"
                            stroke-linecap="round" cx="50" cy="50" r="40" fill="transparent" stroke-dasharray="251.2"
                            stroke-dashoffset="calc(251.2 - (251.2 * 70) / 100)" transform="rotate(-90 50 50)"></circle>

                        <!-- Rotate to start at the top -->

                    </svg>
                    <span
                        class=" absolute top-0 right-0 left-0 bottom-0 inset-0 flex items-center justify-center font-bold text-white">70%</span>
                </div>
            </div>


            <span class="font-bold ml-1">
                User <br> Score
            </span>



        </div>

        <div>
            <ul class="flex items-center">
                <li class="bg-[#032541] h-8 w-8 flex rounded-full text-white items-center text-3xl justify-center ">
                    😄
                </li>
                <li
                    class="bg-[#032541] h-8 w-8 -ml-3 flex rounded-full text-white items-center text-3xl justify-center ">
                    😍
                </li>
            </ul>
        </div>

        <div
            class=" flex bg-[#032541] rounded-l-full  font-bold p-2 pl-3 text-white cursor-pointer items-center rounded-r-full py-1.5 px-2 hover:scale-105 transition ease-in-out duration-150 ">
            <div class="flex flex-nowrap items-center whitespace-nowrap">
                what's your
                <span class="flex pl-1 underline underline-offset-2 decoration-2 decoration-sky-400">
                    vibe
                </span>
                ? <span class=" pl-1 text-[#032541]">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="white"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-info">
                        <circle cx="12" cy="12" r="10" />
                        <path d="M12 16v-4" />
                        <path d="M12 8h.01" />
                    </svg>
                </span>
            </div>
        </div>

    </div>


</template>