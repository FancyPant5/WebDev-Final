<template>
    <header class="bg-dodger-blue-500 py-4">
        <main class="container mx-auto flex flex-row justify-between">
            <div class="text-white text-xl font-bold">
                <nuxt-link to="/">IT Helpdesk</nuxt-link>
            </div>
            <nav class="flex flex-row font-semibold justify-end gap-8 text-white hover:black-700">
                <nuxt-link to="/page1">Your Tickets</nuxt-link>
                <nuxt-link to="/page2">About</nuxt-link>
                <nuxt-link to="/page3">Contact</nuxt-link>
                <nuxt-link to="/page4">Sign In</nuxt-link>

            </nav>
        </main>

    </header>
</template>