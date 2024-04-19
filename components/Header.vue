<template>
    <header class="bg-dodger-blue-500 py-2">
        <main class="container mx-auto flex flex-row justify-between">
            <div class="text-white text-lg font-bold">
                <nuxt-link to="/">IT Helpdesk</nuxt-link>
            </div>
            <nav class="flex flex-row justify-end gap-4">
                <nuxt-link to="/page1">About us</nuxt-link>
                <nuxt-link to="/page2">Contact</nuxt-link>
                <nuxt-link to="/page3">Page 3</nuxt-link>
                <nuxt-link to="/page4">Page 4</nuxt-link>

            </nav>
        </main>

    </header>
</template>