<script>
	import stamp from '../../lib/images/stamp.jpg';
</script>

<div>
	<div class="w-fit mx-auto space-y-10">
		<img src={stamp} alt="" class="mx-auto h-[6rem] drop-shadow-md" />
		<p class="text-xl">Reach out below and I'll be in touch soon...</p>
		<form class="flex flex-col gap-2 w-[20rem] mx-auto">
			<input
				type="email"
				placeholder="Email"
				class="rounded-md border p-2 border-gray-700 outline-none"
			/>
			<textarea
				rows="10"
				placeholder="Message"
				class="resize min-w-[20rem] rounded-md border p-2 border-gray-700 outline-none"
			/>
			<button class="rounded-md border p-2 border-gray-700 hover:bg-gray-600 bg-gray-700 text-white"
				>Send</button
			>
		</form>
		<p class="text-xl text-center">jake@hink.dev</p>
	</div>
</div>
