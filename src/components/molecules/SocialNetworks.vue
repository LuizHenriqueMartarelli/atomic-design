<template>
	<div class="social-networks">
		<SocialLink name="Github" to="#" icon="github.svg" />
		<SocialLink name="Twitter" to="#" icon="twitter.svg" />
		<SocialLink name="Facebook" to="#" icon="facebook.svg" />
	</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { SocialLink } from '@/components/atoms';

export default defineComponent({
	components: {
		SocialLink,
	},
});
</script>

<style lang="scss" scoped>
.social-networks {
	display: grid;
	grid-gap: 1rem;
}
</style>
