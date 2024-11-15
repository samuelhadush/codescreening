<script setup lang="ts">
import UserScoreWidget from './ui/userScoreWidget/UserScoreWidget.vue';

</script>
<template>
    <div
        class="  relative w-full md:bg-[url('https://media.themoviedb.org/t/p/w1920_and_h800_multi_faces/aJn9XeesqsrSLKcHfHP4u5985hn.jpg')]">

        <!-- Mobile -->
        <div class="flex md:hidden flex-col bg-banner-gradient">
            <div
                class="flex   w-[100vw] h-[calc(100vw/2.2222)] bg-cover justify-end min-w-[100vw] bg-[url('https://media.themoviedb.org/t/p/w1920_and_h800_multi_faces/aJn9XeesqsrSLKcHfHP4u5985hn.jpg')]">
                <div class="bg-banner-gradient flex justify-start px-5 py-3 items-center w-full h-full">
                    <!-- Mobile -->
                    <div class=" relative rounded-[8px] overflow-hidden h-full ">
                        <img alt="movie poster"
                            src="https://media.themoviedb.org/t/p/w300_and_h450_bestv2/y4MBh0EjBlMuOzv9axM4qJlmhzz.jpg"
                            class="h-full w-full object-contain " />
                    </div>

                </div>

            </div>
            <section class="w-full text-white mt-4  flex h-full">
                <div class="w-full   flex-col flex h-full">
                    <!-- title -->
                    <div class="flex px-4 flex-col gap-y-2 pb-5">
                        <h2 class="text-white space-x-1 text-[1.25rem]">
                            <a class="font-bold " href="/movie/283995-guardians-of-the-galaxy-vol-2">Guardians of
                                the Galaxy Vol.
                                2</a>
                            <span class="text-gray-300">(2017)</span>
                        </h2>

                    </div>

                    <!--user score widget  -->
                    <UserScoreWidget :scorePercentage="65" />

                    <!-- age mimit -->
                    <div class="flex w-full py-4 px-4 bg-[#0000001a] justify-center">
                        <div class="flex text-sm px-2 justify-start text-white gap-x-4 items-center">


                            <span class="border border-gray-300 px-2 text-gray-300">
                                PG-13
                            </span>

                            <div class="flex flex-col items-start justify-start">
                                <div class="flex gap-x-2 items-center justify-start">

                                    <span class="">
                                        05/05/2017 (US)
                                    </span>
                                    <span class="h-1 w-1 bg-white rounded-full"></span>

                                    <span class="">
                                        2h 17m
                                    </span>

                                    <a href="#"
                                        class=" flex gap-x-2 text-white font-semibold hover:text-white/70 flex-nowrap text-nowrap whitespace-nowrap items-center justify-start">
                                        <span><svg xmlns="http://www.w3.org/2000/svg" width="10" height="10"
                                                viewBox="0 0 24 24" fill="white" stroke="currentColor" stroke-width="2"
                                                stroke-linecap="round" stroke-linejoin="round"
                                                class="lucide lucide-play">
                                                <polygon points="6 3 20 12 6 21 6 3" />
                                            </svg></span>
                                        <span>Play Trailer</span>
                                    </a>


                                </div>
                                <span class=" flex items-center gap-x-1 ">
                                    <a class="text-white hover:text-gray-400"
                                        href="/genre/878-science-fiction/movie">Science
                                        Fiction</a>,&nbsp;<a class="text-white hover:text-gray-400"
                                        href="/genre/12-adventure/movie">Adventure</a>,&nbsp;<a
                                        class="text-white hover:text-gray-400" href="/genre/28-action/movie">Action</a>
                                </span>
                            </div>

                        </div>
                    </div>

                    <!-- actions -->
                    <ul class=" fixed bottom-0 z-20 bg-brand  w-full flex px-4 items-center justify-between gap-x-5 py-1 -mb-1">

                        <li>
                            <a href="#"
                                class="bg-[#032541] h-9 w-9 flex rounded-full text-white items-center justify-center ">
                                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="4" stroke-linecap="round"
                                    stroke-linejoin="round" class="lucide lucide-list">
                                    <path d="M3 12h.01" />
                                    <path d="M3 18h.01" />
                                    <path d="M3 6h.01" />
                                    <path d="M8 12h13" />
                                    <path d="M8 18h13" />
                                    <path d="M8 6h13" />
                                </svg>
                            </a>
                        </li>
                        <li>
                            <a href="#"
                                class="bg-[#032541] h-9 w-9 flex rounded-full text-white items-center justify-center ">
                                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24"
                                    fill="white" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="lucide lucide-heart">
                                    <path
                                        d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z" />
                                </svg>
                            </a>
                        </li>
                        <li>
                            <a href="#"
                                class="bg-[#032541] h-9 w-9 flex rounded-full text-white items-center justify-center ">
                                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24"
                                    fill="white" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="lucide lucide-bookmark">
                                    <path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z" />
                                </svg>
                            </a>
                        </li>
                        <li>
                            <a href="#"
                                class="bg-[#032541] h-9 w-9 flex rounded-full text-white items-center justify-center ">
                                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24"
                                    fill="white" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="lucide lucide-bookmark">
                                    <path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z" />
                                </svg>
                            </a>
                        </li>



                    </ul>

                    <div class="flex px-4 py-4 flex-col ">
                        <h3 class="text-gray-400 font-mono italic ">Obviously</h3>
                        <h3 class="text-white my-2.5 font-semibold">Overview</h3>
                        <p class="font-light">The Guardians must fight to keep their newfound family together as
                            they unravel
                            the mysteries of Peter Quill's true parentage.</p>

                        <ul class="grid grid-cols-2 md:grid-cols-3 gap-y-5 mt-5">

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">James
                                        Gunn</a>
                                </p>
                                <p class="font-light font-sans text-sm">Director, Writer</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Keith
                                        Giffen</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Val
                                        Mayerik</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Steve
                                        Gerber</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Steve
                                        Gan</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Jim
                                        Starlin</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Bill
                                        Mantlo</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Steve
                                        Englehart</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Larry
                                        Lieber</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Stan
                                        Lee</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>

                            <li class="flex flex-col items-start ">
                                <p>
                                    <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Jack
                                        Kirby</a>
                                </p>
                                <p class="font-light font-sans text-sm">Characters</p>
                            </li>


                        </ul>
                    </div>




                </div>
            </section>
        </div>


        <div class=" md:block hidden p-10 relative w-full  bg-banner-gradient ">
            <div class="flex flex-col md:flex-row items-start ">


                <!-- web  -->
                <div
                    class=" relative hidden md:block rounded-[8px] overflow-hidden min-w-[300px] w-[300px] min-h-[450px] h-[450px]">
                    <img alt="movie poster"
                        src="https://media.themoviedb.org/t/p/w300_and_h450_bestv2/y4MBh0EjBlMuOzv9axM4qJlmhzz.jpg"
                        class="h-full w-full object-contain " />
                </div>



                <section class="w-full text-white  flex h-full">
                    <div class="w-full pl-10  flex-col flex h-full">
                        <!-- title -->
                        <div class="flex flex-col pb-5">
                            <h2 class="text-white space-x-1 text-[2.2rem]">
                                <a class="font-bold " href="/movie/283995-guardians-of-the-galaxy-vol-2">Guardians of
                                    the Galaxy Vol.
                                    2</a>
                                <span class="text-gray-300">(2017)</span>
                            </h2>
                            <div class="flex justify-start text-white gap-x-2 items-center">


                                <span class="border border-gray-300 px-2 text-gray-300">
                                    PG-13
                                </span>

                                <span class="">
                                    05/05/2017 (US)
                                </span>
                                <span class=" flex items-center gap-x-1 ">
                                    <a class="text-white hover:text-gray-400"
                                        href="/genre/878-science-fiction/movie">Science
                                        Fiction</a>,&nbsp;<a class="text-white hover:text-gray-400"
                                        href="/genre/12-adventure/movie">Adventure</a>,&nbsp;<a
                                        class="text-white hover:text-gray-400" href="/genre/28-action/movie">Action</a>
                                </span>

                                <span class="">
                                    2h 17m
                                </span>

                            </div>
                        </div>

                        <!--user score widget  -->
                        <UserScoreWidget :scorePercentage="65" />


                        <!-- actions -->
                        <ul class="flex items-center justify-start gap-x-5 mb-5">

                            <li>
                                <a href="#"
                                    class="bg-[#032541] h-9 w-9 flex rounded-full text-white items-center justify-center ">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24"
                                        fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" class="lucide lucide-list">
                                        <path d="M3 12h.01" />
                                        <path d="M3 18h.01" />
                                        <path d="M3 6h.01" />
                                        <path d="M8 12h13" />
                                        <path d="M8 18h13" />
                                        <path d="M8 6h13" />
                                    </svg>
                                </a>
                            </li>
                            <li>
                                <a href="#"
                                    class="bg-[#032541] h-9 w-9 flex rounded-full text-white items-center justify-center ">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24"
                                        fill="white" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" class="lucide lucide-heart">
                                        <path
                                            d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z" />
                                    </svg>
                                </a>
                            </li>
                            <li>
                                <a href="#"
                                    class="bg-[#032541] h-9 w-9 flex rounded-full text-white items-center justify-center ">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24"
                                        fill="white" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" class="lucide lucide-bookmark">
                                        <path d="m19 21-7-4-7 4V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v16z" />
                                    </svg>
                                </a>
                            </li>

                            <li>


                                <a href="#"
                                    class=" flex gap-x-2 text-white font-semibold hover:text-white/70 flex-nowrap text-nowrap whitespace-nowrap items-center justify-start">

                                    <span><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14"
                                            viewBox="0 0 24 24" fill="white" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-play">
                                            <polygon points="6 3 20 12 6 21 6 3" />
                                        </svg></span>
                                    <span>Play Trailer</span>
                                </a>

                            </li>

                        </ul>

                        <div class="flex flex-col ">
                            <h3 class="text-gray-400 font-mono italic ">Obviously</h3>
                            <h3 class="text-white my-2.5 font-semibold">Overview</h3>
                            <p class="font-light">The Guardians must fight to keep their newfound family together as
                                they unravel
                                the mysteries of Peter Quill's true parentage.</p>

                            <ul class="grid grid-cols-3 gap-y-5 mt-5">

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">James
                                            Gunn</a>
                                    </p>
                                    <p class="font-light">Director, Writer</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Keith
                                            Giffen</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Val
                                            Mayerik</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Steve
                                            Gerber</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Steve
                                            Gan</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Jim
                                            Starlin</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Bill
                                            Mantlo</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Steve
                                            Englehart</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Larry
                                            Lieber</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Stan
                                            Lee</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>

                                <li class="flex flex-col items-start ">
                                    <p>
                                        <a class="hover:text-gray-200 font-bold" href="/person/15218-james-gunn">Jack
                                            Kirby</a>
                                    </p>
                                    <p class="font-light">Characters</p>
                                </li>


                            </ul>
                        </div>




                    </div>
                </section>

            </div>
        </div>
    </div>
</template>