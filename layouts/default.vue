<script>
import Banner from '@/components/Banner.vue'

export default {
  components: {
    Banner
  }
}
</script>
<template> 
	<div>
		<Banner />
		<slot />
	</div>
</template>