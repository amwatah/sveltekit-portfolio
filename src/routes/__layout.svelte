<script>
	import '../app.css';
	import BottomNavigation from '$lib/BottomNavigation.svelte';
	import ToggleTheme from '$lib/ToggleTheme.svelte';
import { setContext } from 'svelte';

	let lightModeActive = false;
	const carbonLightTheme = 'https://unpkg.com/carbon-components-svelte/css/g10.css';
	const carbonDarkTheme = 'https://unpkg.com/carbon-components-svelte/css/g90.css';
  function changeTheme(){
     if(lightModeActive) {
        lightModeActive =false
     }else{
        lightModeActive=true
     }
  }
   setContext("themeContext" , changeTheme )
   setContext("lightThemeOn" , lightModeActive )
</script>

<svelte:head>
	<link rel="stylesheet" href={lightModeActive ? carbonLightTheme : carbonDarkTheme} />
</svelte:head>
<div class="site  font-mono min-h-screen w-screen overflow-x-hidden">
	<ToggleTheme />
	<slot />
	<BottomNavigation />
</div>
