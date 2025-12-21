<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
</script>

<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<h2 class="text-3xl font-bold text-center mb-8">Membership Fees & Online Payments</h2>
		<Card.Root class="max-w-2xl mx-auto">
			<Card.Content class="pt-6">
				<p class="mb-6">
					Pay your membership fees securely using PayFast, South Africa's leading payment gateway
					for convenient and secure transactions.
				</p>
				<div class="mb-6">
					<h3 class="text-xl font-semibold mb-4">Membership Types & Fees</h3>
					<ul class="list-disc list-inside">
						<li>Full Member: R50/year</li>
						<li>Associate Member: R30/year</li>
						<li>Student Member: R20/year</li>
					</ul>
				</div>
				<div>
					<h3 class="text-xl font-semibold mb-4">Choose Payment Method</h3>
					<Button variant="default" size="lg" class="bg-yellow-500 hover:bg-yellow-700">
						Pay with PayFast
					</Button>
				</div>
			</Card.Content>
		</Card.Root>
	</main>
</div>
