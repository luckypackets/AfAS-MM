<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
</script>

<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<h2 class="text-3xl font-bold text-center mb-8">Members Feed</h2>
		<div class="max-w-2xl mx-auto space-y-6">
			<Card.Root>
				<Card.Content class="pt-6">
					<div class="flex items-center mb-4">
						<img
							src="https://images.unsplash.com/photo-1446776653964-20c1d3a81b06?w=400&h=200&fit=crop"
							alt="User Avatar"
							class="w-10 h-10 rounded-full mr-4"
						/>
						<div>
							<h3 class="font-semibold">Jane Smith</h3>
							<p class="text-sm text-gray-500">2 hours ago</p>
						</div>
					</div>
					<p class="mb-4">
						Excited to share my latest research on black holes in the Milky Way! Check out the paper
						attached.
					</p>
					<Button variant="link" class="p-0 h-auto">View Paper</Button>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Content class="pt-6">
					<div class="flex items-center mb-4">
						<img
							src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=50&h=50&fit=crop"
							alt="User Avatar"
							class="w-10 h-10 rounded-full mr-4"
						/>
						<div>
							<h3 class="font-semibold">Ahmed Hassan</h3>
							<p class="text-sm text-gray-500">1 day ago</p>
						</div>
					</div>
					<p class="mb-4">
						Attending the AfAS conference next month. Looking forward to networking with fellow
						astronomers!
					</p>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Content class="pt-6">
					<div class="flex items-center mb-4">
						<img
							src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?w=50&h=50&fit=crop"
							alt="User Avatar"
							class="w-10 h-10 rounded-full mr-4"
						/>
						<div>
							<h3 class="font-semibold">Maria Rodriguez</h3>
							<p class="text-sm text-gray-500">3 days ago</p>
						</div>
					</div>
					<p class="mb-4">
						New telescope observations reveal interesting patterns in galaxy formation. Thoughts?
					</p>
					<img
						src="https://images.unsplash.com/photo-1446776653964-20c1d3a81b06?w=400&h=200&fit=crop"
						alt="Galaxy"
						class="w-full rounded-lg mb-4"
					/>
				</Card.Content>
			</Card.Root>
		</div>
	</main>
</div>
