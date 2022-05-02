<script>
	// @ts-nocheck

	import ProjectCard from '$lib/ProjectCard.svelte';
</script>

<div class="page grid grid-cols-12 justify-center gap-1 pt-[5vh] pb-[10vh]  w-screen  overflow-x-hidden   ">
	<header class=" col-span-12  text-3xl">My Projects </header>
   
        <ProjectCard
		project="CRYPTO APP"
		describtion="A  simple app for tracking top cypto coin  .Built with React and Coin Gecko Api"
		website="https://amwatah-crypto-app.netlify.app/"
		github="https://github.com/amwatah/react-crypto-app"
	/>
    <ProjectCard
		project="JOKES APP"
		describtion=" Get the lastes Chuck Norriss  jokes  on this React app using an API from RapidAPI "
		website="https://amwatah-crypto-app.netlify.app/"
		github="https://github.com/amwatah/react-chuck-norris-jokes"
	/>
    <ProjectCard
		project="Football Highlights "
		describtion="Built with React and FootballApi , this app lets you watch football match highlight from Top leagues in the world"
		website="https://amwatah-dimba.netlify.app/"
		github="https://github.com/amwatah/react-football-highlights"
	/>
	 <ProjectCard
		project="Whatsapp Mock "
		describtion=" A whats app mock wireframe built with sveltekit  "
		website="https://amwatah-chat.vercel.app/"
		github="https://github.com/amwatah/whatsnot"
	/>
	 <ProjectCard
		project=" Simple counter app "
		describtion="  A counter PWA app  using next js  "
		website="https://amwatah-counter.vercel.app/"
		github="https://github.com/amwatah/beacon-pwa"
	/>
	

  
	
</div>
