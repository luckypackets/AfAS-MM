<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
</script>

<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<section class="text-center mb-8">
			<h2 class="text-4xl font-bold text-gray-800 mb-4">Welcome to AfAS Membership</h2>
			<p class="text-lg text-gray-600 mb-6">
				Join the African Astronomical Society to connect with fellow astronomers, share research,
				and advance astronomy in Africa.
			</p>
			<Button href="/register" size="lg" class="text-lg">Become a Member</Button>
		</section>

		<section class="grid md:grid-cols-3 gap-8">
			<Card.Root>
				<Card.Header>
					<Card.Title>Member Profiles</Card.Title>
				</Card.Header>
				<Card.Content>
					<p>Create and customize your profile with personal, academic, and research details.</p>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Members Feed</Card.Title>
				</Card.Header>
				<Card.Content>
					<p>
						Share content, discuss research, and stay updated with the latest in African astronomy.
					</p>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Upload Documents</Card.Title>
				</Card.Header>
				<Card.Content>
					<p>Upload your CV and other documentation to showcase your expertise.</p>
				</Card.Content>
			</Card.Root>
		</section>
	</main>
</div>
