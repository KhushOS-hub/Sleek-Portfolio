<script setup>
const about = "Projects"
</script>

<template>
    <div class="border border-black rounded-md p-3 w-full h-full flex flex-col justify-center">

        <div class="text-center">

            <!-- Name -->
            <div class="flex-1 text-left min-w-0">
                <h2 class="text-base font-medium md:text-lg sm:text-sm text-orange-600">
                    {{ about }}
                </h2>

                <ul>
                    <li>
                        <a href="">Nodus</a>
                        <p class="text-xs sm:text-sm md:text-xs">Built a file transfer system</p>
                    </li>
                    <li>
                        <a href="">AuthMail</a>
                        <p class="text-xs sm:text-sm md:text-xs">Auth api built with type safety of TS</p>
                    </li>
                    <li>
                        <a href="">Portfolio</a>
                        <p class="text-xs sm:text-sm md:text-xs">The one you're viewing rn</p>
                    </li>
                </ul>
            </div>

        </div>

    </div>
</template>
