<script setup>
import { CheckCircleIcon } from '@heroicons/vue/24/solid/index.js'
</script>

<template>
    <a href="#" class="text-sm">
        <div v-if="true" class="flex items-center gap-1">
            Day complete!
            <CheckCircleIcon class="h-7 text-green-500" />
        </div>
        <div v-else class="flex items-center gap-1">
            Progress: <span class="font-mono">20 %</span>
            <div class="w-3 h-3 rounded-full bg-red-500"></div>
        </div>
    </a>
</template>
