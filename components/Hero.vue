<template>
    <section class="container mx-auto px-8 py-36 text-center sm:px-12">
  <h1
    class="mb-12 text-5xl font-extrabold leading-tight dark:text-black-50 sm:text-6xl"
  >
    Welcome to the Helpdesk, how can we help you?
  </h1>
  <p class="mb-12 leading-relaxed text-slate-700 dark:text-slate-400">
    For general inquires, you can submit a Helpdesk Ticket describing your issue, 
    and we'll work with you directly to resolve it. 
  </p>
  <div
    class="mx-auto flex w-fit flex-col space-y-4 sm:flex-row sm:space-y-0 sm:space-x-4"
  >

  <nuxt-link to="/page1" class="rounded-md border-0 bg-dodger-blue-500 px-12 py-2 text-base text-white shadow-lg shadow-dodger-blue-300 transition hover:bg-dodger-blue-600 hover:shadow-dodger-blue-400 dark:shadow-dodger-blue-900"
    >IT Helpdesk</nuxt-link>

    <nuxt-link to="/page1" class="rounded-md border-0 bg-dodger-blue-500 px-12 py-2 text-base text-white shadow-lg shadow-dodger-blue-300 transition hover:bg-dodger-blue-600 hover:shadow-dodger-blue-400 dark:shadow-dodger-blue-900"
    >View my Tickets</nuxt-link>
    
   
  </div>
</section>
<section class="container mx-auto px-8 py-28 sm:px-12">
  <h1
    class="sm:mb-18 mb-24 w-full text-center text-4xl font-bold light:text-dodger-blue-100 sm:mx-auto sm:w-4/5"
  >
    Common Issues
  </h1>
  <div class="grid grid-cols-2 gap-4 md:grid-cols-3">
    <div
      class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
    >
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
        class="h-8 w-8"
      >
        <g
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
        >
          <path
            d="M12 18h.01m-2.838-2.828a4 4 0 0 1 5.656 0m-8.485-2.829a8 8 0 0 1 11.314 0"
          ></path>
          <path d="M3.515 9.515c4.686-4.687 12.284-4.687 17 0"></path>
        </g>
      </svg>
      <div class="mt-3 text-sm font-semibold">Connectivity</div>
    </div>
    <div
      class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
    >
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
        class="h-8 w-8"
      >
        <g
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
        >
        <path
            d="M20 6v12a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2zM10 16h6"
          ></path>
          <path
            d="M11 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4 8h3m-3 4h3m-3 4h3"
          ></path>
        </g>
      </svg>
      <div class="mt-3 text-sm font-semibold">Login</div>
    </div>
    <div
      class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
    >
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
        class="h-8 w-8"
      >
        <g
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
        >
          <path
            d="M12 18h.01m-2.838-2.828a4 4 0 0 1 5.656 0m-8.485-2.829a8 8 0 0 1 11.314 0"
          ></path>
          <path d="M3.515 9.515c4.686-4.687 12.284-4.687 17 0"></path>
        </g>
      </svg>
      <div class="mt-3 text-sm font-semibold">High speed internet</div>
    </div>
    <div
      class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
    >
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
        class="h-8 w-8"
      >
        <path
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M3 14a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1zm5-1v4m8-12v.5a2 2 0 0 0 2 2a2 2 0 0 1 2 2v.5"
        ></path>
      </svg>
      <div class="mt-3 text-sm font-semibold">Smoking area</div>
    </div>
    <div
      class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
    >
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
        class="h-8 w-8"
      >
        <g
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
        >
          <path
            d="M20 6v12a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2zM10 16h6"
          ></path>
          <path
            d="M11 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4 8h3m-3 4h3m-3 4h3"
          ></path>
        </g>
      </svg>
      <div class="mt-3 text-sm font-semibold">Meeting room</div>
    </div>
    <div
      class="flex cursor-pointer flex-col items-center justify-start rounded-lg bg-slate-50 py-5 px-6 text-center text-slate-800 shadow-slate-200 transition hover:bg-white hover:shadow-lg hover:shadow-slate-200 dark:bg-slate-800 dark:text-slate-200 dark:shadow-slate-700 dark:hover:shadow-slate-800"
    >
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
        class="h-8 w-8"
      >
        <g
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
        >
          <path
            d="M4 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2z"
          ></path>
          <path d="M9 16V8h4a2 2 0 0 1 0 4H9"></path>
        </g>
      </svg>
      <div class="mt-3 text-sm font-semibold">Huge parking lot</div>
    </div>
  </div>
</section>
</template>
