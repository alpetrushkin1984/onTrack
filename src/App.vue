<script setup>
import { ref } from 'vue'
import TheHeader from '@/components/TheHeader.vue'
import TheNav from '@/components/TheNav.vue'
import TheActivities from '@/pages/TheActivities.vue'
import TheTimeline from '@/pages/TheTimeline.vue'
import TheProgress from '@/pages/TheProgress.vue'
import { PAGE_ACTIVITIES, PAGE_PROGRESS, PAGE_TIMELINE } from '@/constants.js'

function normalizePageHash() {
    const hash = window.location.hash.slice(1)

    if (
        Object.keys(
            [PAGE_ACTIVITIES],
            [PAGE_PROGRESS],
            [PAGE_TIMELINE]
        ).includes(hash)
    ) {
        return hash
    }
    window.location.hash = PAGE_TIMELINE
    return PAGE_TIMELINE
}

const currentPage = ref(normalizePageHash())
</script>

<template>
    <TheHeader />

    <main class="flex-grow">
        <TheTimeline v-show="currentPage === PAGE_TIMELINE" />
        <TheActivities v-show="currentPage === PAGE_ACTIVITIES" />
        <TheProgress v-show="currentPage === PAGE_PROGRESS" />
    </main>

    <TheNav :currentPage="currentPage" @navigate="currentPage = $event" />
</template>
