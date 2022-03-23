<script>
import { Accordion, AccordionItem, ProgressBar } from "carbon-components-svelte";


</script>

<div class="frontend">
    <Accordion  >
        <AccordionItem title="FRONTEND CORE" >
            <div class="skill grid grid-cols-4 items-center gap-1">
                 
                
                   <ProgressBar labelText="HTML" value={70} class="col-span-4" /> 
                   <ProgressBar labelText="CSS" value={40} class="col-span-4" />
                   <ProgressBar labelText="JAVASCRIPT" value={75} class="col-span-4" />  
                 
            </div>
        </AccordionItem>
    </Accordion>
</div>