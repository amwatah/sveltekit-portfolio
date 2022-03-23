<script>
import CssLibraries from "$lib/CssLibraries.svelte";
import FrontEndCore from "$lib/FrontEndCore.svelte";
import JavaScriptUi from "$lib/JavaScriptUI.svelte";
import Others from "$lib/Others.svelte";
import Resume from "$lib/Resume.svelte";


</script>
<div class=" tech grid grid-cols-12 gap-1 justify-center pb-[10vh]   ">
     <div class="title col-span-12 mt-[5vh]  "><p class="font-bold text-2xl" >MY SKILLSET</p></div>
     <section class="skillset col-span-12 sm:col-span-6 md:col-span-4 lg:col-span-3 h-full ">
        <FrontEndCore/>
     </section>
     <section class="skillset col-span-12 sm:col-span-6 md:col-span-4 lg:col-span-3 ">
        <CssLibraries/>
     </section>
     <section class="skillset col-span-12 sm:col-span-6 md:col-span-4 lg:col-span-3 ">
         <JavaScriptUi/>
     </section>
     <section class="skillset col-span-12 sm:col-span-6 md:col-span-4 lg:col-span-3 ">
        <Others/>
    </section>
    <section class="skillset col-span-12 justify-self-auto  font-bold text-lg ">
        <h1 class="title">RESUME AND EXPERIENCE </h1>
        <Resume/>
    </section>

      
</div>