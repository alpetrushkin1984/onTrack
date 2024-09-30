<script setup>
import TheLogo from '@/components/TheLogo.vue'
import TheHeaderProgress from '@/components/TheHeaderProgress.vue'
</script>

<template>
    <header
        class="sticky top-0 z-20 bg-white border-b p-3 flex justify-between items-center"
    >
        <TheLogo />

        <TheHeaderProgress />
    </header>
</template>
