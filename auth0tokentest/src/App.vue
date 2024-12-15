<template>
  <!--
    This example requires updating your template:

    ```
    <html class="h-full bg-gray-100">
    <body class="h-full">
    ```
  -->
  <div class="min-h-full">
    <Popover as="header" class="bg-indigo-600 pb-24" v-slot="{ open }">
      <div class="mx-auto max-w-3xl px-4 sm:px-6 lg:max-w-7xl lg:px-8">
        <div class="relative flex items-center justify-center py-5 lg:justify-between">
          <!-- Logo -->
          <div class="absolute left-0 shrink-0 lg:static">
            <a href="#">
              <span class="sr-only">Your Company</span>
              <img class="h-8 w-auto" src="https://tailwindui.com/plus/img/logos/mark.svg?color=indigo&shade=300" alt="Your Company" />
            </a>
          </div>
        </div>
      </div>
    </Popover>
    <main class="-mt-24 pb-8">
      <div class="mx-auto max-w-3xl px-4 sm:px-6 lg:max-w-7xl lg:px-8">
        <h1 class="sr-only">Page title</h1>
        <!-- Main 3 column grid -->
        <div class="grid grid-cols-1 items-start gap-4 lg:grid-cols-3 lg:gap-8">
          <!-- Left column -->
          <div class="grid grid-cols-1 gap-4">
            <section aria-labelledby="section-1-title">
              <h2 class="sr-only" id="section-1-title">Section title</h2>
              <div class="overflow-hidden rounded-lg bg-white shadow">
                <div class="p-6">
                  <!-- Your content -->
                </div>
              </div>
            </section>
          </div>

          <!-- Right column -->
          <div class="grid grid-cols-1 gap-4 lg:col-span-2">
            <section aria-labelledby="section-2-title">
              <h2 class="sr-only" id="section-2-title">Section title</h2>
              <div class="overflow-hidden rounded-lg bg-white shadow">
                <div class="p-6">
                  <!-- Your content -->
                </div>
              </div>
            </section>
          </div>
        </div>
      </div>
    </main>
    <footer>
      <div class="mx-auto max-w-3xl px-4 sm:px-6 lg:max-w-7xl lg:px-8">
        <div class="border-t border-gray-200 py-8 text-center text-sm text-gray-500 sm:text-left"><span class="block sm:inline">&copy; 2021 Your Company, Inc.</span> <span class="block sm:inline">All rights reserved.</span></div>
      </div>
    </footer>
  </div>
</template>

<script setup>
import {
  Menu,
  MenuButton,
  MenuItem,
  MenuItems,
  Popover,
  PopoverButton,
  PopoverOverlay,
  PopoverPanel,
  TransitionChild,
  TransitionRoot,
} from '@headlessui/vue'

</script>