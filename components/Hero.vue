<template>
    <section class="container mx-auto px-8 py-36 text-center sm:px-12">
  <h1
    class="mb-12 text-5xl font-extrabold leading-tight dark:text-black-50 sm:text-6xl"
  >
    Welcome to the Helpdesk, how can we help you?
  </h1>
  <p class="mb-12 leading-relaxed text-slate-700 dark:text-black-400">
    For general inquires, you can submit a Helpdesk Ticket describing your issue, 
    and we'll work with you directly to resolve it. 
  </p>
  <div
    class="mx-auto flex w-fit flex-col space-y-4 sm:flex-row sm:space-y-0 sm:space-x-4"
  >

  <nuxt-link to="/page1" class="rounded-md border-0 bg-dodger-blue-500 px-12 py-2 text-base text-white shadow-lg shadow-dodger-blue-300 transition hover:bg-dodger-blue-600 hover:shadow-dodger-blue-400 dark:shadow-dodger-blue-900"
    >Submit a Ticket</nuxt-link>

    <nuxt-link to="/page2" class="rounded-md border-0 bg-dodger-blue-500 px-12 py-2 text-base text-white shadow-lg shadow-dodger-blue-300 transition hover:bg-dodger-blue-600 hover:shadow-dodger-blue-400 dark:shadow-dodger-blue-900"
    >Learn more</nuxt-link>
    
   
  </div>
</section>
<section
  class="container mx-auto flex flex-col items-center px-8 py-36 sm:flex-row-reverse sm:px-12"
>
  <div class="mb-8 w-full sm:mb-0 sm:w-1/2 sm:pl-4 md:pl-16">
    <img
      alt="Hanging out with friends"
      class="rounded-lg sm:rounded-br-[80px] sm:rounded-tl-[120px]"
      src="/assets/Class.jpg"
    />
  </div>
  <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left">
    <h1
      class="mb-6 text-3xl font-bold leading-tight dark:text-black-50 md:text-4xl"
    >
      Stressed about your tech? We got you!
    </h1>
    <p class="mb-2 leading-relaxed text-slate-700 dark:text-black-400">
      We provide teachers &amp; students with IT support 24/7! 
    </p>
    <ul
      class="mb-8 flex flex-col items-center space-y-1 dark:text-black-400 sm:items-start"
    >
      <li class="flex items-end">
        <svg
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
          width="1.2em"
          height="1.2em"
          class="mr-2 text-dodger-blue-300"
        >
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="m5 12l5 5L20 7"
          ></path>
        </svg>
        <span>AI chatbot suggestions.</span>
      </li>
      <li class="flex items-end">
        <svg
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
          width="1.2em"
          height="1.2em"
          class="mr-2 text-dodger-blue-300"
        >
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="m5 12l5 5L20 7"
          ></path>
        </svg>
        <span>Professional expert advice.</span>
      </li>
      <li class="flex items-end">
        <svg
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
          width="1.2em"
          height="1.2em"
          class="mr-2 text-dodger-blue-300"
        >
          <path
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="m5 12l5 5L20 7"
          ></path>
        </svg>
        <span>Device replacements</span>
      </li>
    </ul>
    <div class="flex flex-col space-y-3 md:flex-row md:space-x-2 md:space-y-0">
      <button
        class="rounded-md border-0 bg-dodger-blue-500 px-5 py-2 text-base text-white shadow-lg shadow-dodger-blue-300 transition hover:bg-dodger-blue-600 hover:shadow-dodger-blue-400 dark:shadow-dodger-blue-900"
      >
        Open menu
      </button>
      <button
        class="rounded-md border-0 bg-dodger-blue-500 px-5 py-2 text-base text-white shadow-lg shadow-dodger-blue-300 transition hover:bg-dodger-blue-600 hover:shadow-dodger-blue-400 dark:shadow-dodger-blue-900"
      >
        Explore services
      </button>
    </div>
  </div>
</section>
</template>
