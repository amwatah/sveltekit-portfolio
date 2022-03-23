<script>
    import { Accordion, AccordionItem, ProgressBar } from "carbon-components-svelte";
    
    
    </script>
    
    <div class="frontend">
        <Accordion  >
            <AccordionItem title="CSS LIBRARIES " >
                <div class="skill grid grid-cols-4 items-center gap-1">
                     
                    
                       <ProgressBar labelText="TAILWIND CSS" value={70} class="col-span-4" /> 
                       <ProgressBar labelText="MATERIAL DESIGN" value={50} class="col-span-4" />
                       <ProgressBar labelText="BOOTSTRAP" value={30} class="col-span-4" />  
                     
                </div>
            </AccordionItem>
        </Accordion>
    </div>