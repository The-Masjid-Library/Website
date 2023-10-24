
<link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js">
	import {  AppBar, Accordion, AccordionItem, AppShell, TreeViewItem, TreeView, LightSwitch} from '@skeletonlabs/skeleton';
</script>








		
   <AppBar>
	<svelte:fragment slot="lead" ><h1 class="h2" style="position:relative; top:1px;"><img style="width: 50px; height: 50px;" src="https://raw.githubusercontent.com/The-Masjid-Library/Library/main/logo%20masjed.png?token=GHSAT0AAAAAACH4ALSLFXWP2G3IUOVM5GXUZJXSNVQ"></h1></svelte:fragment>
	<h2 class="h2" style="">
		<span class="bg-gradient-to-r from-slate-800 to-gray-500 bg-clip-text text-transparent" style="position:relative; left:-15px;">Masjid</span>
		</h2>
	<svelte:fragment slot="trail"><LightSwitch /><a href="https://discord.gg/masjid" type="button" class="btn variant-soft-primary"><b>Discord</b></a></svelte:fragment>
   </AppBar>


	<slot />
	<!-- ---- / ---- -->
	<div class="card p-4" style=" position:relative; left:25%; top:100px; width:50%;">
		
       <h1 class="h1" style="position:relative; top:-10px; left:31%;">📚Library</h1>

	<TreeView>
		<TreeViewItem>
			<span>Books</span>
			<svelte:fragment slot="children">
				<TreeViewItem>
					Mushaf
					<svelte:fragment slot="children">
					<a class="anchor" href="https://quran.com">Quran</a>
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