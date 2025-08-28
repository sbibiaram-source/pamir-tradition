<script setup lang="ts">

</script>

<template>
  <div id="contact-us" class="overflow-hidden bg-white py-16 px-4 dark:bg-slate-900 sm:px-6 lg:px-8 lg:py-24">
    <div class="relative mx-auto max-w-xl">
      <svg class="absolute left-full translate-x-1/2 transform" width="404" height="404" fill="none"
           viewBox="0 0 404 404" aria-hidden="true">
        <defs>
          <pattern id="85737c0e-0916-41d7-917f-596dc7edfa27" x="0" y="0" width="20" height="20"
                   patternUnits="userSpaceOnUse">
            <rect x="0" y="0" width="4" height="4" class="text-gray-200 dark:text-slate-600"
                  fill="currentColor"></rect>
          </pattern>
        </defs>
        <rect width="404" height="404" fill="url(#85737c0e-0916-41d7-917f-596dc7edfa27)"></rect>
      </svg>
      <svg class="absolute right-full bottom-0 -translate-x-1/2 transform" width="404" height="404" fill="none"
           viewBox="0 0 404 404" aria-hidden="true">
        <defs>
          <pattern id="85737c0e-0916-41d7-917f-596dc7edfa27" x="0" y="0" width="20" height="20"
                   patternUnits="userSpaceOnUse">
            <rect x="0" y="0" width="4" height="4" class="text-gray-200 dark:text-slate-800"
                  fill="currentColor"></rect>
          </pattern>
        </defs>
        <rect width="404" height="404" fill="url(#85737c0e-0916-41d7-917f-596dc7edfa27)"></rect>
      </svg>
      <div class="text-center">
        <h2 class="text-3xl font-extrabold tracking-tight text-red-500 dark:text-slate-200 sm:text-4xl">Contact Us
        </h2>
        <p class="mt-4 text-lg leading-6 text-gray-500 dark:text-slate-400">Please use the form below to contact us.
          Thank you!
        </p>
      </div>
      <div class="mt-12">
        <form class="grid grid-cols-1 gap-y-6 sm:grid-cols-2 sm:gap-x-8">
          <div class="sm:col-span-2">
            <label for="name" class="block text-sm font-medium text-red-500 dark:text-slate-400">Name</label>
            <div class="mt-1"><input placeholder="Name" name="name" type="text" id="name" autocomplete="organization" required="" class="border-gray-300 block w-full rounded-md py-3 px-4 shadow-sm focus:border-sky-500 focus:ring-sky-500 dark:border-white/5 dark:bg-slate-700/50 dark:text-white">
            </div>
          </div>
          <div class="sm:col-span-2">
            <label for="email" class="block text-sm font-medium text-red-500 dark:text-slate-400">Email</label>
            <div class="mt-1"><input placeholder="Email" name="email" id="email" required="" type="email" autocomplete="email" class="border-gray-300 block w-full rounded-md py-3 px-4 shadow-sm focus:border-sky-500 focus:ring-sky-500 dark:border-white/5 dark:bg-slate-700/50 dark:text-white">
            </div>
          </div>
          <div class="sm:col-span-2">
            <label for="message" class="block text-sm font-medium text-red-500 dark:text-slate-400">Message</label>
            <div class="mt-1"><input placeholder="Message">
              <textarea required="" name="message" id="message" rows="4" class="border-gray-300 block w-full rounded-md py-3 px-4 shadow-sm focus:border-sky-500 focus:ring-sky-500 dark:border-white/5 dark:bg-slate-700/50 dark:text-white"></textarea>
            </div>
          </div>
          <div class="flex justify-end sm:col-span-2">
            <button type="submit" class="inline-flex items-center rounded-md px-4 py-2 font-medium focus:outline-none focus-visible:ring focus-visible:ring-red-500 shadow-sm sm:text-sm transition-colors duration-75 text-black border border-red-500 hover:bg-red-500 active:red-500 disabled:bg-red-500 dark:hover:bg-red-500 dark:active:bg-red-500 dark:disabled:bg-red-500 disabled:cursor-not-allowed">
              <span>Send Message</span>
            </button>

          </div>
        </form>
        <a href="https://veilmail.io/e/FkKh7o" class="font-medium text-red-500 dark:text-red-500 hover:underline">Or click here to reveal our protected email address</a>

      </div>
    </div>
  </div>
</template>

<style scoped>

</style>