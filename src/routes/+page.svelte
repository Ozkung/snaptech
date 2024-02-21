<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<div class="container h-full mx-auto flex items-center">
	<div class="space-y-5">
		<!-- <h1 class="h1">Let's get cracking bones!</h1>
		<p>Start by exploring:</p>
		<ul>
			<li><code class="code">/src/routes/+layout.svelte</code> - barebones layout</li>
			<li><code class="code">/src/app.postcss</code> - app wide css</li>
			<li>
				<code class="code">/src/routes/+page.svelte</code> - this page, you can replace the contents
			</li>
		</ul> -->
		<form action="https://demo.grm.asia/api/emailtransaction" method="post">
			<div class="flex items-center flex-wrap" style="width: 100%">
				<div class="mt-4 mx-3 mx-auto">
					<img src="Snaptech.png" width="100%"/>
				</div>
				<div style="width: 100%" class="mt-4">
					<div class="flex justify-center items-center">
						<div>
							<input class="input" style="width: 100%" name="email" type="text" placeholder="Email Address" />
						</div>
						<div>
							<button type="submit" class="m-4 btn variant-filled">Send</button>
						</div>
					</div>
				</div>
			</div>
		</form>
	</div>
</div>
