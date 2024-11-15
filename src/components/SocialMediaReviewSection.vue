<template>
    <section class="flex flex-col mt-5 py-5 border-t border-gray-200 w-full">
        <div class="flex justify-start items-start">
            <h3 class="font-medium font-sans mr-12 mb-5 text-xl">Social</h3>
            <ul class=" flex gap-x-6 items-center justify-start">
                <li class=" border-b-4 border-black">
                    <a id="reviews" class="font-semibold text-black " href="#">Reviews <span
                            class="text-gray-500 font-medium">25</span></a>
                </li>
                <li class=" ">
                    <a id="reviews" class="font-semibold text-black " href="#"> Discussions <span
                            class="text-gray-500 font-medium ">67</span></a>
                </li>
            </ul>

        </div>
        <div class="flex flex-col border border-gray-200 p-5  w-full rounded-md">
            <div class="flex w-full justify-start items-center">
                <div class="w-12 mr-4">
                    <a href="/u/RonaldWalker">
                        <img loading="lazy" class=" rounded-full min-h-[45px] h-[45px] min-w-[45px] w-[45px]"
                            src="https://media.themoviedb.org/t/p/w45_and_h45_face/hxWNGF4QcduLDIMdeCft2CzzrBV.jpg"
                            alt="RonaldWalker">
                    </a>
                </div>

                <div class="flex flex-col justify-start">
                    <h3 class="text-lg font-sans font-bold ">A review by RonaldWalker</h3>
                    <p class="flex items-center whitespace-nowrap text-gray-500 font-light flex-nowrap ">
                        Written by <a class="text-gray-800 mx-1 hover:text-gray-700"
                            href="/u/RonaldWalker">RonaldWalker</a>
                        on
                        January 19, 2020
                    </p>

                </div>

            </div>

            <div class="flex flex-col font-light font-sans gap-y-4 mt-5 justify-start">
                <p class=" leading-tight ">Another enjoyable entry, 'Guardians of the Galaxy Vol. 2' is very good fun.
                </p>
                <p class=" leading-tight ">I actually didn't find the story in this as interesting as in the first film,
                    but the humour - which is still up to the mark in 'Guardians of the Galaxy' - is much greater here;
                    it
                    got more laughs from me, that's for sure. The ending to this is also entertaining.</p>
            </div>


        </div>
        <p class="font-semibold mt-5">Read All Reviews</p>

    </section>

</template>