<script lang="ts">
	import "./layout.css";
	import logo from "$lib/assets/AfASlogo.png";

	let { children } = $props();
</script>

<header class="bg-white shadow">
	<div class="container mx-auto px-4 py-4 flex items-center justify-between">
		<div class="flex items-center">
			<img src={logo} alt="AfAS Logo" class="h-12 mr-4" />
		</div>
		<nav>
			<ul class="flex space-x-4">
				<li>
					<a href="/" class="text-gray-600 hover:text-gray-800"
						>Home</a
					>
				</li>
				<li>
					<a
						href="/register"
						class="text-gray-600 hover:text-gray-800">Register</a
					>
				</li>
				<li>
					<a href="/feed" class="text-gray-600 hover:text-gray-800"
						>Members Feed</a
					>
				</li>
				<li>
					<a href="/profile" class="text-gray-600 hover:text-gray-800"
						>Profile</a
					>
				</li>
				<li>
					<a
						href="/payments"
						class="text-gray-600 hover:text-gray-800">Payments</a
					>
				</li>
				<li>
					<a href="/events" class="text-gray-600 hover:text-gray-800"
						>Events</a
					>
				</li>
				<li>
					<a
						href="/resources"
						class="text-gray-600 hover:text-gray-800">Resources</a
					>
				</li>
				<li>
					<a href="/admin" class="text-gray-600 hover:text-gray-800"
						>Admin</a
					>
				</li>
			</ul>
		</nav>
	</div>
</header>

<main class="container mx-auto px-4 py-8">
	{@render children()}
</main>

<footer class="bg-gray-800 text-white py-4">
	<div class="container mx-auto px-4 text-center">
		<p>© 2025 African Astronomical Society. All rights reserved.</p>
	</div>
</footer>
