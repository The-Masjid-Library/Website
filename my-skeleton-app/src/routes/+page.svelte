<head>
<link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js">
</script>
</head>

<py-script>pyscript.write('test1',"Masjed Library")</py-script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5">
		<!-- svelte-ignore a11y-missing-content -->
		<h1 class="h1" id="test1"></h1>
		<p>Start by exploring:</p>
		<ul>
			<li><code class="code">/src/routes/+layout.svelte</code> - barebones layout</li>
			<li><code class="code">/src/app.postcss</code> - app wide css</li>
			<li>
				<code class="code">/src/routes/+page.svelte</code> - this page, you can replace the contents
			</li>
		</ul>
	</div>
</div>
