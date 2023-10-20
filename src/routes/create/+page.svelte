<header class="grid grid-cols-2 w-full gap-8 text-2xl px-4">
	<div class="p-4 bg-gray-200 border-8 border-t-0 border-gray-300 w-fit">
		<a href="/" class="flex gap-2">
			<img src="/logo.svg" class="h-8" alt="logo" />
			ModBox
		</a>
	</div>
	<div class="flex gap-2 justify-end">
		<div class="bg-gray-200 border-8 border-t-0 border-gray-300 p-4">N</div>
		<div class="bg-gray-200 border-8 border-t-0 border-gray-300 p-4">Account</div>
	</div>
</header>

<div class="bg-gray-200 flex flex-col items-center w-fit m-auto p-8 -mt-20 gap-8 pt-32">
	<span class="text-3xl">Create a Modpack</span>
	<div class="grid grid-cols-2 gap-8">
		{#each [0, 1, 2, 4] as dummyIndex}
			<div class="bg-gray-300 flex flex-col items-center p-4 gap-2 w-64 h-64 justify-between">
				<span class="flex justify-center items-center">Make from ....</span>
				<div class="w-16 h-16 bg-gray-400" />
				<button class="bg-gray-400 p-2 w-full">Select</button>
			</div>
		{/each}
	</div>
</div>
