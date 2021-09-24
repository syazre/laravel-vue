<template>
    <div class="hidden fixed top-0 right-0 px-6 py-4 sm:block">
        <router-link :to="{ name: 'home' }" class="text-sm text-gray-700 dark:text-gray-500 underline">Home</router-link>
        <router-link :to="{ name: 'login' }" class="ml-4 text-sm text-gray-700 dark:text-gray-500 underline">Login</router-link>
        <router-link :to="{ name: 'register' }" class="ml-4 text-sm text-gray-700 dark:text-gray-500 underline">Register</router-link>
    </div>
</template>

<script>
export default {
    name: 'navbar'
}
</script>