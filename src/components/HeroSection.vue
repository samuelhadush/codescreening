<template>
    <div
        class="  relative w-full bg-[url('https://media.themoviedb.org/t/p/w1920_and_h800_multi_faces/aJn9XeesqsrSLKcHfHP4u5985hn.jpg')]">
        <div class=" p-10 relative w-full  bg-banner-gradient ">
            <div class="flex items-start ">

                <div class=" relative rounded-[8px] overflow-hidden min-w-[300px] w-[300px] min-h-[450px] h-[450px]">
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

                        <!-- score -->
                        <div class="flex items-center gap-x-2 justify-start">
                            <div class="flex items-center text-white justify-start ">

                                <!-- user score progress bar -->
                                <div class="relative w-20 h-20 rounded-full p-1">
                                    <div class="rounded-full bg-[#081c22]">
                                        <svg class="w-full h-full" viewBox="0 0 100 100">
                                            <!-- Background circle -->
                                            <circle class="text-[#204529] stroke-current" stroke-width="6" cx="50"
                                                cy="50" r="40" fill="transparent"></circle>
                                            <!-- Progress circle -->
                                            <circle class="text-[#21d07a]  progress-ring__circle stroke-current"
                                                stroke-width="4" stroke-linecap="round" cx="50" cy="50" r="40"
                                                fill="transparent" stroke-dasharray="251.2"
                                                stroke-dashoffset="calc(251.2 - (251.2 * 70) / 100)"
                                                transform="rotate(-90 50 50)"></circle>

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
                                    <li
                                        class="bg-[#032541] h-8 w-8 flex rounded-full text-white items-center text-3xl justify-center ">
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
                                    <span
                                        class="flex pl-1 underline underline-offset-2 decoration-2 decoration-sky-400">
                                        vibe
                                    </span>
                                    ? <span class=" pl-1 text-[#032541]">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                                            viewBox="0 0 24 24" fill="white" stroke="currentColor" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-info">
                                            <circle cx="12" cy="12" r="10" />
                                            <path d="M12 16v-4" />
                                            <path d="M12 8h.01" />
                                        </svg>
                                    </span>
                                </div>
                            </div>

                        </div>

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