
<link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js">
	import {  AppBar, Accordion, AccordionItem, AppShell} from '@skeletonlabs/skeleton';
</script>








		
   <AppBar>
	<svelte:fragment slot="lead" ><div>🕌</div></svelte:fragment>
	<h2 class="h2" style="">
		<span class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone">Masjid</span>
		</h2>
	<svelte:fragment slot="trail"><button type="button" class="btn variant-ghost-primary">Discord</button></svelte:fragment>
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


