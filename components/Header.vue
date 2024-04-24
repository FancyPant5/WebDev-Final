<template>
    <header class="bg-dodger-blue-500 py-4 ">
        <main class="container mx-auto flex flex-row justify-between">
            <div class="text-white text-xl font-bold text-black-400 transition hover:text-slate-900 light:hover:text-slate-50">
                <nuxt-link to="/">IT Helpdesk</nuxt-link>
            </div>
            
            <nav class="flex flex-row font-semibold justify-end gap-8 text-white ">
                <nuxt-link to="/page1" class="px-2 py-2 text-sm text-black-400 no-underline transition hover:text-slate-900 light:hover:text-slate-50">Your Tickets</nuxt-link>
                <nuxt-link to="/page2" class="px-2 py-2 text-sm text-black-400 no-underline transition hover:text-slate-900 light:hover:text-slate-50">About</nuxt-link>
                <nuxt-link to="/page3" class="px-2 py-2 text-sm text-black-400 no-underline transition hover:text-slate-900 light:hover:text-slate-50">FAQ</nuxt-link>
                <nuxt-link to="/page4" class="px-2 py-2 text-sm text-black-400 no-underline transition hover:text-slate-900 light:hover:text-slate-50">Sign In</nuxt-link>

            </nav>
        </main>

    </header>
</template>