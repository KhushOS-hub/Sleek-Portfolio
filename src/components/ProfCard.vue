<script setup>
const name = "Kushagra Gupta"
const description = "Engineer · Musician · Polymath"
const since = "since 2006"
</script>

<template>
    <div class="border border-black rounded-md p-3 w-auto items-center mx-4 sm:w-3/6 mt-8 sm:mt-25 sm:mx-auto sm:ml-25 md:w-2/6 lg:w-2/7 ">

        <!-- Top row: Profile Info -->
        <div class="flex items-center gap-3">

            <!-- Profile Picture -->
            <div class="size-20 shrink-0 rounded-full border border-black overflow-hidden">
                <img src="../assets/images/mee.jpeg" alt="Khush" class="w-full h-full object-cover">
            </div>

            <!-- Name -->
            <div class="flex-1 text-right min-w-0">
                <h2 class="text-base font-medium md:text-lg sm:text-sm">
                    {{ name }}
                </h2>

                <p class="text-xs sm:text-sm md:text-xs lg:text-sm  text-orange-600">
                    {{ since }}
                </p>
            </div>

        </div>

        <!-- Bottom row: Description and Social Links -->
        <div class="mt-6 flex flex-wrap items-center justify-between gap-3">

            <p class="text-sm md:text-[12px]">
                {{ description }}
            </p>

            <div class="flex items-center gap-3">

                <a href="https://github.com/KhushOS-hub" target="_blank" rel="noopener noreferrer" aria-label="GitHub"
                    class="size-8 shrink-0 rounded-full border border-black flex items-center justify-center">
                    <img src="../assets/icons/github.svg" alt="" class="size-4">
                </a>

                <a href="https://linkedin.com/" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn"
                    class="size-8 shrink-0 rounded-full border border-black flex items-center justify-center">
                    <img src="../assets/icons/linkedin.svg" alt="" class="size-6">
                </a>

                <a href="https://spotify.com/" target="_blank" rel="noopener noreferrer" aria-label="Spotify"
                    class="size-8 shrink-0 rounded-full border border-black flex items-center justify-center">
                    <img src="../assets/icons/spotify.svg" alt="" class="size-4">
                </a>

            </div>

        </div>

    </div>
</template>
