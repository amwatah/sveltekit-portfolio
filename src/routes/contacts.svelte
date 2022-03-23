<script>
import Icon from "@iconify/svelte";
import { Tile } from "carbon-components-svelte";



</script>
<div class="page grid grid-cols-12  pt-[5vh] ">
    <Tile class="github col-span-12 flex items-center rounded-md m-2  ">
        <Icon icon="ant-design:github-filled" class=" flex-[1]" />
        <p class="flex-[2]">Github</p>
        <a href="https://github.com/amwatah"  class="flex-[2] underline " >amwatah</a>
    </Tile>
    <Tile class="github col-span-12 flex items-center rounded-md m-2  ">
        <Icon  icon="akar-icons:instagram-fill" class=" flex-[1]" />
        <p class="flex-[2]">instagram</p>
        <a href="https://www.instagram.com/im_amwatah/"  class="flex-[2] underline " >@Im_amwatah</a>
    </Tile>
    <Tile class="github col-span-12 flex items-center rounded-md m-2  ">
        <Icon icon="akar-icons:twitter-fill" class=" flex-[1]" />
        <p class="flex-[2]">Twitter</p>
        <a href="https://twitter.com/Im_amwatah"  class="flex-[2] underline " >@Im_amwatah</a>
    </Tile>
     <Tile class="github col-span-12 flex items-center rounded-md m-2  ">
        <Icon  icon="carbon:email"  class=" flex-[1]" />
        <p  id="email" class="flex-[2]">email</p>
        
        <p   class="flex-[2] underline " >obuyaamwatah@gmail.com</p>
    </Tile>
    <Tile class="github col-span-12 flex items-center rounded-md m-2  ">
        <Icon   icon="akar-icons:whatsapp-fill" class=" flex-[1]" />
        <p  id="email" class="flex-[2]">whatsapp</p>
        <p   class="flex-[2] underline " >+254793859659</p>
    </Tile>
</div>