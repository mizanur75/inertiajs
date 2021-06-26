<template>
  <app-layout>
    <header class="bg-white shadow">
      <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
        <h1 class="text-3xl font-bold text-gray-900">About</h1>
      </div>
    </header>
    <main>
      <div class="max-w-7xl mx-auto py-6 sm:-6 lg:px-8">
        <div class="px-4 py-6 sm:px-0">
          <div
            class="border-4 border-dashed border-gray-200 round-lg h-96"
          ></div>
        </div>
      </div>
    </main>
  </app-layout>
</template>

<script>
import AppLayout from "../Layouts/App";
export default {
  components: {
    AppLayout,
  },
};
</script>
