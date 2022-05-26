<template>
  <section id="projects">
    <h1 class="text-center text-3xl mb-10">Projects</h1>
    <div class="flex space-x-3 justify-center">
      <div class="p-5 rounded-lg w-full md:w-1/2 lg:w-1/3 bg-sky-100 shadow-md">
        <div class="flex justify-between">
          <h2 class="text-xl mb-3 text-sky-900 font-medium">
            Myze <span class="text-sm">(wip)</span>
          </h2>
          <div class="flex space-x-5">
            <a class="text-indigo-600" href="https://myze.ca">
              <NewWindowIcon class="h-6" />
            </a>
            <a href="https://github.com/MisterShack/Myze-Client">
              <GitHubIcon class="h-6" />
            </a>
          </div>
        </div>
        <p class="text-lg">
          A personal finance tracking app that allows you to manually manage
          your transactions and consolidate your bank/credit accounts.
        </p>
        <p class="mt-5 text-sm">
          Created using Vue.js, Tailwind CSS and Supabase
        </p>
      </div>
      <div class="p-5 rounded-lg w-full md:w-1/2 lg:w-1/3 bg-sky-100 shadow-md">
        <div class="flex justify-between">
          <h2 class="text-xl mb-3 text-sky-900 font-medium">
            Lotto 6/49 API <span class="text-sm">(wip)</span>
          </h2>
          <div class="flex space-x-5">
            <a href="https://github.com/MisterShack/lottery-649-api">
              <GitHubIcon class="h-6" />
            </a>
          </div>
        </div>
        <p class="text-lg">
          A start to an API where a lotto 6/49 ticket may be checked to validate the winning prize amount. Future development will allow users to add funds to a wallet, buy and validate tickets.
        </p>
        <p class="mt-5 text-sm">
          Created using PHP and the Laravel Framework
        </p>
      </div>

    </div>
  </section>
</template>

<script setup>
  import GitHubIcon from "./icons/GitHubIcon.vue";
  import NewWindowIcon from "./icons/NewWindowIcon.vue";
</script>
