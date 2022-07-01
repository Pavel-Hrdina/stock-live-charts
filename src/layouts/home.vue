<template>
  <main class="px-4 py-10 text-center text-gray-700 dark:text-gray-200">
    <div class="flex justify-center items-center">
      <router-link to="/">
        <div class="m-5" i-carbon-home></div>
      </router-link>
      <router-link to="/charts/line-chart">
        <div class="m-5" i-carbon-chart-column></div>
      </router-link>
    </div>
    <RouterView />
    <div class="mt-5 mx-auto text-center opacity-75 dark:opacity-50 text-sm">
      [Home Layout]
    </div>
  </main>
</template>
