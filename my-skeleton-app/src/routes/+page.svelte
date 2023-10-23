
<link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js">
	import {  AppBar, Accordion, AccordionItem, AppShell} from '@skeletonlabs/skeleton';
</script>








		
   <AppBar>
	<svelte:fragment slot="lead" ><h1 class="h2" style="position:relative; top:-3px;">🕌</h1></svelte:fragment>
	<h2 class="h2" style="">
		<span class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone" style="position:relative; left:-15px;">Masjid</span>
		</h2>
	<svelte:fragment slot="trail"><a href="https://discord.gg/masjid" type="button" class="btn variant-soft-primary">Discord</a></svelte:fragment>
   </AppBar>


	<slot />
	<!-- ---- / ---- -->
	<div class="card p-4" style=" position:relative; left:25%; top:100px; width:50%;">
		
<Accordion>
	<AccordionItem open>
		<svelte:fragment slot="lead">📘</svelte:fragment>
		<svelte:fragment slot="summary">Quran</svelte:fragment>
		<svelte:fragment slot="content">This section would have Quran and Tafsier</svelte:fragment>
	</AccordionItem>
	<AccordionItem>
		<svelte:fragment slot="lead">📕</svelte:fragment>
		<svelte:fragment slot="summary">Hadith</svelte:fragment>
		<svelte:fragment slot="content">This section would have Hadith Books</svelte:fragment>
	</AccordionItem>
	<!-- ... -->
</Accordion>

		
		
	</div>


