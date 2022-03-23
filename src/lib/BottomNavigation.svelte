<script>
	import Icon from '@iconify/svelte';
</script>

<div
	class="btm-nav  fixed bottom-0 left-0 right-0 w-full  border-2 border-white  h-[10vh] flex justify-center items-center   "
>
	<!-- 
        <Icon icon="fluent:window-dev-tools-16-filled" />
        <Icon icon="fluent:window-dev-tools-16-filled" /> -->

	<a  href="/"  class="btn  btn-square flex flex-col justify-center  items-center  ">
		<Icon icon="bx:home" />
		<p class="text-2xs">Home</p>
	</a >
    <a href="/tech"  class="btn  btn-square flex flex-col justify-center  items-center  ">
		<Icon icon="fluent:window-dev-tools-16-filled" />
		<p class="text-2xs">Tech</p>
	</a >
    <a href="/projects"  class="btn  btn-square flex flex-col justify-center  items-center  ">
		<Icon icon="carbon:application-mobile" />
		<p class="text-2xs">Apps</p>
	</a >
    <a href="/contacts"  class="btn  btn-square flex flex-col justify-center  items-center  ">
		<Icon icon="ic:sharp-contacts" />
		<p class="text-2xs">Contact</p>
	</a >
</div>
