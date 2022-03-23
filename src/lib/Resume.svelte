<script>
	import { Tab, TabContent, Tabs } from 'carbon-components-svelte';
</script>

<div class="text-lg">
	<Tabs>
		<Tab label="2019-2022" />
		<Tab label="2020-2020" />

		<svelte:fragment slot="content">
			<TabContent>
				<span>Student at</span>
				<a href="https://www.mmu.ac.ke/" class="underline"> Multimedia University of Kenya </a>
				<br />
				Bachelor of science ( Computer Technology)
			</TabContent>
			<TabContent>
				<ul>
					<li>
						ICT club offical at <a href="https://www.mmu.ac.ke/" class="underline">Multimedia University Of Kenya</a>
					</li>
				</ul>
			</TabContent>
		</svelte:fragment>
	</Tabs>
</div>
