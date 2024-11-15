<template>
    <section class="flex flex-col mt-5 py-5 border-t border-gray-200 w-full">
        <div class="flex md:flex-row flex-col w-full justify-start items-start">
            <h3 class="font-medium font-sans mr-12 mb-5 text-xl text-black">Media</h3>
            <ul class=" flex gap-x-6   w-full mb-4 md:mb-0 items-center overflow-x-auto justify-start">
                <li class=" border-b-4 border-black">
                    <a id="reviews" class="font-semibold text-black text-sm whitespace-nowrap " href="#">Most Popular
                        <span class="text-gray-500 font-medium">25</span></a>
                </li>
                <li class=" ">
                    <a id="reviews" class="font-semibold text-black text-sm whitespace-nowrap " href="#"> Videos <span
                            class="text-gray-500 font-medium ">8</span></a>
                </li>
                <li class=" ">
                    <a id="reviews" class="font-semibold text-black text-sm whitespace-nowrap " href="#"> Backdrop <span
                            class="text-gray-500 font-medium ">63</span></a>
                </li>
                <li class=" ">
                    <a id="reviews" class="font-semibold text-black text-sm whitespace-nowrap " href="#"> Posters <span
                            class="text-gray-500 font-medium ">323</span></a>
                </li>
            </ul>


        </div>
        <div class="flex rounded-lg max-w-full md:w-[calc(100vw-80px-268px)] md:max-w-[calc(100vw-80px-268px)] overflow-x-auto">

            <!-- media slider items  -->
            <div
            class=" flex  min-h-[141px] h-[141px]   md:min-h-[300px] md:h-[300px] min-w-[250px] w-[250px] md:min-w-[533px] md:w-[533px]">


                <div
                    class=" flex object-cover bg-center bg-[length:100%]  bg-[url(https://i.ytimg.com/vi/2WhQcK-Zaok/hqdefault.jpg)] items-center justify-center min-h-[141px] h-[141px]   md:min-h-[300px] md:h-[300px] min-w-[250px] w-[250px] md:min-w-[533px] md:w-[533px]">

                    <a class="h-full w-full flex text-white items-center justify-center"
                        href="video/play?key=2WhQcK-Zaok">

                        <div class="p-4 rounded-full bg-[#000000b3]">

                            <span><svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24"
                                    fill="white" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="lucide lucide-play">
                                    <polygon points="6 3 20 12 6 21 6 3" />
                                </svg></span>
                        </div>

                    </a>

                </div>
            </div>

            <!-- no link media -->
            <div
            class=" flex  min-h-[141px] h-[141px]   md:min-h-[300px] md:h-[300px] min-w-[250px] w-[250px] md:min-w-[533px] md:w-[533px]">

                <div
                    class=" flex object-cover bg-center bg-[length:100%]  bg-[url(https://media.themoviedb.org/t/p/w533_and_h300_bestv2/aJn9XeesqsrSLKcHfHP4u5985hn.jpg)] items-center justify-center min-h-[141px] h-[141px]   md:min-h-[300px] md:h-[300px] min-w-[250px] w-[250px] md:min-w-[533px] md:w-[533px]">

                    <!-- <a class="h-full w-full flex text-white items-center justify-center" href="video/play?key=2WhQcK-Zaok">
                    <div class="p-4 rounded-full bg-[#000000b3]">
                      
                                          <span><svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24"
                                              fill="white" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                              stroke-linejoin="round" class="lucide lucide-play">
                                              <polygon points="6 3 20 12 6 21 6 3" />
                                            </svg></span>
                    </div>
                  </a> -->

                </div>
            </div>

            <!-- no link media -->
            <div
                class=" flex  min-h-[141px] h-[141px]   md:min-h-[300px] md:h-[300px] min-w-[250px] w-[250px] md:min-w-[533px] md:w-[533px]">
                <div
                    class=" flex object-cover bg-center bg-[length:100%]  bg-[url(https://media.themoviedb.org/t/p/w220_and_h330_face/y4MBh0EjBlMuOzv9axM4qJlmhzz.jpg)] items-center justify-center min-h-[141px] h-[141px]   md:min-h-[300px] md:h-[300px] min-w-[250px] w-[250px] md:min-w-[533px] md:w-[533px]">


                </div>
            </div>



        </div>

    </section>
</template>