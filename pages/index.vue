<script lang="ts" setup>
definePageMeta({
	layout: "dashboard"
});

</script>
<template>
	<div>
    <div class="flex justify-center items-center h-screen bg-bg-default">
      <div class="grid gap-4 grid-cols-2 grid-rows-2">
        <button
          class="h-10 px-6 font-semibold rounded-md bg-bg-default text-fg-default border-solid border-fg-default border-2"
        >
          Primary
        </button>

        <button
          class="h-10 px-6 font-semibold rounded-md bg-bg-muted text-fg-muted border-solid border-fg-muted border-2"
        >
          Secondary
        </button>
      </div>
    </div>
  </div>
</template>