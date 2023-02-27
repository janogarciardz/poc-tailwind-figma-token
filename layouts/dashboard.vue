<script lang="ts" setup>

const isDark = ref(false)

const toggleDarkMode = () => {
  isDark.value = !isDark.value
  if (isDark.value){
		document.documentElement.setAttribute('data-theme', 'dark')
	}else{
		document.documentElement.setAttribute('data-theme', 'light')
	}
}

const buttonLabel = computed(() => {
  return isDark.value ? 'Light' : 'Dark'
})
</script>
<template>
	<div>
	<div class="text-fg-default bg-bg-default">
    <button
      class="h-10 px-6 font-semibold rounded-md bg-bg-default text-fg-default border-solid border-fg-default border-2"
      @click="toggleDarkMode"
    >
      <Icon v-if="isDark" name="heroicons-outline:sun" />
      <Icon v-else name="heroicons-outline:moon" />
      {{ buttonLabel }}
    </button>
  </div>

		<slot />
	</div>
</template>