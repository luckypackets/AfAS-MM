<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
</script>

<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<h2 class="text-3xl font-bold text-center mb-8">Events Calendar & Registration</h2>
		<div class="space-y-6">
			<Card.Root>
				<Card.Header>
					<Card.Title>Annual AfAS Conference 2026</Card.Title>
					<Card.Description>June 15-18, 2026 | Nairobi, Kenya</Card.Description>
				</Card.Header>
				<Card.Content>
					<p class="mb-4">
						Join us for the premier astronomy conference in Africa. Topics include exoplanets,
						cosmology, and African astronomy initiatives.
					</p>
					<p class="font-semibold mb-4">Fee: R100 (Members), R150 (Non-Members)</p>
					<Button>Register & Pay</Button>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Webinar: Black Holes and Gravitational Waves</Card.Title>
					<Card.Description>January 20, 2026 | Online</Card.Description>
				</Card.Header>
				<Card.Content>
					<p class="mb-4">Learn about the latest discoveries in gravitational wave astronomy.</p>
					<p class="font-semibold mb-4">Fee: Free for Members</p>
					<Button>Register</Button>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Workshop: Telescope Building for Beginners</Card.Title>
					<Card.Description>March 10-12, 2026 | Cape Town, South Africa</Card.Description>
				</Card.Header>
				<Card.Content>
					<p class="mb-4">Hands-on workshop for building and using amateur telescopes.</p>
					<p class="font-semibold mb-4">Fee: R75</p>
					<Button>Register & Pay</Button>
				</Card.Content>
			</Card.Root>
		</div>
	</main>
</div>
