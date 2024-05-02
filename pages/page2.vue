<template>
    <section
  class="container mx-auto flex flex-col items-center px-12 py-28 sm:flex-row"
>
  <img
    alt="productivity"
    class=" flex bg-center mb-10 h-24 w-full pr-16 pl-16 rounded-lg sm:rounded-br-[80px] sm:rounded-tl-[120px] sm:mb-0 sm:h-80 "
    src="/assets/workingPerson.jpg"
  />
  <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left">
    <h2
      class="mb-4 text-3xl font-bold leading-tight dark:text-black-50 md:text-4xl"
    >
      Trusted and secured 
    </h2>
    <p class="leading-relaxed text-black-700 dark:text-black-400">
      Our campus system relies on 24/7 cyber security that monitors school infrastructure for potential attacks. We also work with ZiplyFiber to make sure you get the fastest internet speeds for your schooling needs.
    </p>
    <a
      class="group relative mx-auto mt-8 inline-block font-semibold text-black-900 underline decoration-dodger-blue-300 decoration-2 underline-offset-8 transition hover:decoration-slate-700 dark:text-black-200 dark:hover:decoration-slate-200 sm:mx-0"
      href="/page4"
    >
      Review security policies
      
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
        class="absolute bottom-0 -right-6 scale-x-0 transition group-hover:scale-x-100"
      >
        <path
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M5 12h14m-4 4l4-4m-4-4l4 4"
        ></path>
      </svg>
    </a>
  </div>
</section>
<section
  class="container mx-auto flex flex-col items-center px-12 py-28 sm:flex-row-reverse"
>
  <img
    alt="Security"
    class="flex bg-center mb-10 h-24 w-full pr-16 pl-16 rounded-lg sm:rounded-br-[80px] sm:rounded-tl-[120px] sm:mb-0 sm:h-80"
    src="/assets/CodingBackground.jpg"
  />
  <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left">
    <h2
      class="mb-4 text-3xl font-bold leading-tight dark:text-black-50 md:text-4xl"
    >
      Multi layer security
    </h2>
    <p class="leading-relaxed text-black-700 dark:text-black-400">
      Our system utilizes multi-factor authentication, making our campus safe from login fraud.
    </p>
    <a
      class="group relative mx-auto mt-8 inline-block font-semibold text-black-900 underline decoration-dodger-blue-300 decoration-2 underline-offset-8 transition hover:decoration-black-700 dark:text-black-200 dark:hover:decoration-slate-200 sm:mx-0"
      href="/page4"
    >
      View authentication methods
      
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
        class="absolute bottom-0 -right-6 scale-x-0 transition group-hover:scale-x-100"
      >
        <path
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M5 12h14m-4 4l4-4m-4-4l4 4"
        ></path>
      </svg>
    </a>
  </div>
</section>
<section
  class="container mx-auto flex flex-col items-center px-12 py-28 sm:flex-row"
>
  <img
    alt="Security"
    class="flex bg-center mb-10 h-24 w-full pr-16 pl-16 rounded-lg sm:rounded-br-[80px] sm:rounded-tl-[120px] sm:mb-0 sm:h-80"
    src="/assets/Class.jpg"
  />
  <div class="mr-4 w-full text-center sm:w-1/2 sm:text-left">
    <h2
      class="mb-4 text-3xl font-bold leading-tight dark:text-black-50 md:text-4xl"
    >
      Meaningful insight
    </h2>
    <p class="leading-relaxed text-black-700 dark:text-black-400">
      Ask our trained experts for advice on a variety of technological situations.
    </p>
    <a class="group relative mx-auto mt-8 inline-block font-semibold text-black-900 underline decoration-dodger-blue-300 decoration-2 underline-offset-8 transition hover:decoration-black-700 dark:text-black-200 dark:hover:decoration-slate-200 sm:mx-0"
      href="/page1"
      >
      Submit a Ticket
    
    </a>
  </div>
</section>

</template>

<script setup>
useHead({
  title: 'About',
  meta: [
    { name: 'description', content: 'My amazing site.' }
  ],
  bodyAttrs: {
    class: 'test'
  },
  script: [ { innerHTML: 'console.log(\'Hello world\')' } ]
})
</script>