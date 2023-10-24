
<link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js">
	import {  AppBar, Accordion, AccordionItem, AppShell, TreeViewItem, TreeView} from '@skeletonlabs/skeleton';
</script>








		
   <AppBar>
	<svelte:fragment slot="lead" ><h1 class="h2" style="position:relative; top:-3px;">🕌</h1></svelte:fragment>
	<h2 class="h2" style="">
		<span class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone" style="position:relative; left:-15px;">Masjid Library</span>
		</h2>
	<svelte:fragment slot="trail"><a href="https://discord.gg/masjid" type="button" class="btn variant-soft-primary">Discord</a></svelte:fragment>
   </AppBar>


	<slot />
	<!-- ---- / ---- -->
	<div class="card p-4" style=" position:relative; left:25%; top:100px; width:50%;">
		


	<TreeView>
		<TreeViewItem>
			<span>Books</span>
			<svelte:fragment slot="children">
				<TreeViewItem>
					Mushaf
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Hadith
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Aqeedah
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Fiqh
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Tafsir
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Seerah
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Health
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Other
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
			</svelte:fragment>
		</TreeViewItem>

		<TreeViewItem>
			Lessons
			<svelte:fragment slot="children">
				<TreeViewItem>
					Mushaf
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Hadith
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Aqeedah
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Fiqh
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Tafsir
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Seerah
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Other
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
			</svelte:fragment>
		</TreeViewItem>

		<TreeViewItem>
			Lectures
			<svelte:fragment slot="children">
				<TreeViewItem>
					Arabic
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					English
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
				<TreeViewItem>
					Other Languages
					<svelte:fragment slot="children">
					 test
					</svelte:fragment>
				</TreeViewItem>
			</svelte:fragment>
		</TreeViewItem>

		<TreeViewItem>
			Refutations
			<svelte:fragment slot="children">
				
			</svelte:fragment>
		</TreeViewItem>

		<TreeViewItem>
			Answers
			<svelte:fragment slot="children">
				
			</svelte:fragment>
		</TreeViewItem>

		<TreeViewItem>
			Responses
			<svelte:fragment slot="children">
				
			</svelte:fragment>
		</TreeViewItem>
		
	</TreeView>
					
	</div>