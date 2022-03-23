<script>
	import { Accordion, AccordionItem, ProgressBar } from 'carbon-components-svelte';
</script>

<div class="frontend">
	<Accordion>
		<AccordionItem title="MENTIONABLE">
			<div class="skill grid grid-cols-4 items-center gap-1">
				<ProgressBar labelText="FLUTTER" value={24} class="col-span-4" />
				<ProgressBar labelText="FIREBASE" value={50} class="col-span-4" />
				<ProgressBar labelText="GIT AND GITHUB " value={70} class="col-span-4" />
				<ProgressBar labelText="UI & UX DESIGN" value={30} class="col-span-4" />
				<ProgressBar labelText="CTRL + C CTRL + V" value={100} class="col-span-4" />
			</div>
		</AccordionItem>
	</Accordion>
</div>
