<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
</script>

<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<Card.Root class="max-w-4xl mx-auto">
			<Card.Content class="pt-6">
				<div class="flex items-center mb-8">
					<img
						src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=150&h=150&fit=crop"
						alt="Profile"
						class="w-24 h-24 rounded-full mr-6"
					/>
					<div>
						<h2 class="text-3xl font-bold">John Doe</h2>
						<p class="text-gray-600">Astronomer at University of Cape Town</p>
					</div>
				</div>
				<div class="grid md:grid-cols-2 gap-8">
					<div>
						<h3 class="text-xl font-semibold mb-4">Personal Information</h3>
						<p><strong>Name:</strong> John Doe</p>
						<p><strong>Email:</strong> john.doe@example.com</p>
						<p><strong>Phone:</strong> +27 123 456 789</p>
						<p><strong>Address:</strong> Cape Town, South Africa</p>
					</div>
					<div>
						<h3 class="text-xl font-semibold mb-4">Academic & Institutional</h3>
						<p><strong>Institution:</strong> University of Cape Town</p>
						<p><strong>Position:</strong> Research Fellow</p>
					</div>
				</div>
				<div class="mt-8">
					<h3 class="text-xl font-semibold mb-4">Research Interests</h3>
					<p>Exoplanets, Stellar Astrophysics, Observational Astronomy</p>
				</div>
				<div class="mt-8">
					<h3 class="text-xl font-semibold mb-4">Notable Publications</h3>
					<ul class="list-disc list-inside">
						<li>Doe, J. (2023). "Advances in Exoplanet Detection". Journal of Astronomy.</li>
						<li>Doe, J., & Smith, A. (2022). "Stellar Evolution Models". Astrophysics Letters.</li>
					</ul>
				</div>
				<div class="mt-8">
					<h3 class="text-xl font-semibold mb-4">Documents</h3>
					<div class="flex gap-4">
						<Button variant="link" class="p-0 h-auto">Download CV</Button>
						<Button variant="link" class="p-0 h-auto">Other Documents</Button>
					</div>
				</div>
			</Card.Content>
		</Card.Root>

		<div class="max-w-4xl mx-auto mt-8 space-y-8">
			<Card.Root>
				<Card.Header>
					<Card.Title>Personal Dashboard</Card.Title>
				</Card.Header>
				<Card.Content>
					<p><strong>Membership Status:</strong> Active</p>
					<p><strong>Renewal Date:</strong> December 31, 2026</p>
					<h4 class="font-semibold mt-4">Society Updates</h4>
					<ul class="list-disc list-inside">
						<li>Annual Conference scheduled for June 2026 in Nairobi.</li>
						<li>New research grant opportunities available.</li>
					</ul>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Profile Management</Card.Title>
				</Card.Header>
				<Card.Content>
					<p class="mb-4">
						Update your contact information, affiliation, publications, and profile picture.
					</p>
					<Button>Edit Profile</Button>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Membership Details</Card.Title>
				</Card.Header>
				<Card.Content>
					<p><strong>Membership Number:</strong> AFAS-001</p>
					<p><strong>Membership Type:</strong> Full</p>
					<p><strong>Join Date:</strong> January 15, 2023</p>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Membership Certificates</Card.Title>
				</Card.Header>
				<Card.Content>
					<p class="mb-4">
						Your membership certificate is automatically generated and can be downloaded as a PDF.
					</p>
					<p><strong>Certificate Details:</strong></p>
					<ul class="list-disc list-inside mb-4">
						<li>Name: John Doe</li>
						<li>Membership Number: AFAS-001</li>
						<li>Type: Full</li>
						<li>Admission Date: January 15, 2023</li>
					</ul>
					<Button>Download PDF Certificate</Button>
					<div class="mt-4">
						<p><strong>QR Code for Verification:</strong></p>
						<img src="https://via.placeholder.com/100x100?text=QR" alt="QR Code" class="mt-2" />
						<p class="text-sm text-gray-600">Scan to verify authenticity on the AfAS website.</p>
					</div>
				</Card.Content>
			</Card.Root>
		</div>
	</main>
</div>
