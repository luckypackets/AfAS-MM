<script lang="ts">
	import * as Card from '$lib/components/ui/card';
	import { Button } from '$lib/components/ui/button';
	import { Input } from '$lib/components/ui/input';
	import { Label } from '$lib/components/ui/label';
	import * as Select from '$lib/components/ui/select';
	import { Textarea } from '$lib/components/ui/textarea';
</script>

<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<h2 class="text-3xl font-bold text-center mb-8">Administration Portal</h2>
		<div class="space-y-8">
			<Card.Root>
				<Card.Header>
					<Card.Title>Member Management</Card.Title>
					<Card.Description>Search, update, and manage the member database.</Card.Description>
				</Card.Header>
				<Card.Content>
					<div class="space-y-4">
						<div>
							<Input placeholder="Search members..." />
							<Button class="mt-2">Search</Button>
						</div>
						<div class="overflow-x-auto">
							<table class="w-full">
								<thead>
									<tr class="border-b">
										<th class="px-4 py-2 text-left">Name</th>
										<th class="px-4 py-2 text-left">Membership #</th>
										<th class="px-4 py-2 text-left">Status</th>
										<th class="px-4 py-2 text-left">Actions</th>
									</tr>
								</thead>
								<tbody>
									<tr class="border-b">
										<td class="px-4 py-2">John Doe</td>
										<td class="px-4 py-2">AFAS-001</td>
										<td class="px-4 py-2">Active</td>
										<td class="px-4 py-2">
											<Button variant="link" class="p-0 h-auto">Edit</Button>
										</td>
									</tr>
									<tr class="border-b">
										<td class="px-4 py-2">Jane Smith</td>
										<td class="px-4 py-2">AFAS-002</td>
										<td class="px-4 py-2">Active</td>
										<td class="px-4 py-2">
											<Button variant="link" class="p-0 h-auto">Edit</Button>
										</td>
									</tr>
								</tbody>
							</table>
						</div>
					</div>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Application Management</Card.Title>
					<Card.Description>Overview of pending and processed applications.</Card.Description>
				</Card.Header>
				<Card.Content>
					<div>
						<h4 class="font-semibold mb-2">Pending Applications</h4>
						<ul class="list-disc list-inside mb-4">
							<li>Ahmed Hassan - Submitted 2 days ago</li>
							<li>Maria Rodriguez - Submitted 1 week ago</li>
						</ul>
						<h4 class="font-semibold mb-2">Processed Applications</h4>
						<ul class="list-disc list-inside">
							<li>John Doe - Approved</li>
							<li>Jane Smith - Approved</li>
						</ul>
					</div>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Reporting & Analytics</Card.Title>
					<Card.Description>Membership growth, country distribution, and trends.</Card.Description>
				</Card.Header>
				<Card.Content>
					<div class="grid md:grid-cols-3 gap-4">
						<div class="text-center">
							<h4 class="font-semibold mb-2">Membership Growth</h4>
							<img
								src="https://via.placeholder.com/200x150?text=Chart"
								alt="Growth Chart"
								class="mx-auto"
							/>
						</div>
						<div class="text-center">
							<h4 class="font-semibold mb-2">Country Distribution</h4>
							<img
								src="https://via.placeholder.com/200x150?text=Map"
								alt="Distribution Map"
								class="mx-auto"
							/>
						</div>
						<div class="text-center">
							<h4 class="font-semibold mb-2">Trends</h4>
							<img
								src="https://via.placeholder.com/200x150?text=Trends"
								alt="Trends Chart"
								class="mx-auto"
							/>
						</div>
					</div>
				</Card.Content>
			</Card.Root>

			<Card.Root>
				<Card.Header>
					<Card.Title>Communication Tools</Card.Title>
					<Card.Description>Bulk email to all or segmented groups.</Card.Description>
				</Card.Header>
				<Card.Content>
					<form class="space-y-4">
						<div class="space-y-2">
							<Label for="recipient">Recipient Group</Label>
							<Select.Root>
								<Select.Trigger id="recipient">
									<Select.Value placeholder="Select a group" />
								</Select.Trigger>
								<Select.Content>
									<Select.Item value="all">All Members</Select.Item>
									<Select.Item value="full">Full Members</Select.Item>
									<Select.Item value="student">Student Members</Select.Item>
								</Select.Content>
							</Select.Root>
						</div>
						<div class="space-y-2">
							<Label for="subject">Subject</Label>
							<Input id="subject" type="text" />
						</div>
						<div class="space-y-2">
							<Label for="message">Message</Label>
							<Textarea id="message" rows={4} />
						</div>
						<Button type="submit">Send Email</Button>
					</form>
				</Card.Content>
			</Card.Root>
		</div>
	</main>
</div>
