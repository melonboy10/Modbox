<header class="grid grid-cols-3 w-full gap-8 text-2xl px-4 mb-4">
	<div class="p-4 bg-gray-200 border-8 border-t-0 border-gray-300 w-fit">
		<a href="/" class="flex gap-2">
			<img src="/logo.svg" class="h-8" alt="logo" />
			ModBox
		</a>
	</div>
	<div
		class="flex justify-center bg-gray-200 border-8 border-t-0 border-gray-300 p-4 gap-12 p-x-8 w-fit m-auto"
	>
		<a href="/">Browse</a>
		<a href="/create">Create</a>
	</div>
	<div class="flex gap-2 justify-end">
		<div class="bg-gray-200 border-8 border-t-0 border-gray-300 p-4">N</div>
		<div class="bg-gray-200 border-8 border-t-0 border-gray-300 p-4">Account</div>
	</div>
</header>
<div class="flex flex-col items-center text-xl mb-4">
	<!-- Search -->
	<div class="bg-gray-200 border-8 border-gray-300 flex p-2 gap-2">
		<input
			type="text"
			placeholder="Search"
			class="w-full bg-transparent border-4 border-gray-300 p-1 px-2"
		/>
		<select class="bg-transparent border-4 border-gray-300 px-2">
			<option>Sort</option>
		</select>
		<select class="bg-transparent border-4 border-gray-300 px-2">
			<option>Loader</option>
		</select>
		<select class="bg-transparent border-4 border-gray-300 px-2">
			<option>Version</option>
		</select>
	</div>
</div>
<div class="flex flex-col max-w-5xl m-auto mb-4">
	<div class="grid grid-cols-3 gap-4">
		<!-- Card -->
		{#each [1, 2, 3, 4, 5, 6, 7, 8, 9] as dummyIndex}
			<div class={`bg-gray-200 p-4 ${dummyIndex % 4 <= 1 ? 'col-span-1' : 'col-span-2'}`}>
				<div class="flex justify-between">
					<div class="flex gap-2">
						<div class="bg-gray-300 w-8 h-8" />
						<div class="bg-gray-300 w-8 h-8" />
						<div class="bg-gray-300 w-8 h-8" />
					</div>
					<div class="bg-gray-300 w-8 h-8" />
				</div>
				<div class="bg-gray-300 w-full h-64" />
				<div class="bg-gray-300 w-full h-8" />
			</div>
		{/each}
	</div>
</div>
