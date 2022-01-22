<template>
  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="relative bg-white">
    <div class="absolute inset-0 z-30 pointer-events-none" aria-hidden="true" />
    <div class="relative z-20">
      <div class="max-w-7xl mx-auto flex justify-between items-center px-4 py-5 sm:px-6 sm:py-4 lg:px-8 md:justify-start md:space-x-10">
        <div>
          <a href="#" class="flex">
            <span class="sr-only">Workflow</span>
            <img class="h-8 w-auto sm:h-10" src="../static/logoFull.png" alt="">
          </a>
        </div>
        <div class="hidden md:flex-1 md:flex md:items-center md:justify-between">
          <nav class="flex space-x-10" />
          <div class="flex items-center md:ml-12">
            <a href="#" class="text-base font-medium">
              Sign in
            </a>
            <a
              href="#"
              class="ml-8 inline-flex items-center justify-center px-6 py-1 border border-transparent rounded-full text-base font-medium text-white bg-gray-600 hover:bg-grey-700"
            >
              Sign Up
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
