<script lang="ts">
	const navItems = [
		{ href: '/', label: 'Home' },
		{ href: '/register', label: 'Register' },
		{ href: '/feed', label: 'Members Feed' },
		{ href: '/profile', label: 'Profile' },
		{ href: '/payments', label: 'Payments' },
		{ href: '/events', label: 'Events' },
		{ href: '/resources', label: 'Resources' },
		{ href: '/admin', label: 'Admin' }
	];
</script>

<header class="bg-white shadow">
	<div class="container mx-auto px-4 py-4 flex items-center justify-between flex-wrap">
		<div class="flex items-center">
			<img src="/AfASlogo.png" alt="AfAS Logo" class="h-10 mr-4" />
		</div>
		<nav class="mt-4 md:mt-0">
			<ul class="flex flex-wrap gap-4">
				{#each navItems as item}
					<li>
						<a href={item.href} class="text-gray-600 hover:text-gray-800 whitespace-nowrap"
							>{item.label}</a
						>
					</li>
				{/each}
			</ul>
		</nav>
	</div>
</header>
