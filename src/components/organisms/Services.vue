<template>
	<div class="services">
		<Service
			title="Front End"
			description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates mollitia facere debitis cupiditate fuga cum sit, corporis distinctio deleniti unde quibusdam perspiciatis excepturi asperiores culpa ea optio aliquid iusto molestias!"
		/>
		<Service
			title="Back End"
			description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates mollitia facere debitis cupiditate fuga cum sit, corporis distinctio deleniti unde quibusdam perspiciatis excepturi asperiores culpa ea optio aliquid iusto molestias!"
		/>
		<Service
			title="Manutenção"
			description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates mollitia facere debitis cupiditate fuga cum sit, corporis distinctio deleniti unde quibusdam perspiciatis excepturi asperiores culpa ea optio aliquid iusto molestias!"
		/>
	</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { Service } from '@/components/molecules';
export default defineComponent({ components: { Service } });
</script>

<style lang="scss" scoped>
.services {
	display: grid;
	grid-template-columns: repeat(3, 1fr);
	grid-gap: 5rem;
}
</style>
