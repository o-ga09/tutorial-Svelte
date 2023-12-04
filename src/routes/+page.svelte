<script>
	let count = 0;

	const plusButton = () => {
		count = count + 1;
	};

	const minusButton = () => {
		count = count - 1;
	};
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="counter">
	<h1 class="text-center">カウンターアプリ</h1>
	<div
		class="
		flex
		items-center
		justify-center
		w-64
		h-96
		text-5xl
		font-bold
		bg-lime-400
		rounded-lg
		m-4
	  "
	>
		{count}
	</div>
	<div class="flex items-center justify-center h-20">
		<button
			class="
		  h-full
		  w-20
		  m-4
		  bg-cyan-400
		  border-cyan-400
		  rounded-lg
		  text-3xl
		"
			on:click={plusButton}
		>
			+
		</button>
		<button
			class="
		  h-full
		  w-20
		  m-4
		  bg-cyan-400
		  border-cyan-400
		  rounded-lg
		  text-3xl
		"
			on:click={minusButton}
		>
			-
		</button>
	</div>
</div>
