<template>
	<div class="p-10">
		<h1>hello</h1>
		<h1 class="text-yellow-400 text-lg">world</h1>
		<div class="flex gap-2">
			<Button label="Primary" />
			<Button label="Success" severity="success" />
			<Button icon="pi pi-home" aria-label="Save" />

			<Button label="Danger" severity="danger" />
			<Button type="button" label="Search" icon="pi pi-search" />
		</div>
	</div>
	
	<NuxtPage/>
</template>
