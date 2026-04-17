<script lang="ts">
</script>

<main class="mx-auto flex h-screen max-w-3xl flex-col p-4">
	<header class="flex items-center justify-between pb-4">
		<h1 class="text-xl font-bold">Mercator</h1>
	</header>

	<form class="flex gap-2 pt-4">
		<input
			type="text"
			placeholder="How can I glaze you today?"
			class="flex-1 rounded-lg border border-gray-200 px-4 py-2 shadow-2xl"
		/>
		<button type="submit" class="rounded-lg bg-black px-6 py-2 text-white disabled:opacity-50">
			Send it
		</button>
	</form>
</main>
