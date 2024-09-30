<script setup>
import NavItem from '../components/NavItem.vue'
import {
    ChartBarIcon,
    ClockIcon,
    ListBulletIcon,
} from '@heroicons/vue/24/outline/index.js'

const navItems = {
    timeline: ClockIcon,
    activities: ListBulletIcon,
    progress: ChartBarIcon,
}
</script>

<template>
    <nav class="sticky bottom-0 z-10 bg-white">
        <ul class="flex justify-around items-center border-t">
            <NavItem
                v-for="(icon, page) in navItems"
                :key="page"
                :href="`#${page}`"
            >
                <component :is="icon" class="h-6 w-6" /> {{ page }}
            </NavItem>
        </ul>
    </nav>
</template>
