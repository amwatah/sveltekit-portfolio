<script>
	import Icon from '@iconify/svelte';
	import { Tile } from 'carbon-components-svelte';

	export let project = 'Project Name';
	export let describtion = ' project describtion';
	export let website;
	export let github;
</script>

<Tile class="col-span-12 sm:col-span-4 md:col-span-3 overflow-x-hidden  transition duration-500 hover:scale-[1.25] ">
	<div
		class="project-card flex flex-col gap-2  items-center border-2 border-[#4589FF]   "
	>
		<section class="title  flex-[1] border-2 ">
			{project}
		</section>
		<section class="image  flex-[5]  ">
			<Icon icon="arcticons:projectm" class="text-7xl bg-primary rounded-md " />
		</section>
		<section class="describtion text-center  flex-[1] ">
			{describtion}
		</section>
		<section class="actions  flex-[1]flex justify-between items-center ">
			<a href={website}><button class="btn btn-square"> <Icon icon="iconoir:internet" /></button></a
			>
			<a href={github}><button class="btn btn-square  "><Icon icon="bytesize:github" /> </button></a
			>
		</section>
	</div>
</Tile>
