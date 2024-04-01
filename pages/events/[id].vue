<script setup>
const route = useRoute()
console.log(route.params.id)

const nuxt = useNuxtApp()
console.log("nuxt",nuxt)
</script>

<template>
    <div>
        <h2 class="text-4xl text-blue-600">event id: {{ $route.params.id }}</h2>
    </div>
</template>