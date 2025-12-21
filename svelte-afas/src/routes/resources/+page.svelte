<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
</script>

<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<h2 class="text-3xl font-bold text-center mb-8">Members-Only Resource Hub</h2>
		<div class="space-y-8">
			<Card.Root>
				<Card.Header>
					<Card.Title>Journals</Card.Title>
				</Card.Header>
				<Card.Content>
					<ul class="space-y-2">
						<li>
							<Button variant="link" class="p-0 h-auto">
								African Journal of Astronomy - Vol. 12, Issue 3
							</Button>
							<span class="text-sm text-gray-500 ml-2">(PDF)</span>
						</li>
						<li>
							<Button variant="link" class="p-0 h-auto">Cosmology in Africa: Recent Advances</Button
							>
							<span class="text-sm text-gray-500 ml-2">(PDF)</span>
						</li>
						<li>
							<Button variant="link" class="p-0 h-auto">
								Exoplanet Research from African Observatories
							</Button>
							<span class="text-sm text-gray-500 ml-2">(PDF)</span>
						</li>
					</ul>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Webinars</Card.Title>
				</Card.Header>
				<Card.Content>
					<ul class="space-y-2">
						<li>
							<Button variant="link" class="p-0 h-auto">Introduction to Radio Astronomy</Button>
							<span class="text-sm text-gray-500 ml-2">(Video Recording)</span>
						</li>
						<li>
							<Button variant="link" class="p-0 h-auto">Machine Learning in Astrophysics</Button>
							<span class="text-sm text-gray-500 ml-2">(Video Recording)</span>
						</li>
						<li>
							<Button variant="link" class="p-0 h-auto">
								African Night Sky: Cultural and Scientific Perspectives
							</Button>
							<span class="text-sm text-gray-500 ml-2">(Video Recording)</span>
						</li>
					</ul>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Research Papers</Card.Title>
				</Card.Header>
				<Card.Content>
					<ul class="space-y-2">
						<li>
							<Button variant="link" class="p-0 h-auto">
								Stellar Populations in the Large Magellanic Cloud
							</Button>
							<span class="text-sm text-gray-500 ml-2">(PDF)</span>
						</li>
						<li>
							<Button variant="link" class="p-0 h-auto">
								Gravitational Lensing by Galaxy Clusters
							</Button>
							<span class="text-sm text-gray-500 ml-2">(PDF)</span>
						</li>
						<li>
							<Button variant="link" class="p-0 h-auto">
								Radio Observations of Active Galactic Nuclei
							</Button>
							<span class="text-sm text-gray-500 ml-2">(PDF)</span>
						</li>
					</ul>
				</Card.Content>
			</Card.Root>
		</div>
	</main>
</div>
