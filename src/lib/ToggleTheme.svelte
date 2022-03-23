<script>
	import Icon from '@iconify/svelte';

	import { Toggle } from 'carbon-components-svelte';
	import { getContext } from 'svelte';
	let toggleTheme = getContext('themeContext');
</script>

<div class="toggle-theme fixed top-0 right-[1%]    flex items-center justify-start  ">
	<Toggle
		size="sm"
		on:toggle={() => {
			
			toggleTheme();
		}}
		class="flex-[3]"
	/>
	<Icon icon="emojione:sun-with-face" class="text-lg ml-8 mt-3 " />
</div>
