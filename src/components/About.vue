<script setup>
const about = "About"
const author = "Hey, I'm Kushagra Gupta, a software developer from India who loves building, creating, and exploring new ideas. I believe in constant growth and making things that matter. And as Almight said to deku Young Man, You too can become a Hero."
</script>

<template>
    <div class="border border-black rounded-md p-3 w-full h-full flex flex-col justify-center">

        <div class="text-center">

            <!-- Name -->
            <div class="flex-1 text-left min-w-0">
                <h2 class="text-base font-medium md:text-lg sm:text-sm text-orange-600">
                    {{ about }}
                </h2>

                <p class="text-xs sm:text-sm md:text-xs lg:text-sm ">
                    {{ author }}
                </p>
            </div>

        </div>

    </div>
</template>
