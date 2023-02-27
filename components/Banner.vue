<template>
  <div class="flex items-center gap-x-6 bg-indigo-600 py-2.5 px-6 sm:px-3.5 sm:before:flex-1">
    <p class="text-sm leading-6 text-white">
      Build an ADU Now, Pay Later with <strong class="font-semibold">Multitaskr</strong>. Generate monthly income with Multitaskr 100% ADU financing for qualifying homeowners. <a href="#" class="underline underline-offset-1">See If You Qualify&nbsp;<span aria-hidden="true">&rarr;</span></a>	
    </p>
    <div class="flex flex-1 justify-end">
      <button type="button" class="-m-3 p-3 focus-visible:outline-offset-[-4px]">
        <span class="sr-only">Close</span>
        <XMarkIcon class="h-5 w-5 text-white" aria-hidden="true" />
      </button>
    </div>
  </div>
</template>

<script setup>
import { XMarkIcon } from '@heroicons/vue/20/solid'
</script>