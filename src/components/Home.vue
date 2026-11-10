<script setup>
import ProfCard from './ProfCard.vue'
import About from './About.vue'
import Projects from './Projects.vue'
</script>

<template>
    <main class="mx-4 mt-8 md:mx-10 lg:mx-20">

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <ProfCard />
            <About />
            <Projects/>
        </div>
    </main>
</template>