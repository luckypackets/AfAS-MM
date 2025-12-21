<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
	import { Input } from '$lib/components/ui/input';
	import { Label } from '$lib/components/ui/label';
	import { Textarea } from '$lib/components/ui/textarea';
</script>

<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<h2 class="text-3xl font-bold text-center mb-8">Member Registration</h2>
		<Card.Root class="max-w-2xl mx-auto">
			<Card.Content class="pt-6">
				<form action="#" method="post" enctype="multipart/form-data">
					<div class="grid md:grid-cols-2 gap-4">
						<div class="space-y-2">
							<Label for="first_name">First Name</Label>
							<Input type="text" id="first_name" name="first_name" />
						</div>
						<div class="space-y-2">
							<Label for="last_name">Last Name</Label>
							<Input type="text" id="last_name" name="last_name" />
						</div>
					</div>
					<div class="mt-4 space-y-2">
						<Label for="email">Email</Label>
						<Input type="email" id="email" name="email" />
					</div>
					<div class="mt-4 space-y-2">
						<Label for="phone">Phone</Label>
						<Input type="tel" id="phone" name="phone" />
					</div>
					<div class="mt-4 space-y-2">
						<Label for="address">Address</Label>
						<Textarea id="address" name="address" rows={3} />
					</div>
					<div class="mt-4 space-y-2">
						<Label for="institution">Institution</Label>
						<Input type="text" id="institution" name="institution" />
					</div>
					<div class="mt-4 space-y-2">
						<Label for="position">Position/Title</Label>
						<Input type="text" id="position" name="position" />
					</div>
					<div class="mt-4 space-y-2">
						<Label for="research_interests">Research Interests</Label>
						<Textarea id="research_interests" name="research_interests" rows={3} />
					</div>
					<div class="mt-4 space-y-2">
						<Label for="publications">Notable Publications</Label>
						<Textarea id="publications" name="publications" rows={3} />
					</div>
					<div class="mt-4 space-y-2">
						<Label for="cv">Upload CV</Label>
						<Input type="file" id="cv" name="cv" accept=".pdf,.doc,.docx" />
					</div>
					<div class="mt-4 space-y-2">
						<Label for="other_docs">Other Documentation</Label>
						<Input type="file" id="other_docs" name="other_docs" multiple />
					</div>
					<div class="mt-6">
						<Button type="submit" class="w-full">Register</Button>
					</div>
				</form>
			</Card.Content>
		</Card.Root>
	</main>
</div>
