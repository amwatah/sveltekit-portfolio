<script>
import Icon from "@iconify/svelte";


</script>

<div data-theme="light" class="page text-base grid grid-cols-12 w-screen overflow-x-hidden pt-[10vh] ">
	<h1 class="name-text col-span-12 justify-self-center text-6xl ">Amwatah</h1>
	<h1 class="name-text col-span-12 justify-self-center text-sm ">A web developer</h1>
	<figure class="animation col-span-10 col-start-2 h-[60vh] ">
		<script
			src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
		<lottie-player
			src="https://assets1.lottiefiles.com/packages/lf20_s2vaal7n.json"
			background="transparent"
			speed="1"
			loop
			autoplay
		/>
	</figure>
	<section class="github col-span-12 justify-self-center text-4xl" data-theme="dark" >
            <a href="https://github.com/amwatah">
            <Icon icon="fa:github-square" class="glass mt-3 hover:text-fuchsia-500"  />
      </a>
      </section>

</div>
