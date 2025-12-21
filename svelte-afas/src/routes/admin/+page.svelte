<div class="bg-gray-100">
	<main class="container mx-auto px-4 py-8">
		<h2 class="text-3xl font-bold text-center mb-8">Administration Portal</h2>
		<div class="space-y-8">
			<div class="bg-white p-6 rounded-lg shadow">
				<h3 class="text-xl font-semibold mb-4">Member Management</h3>
				<p>Search, update, and manage the member database.</p>
				<div class="mt-4">
					<input
						type="text"
						placeholder="Search members..."
						class="border border-gray-300 rounded px-3 py-2 w-full"
					/>
					<button class="mt-2 bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
						>Search</button
					>
				</div>
				<div class="mt-4">
					<table class="w-full table-auto">
						<thead>
							<tr class="bg-gray-200">
								<th class="px-4 py-2">Name</th>
								<th class="px-4 py-2">Membership #</th>
								<th class="px-4 py-2">Status</th>
								<th class="px-4 py-2">Actions</th>
							</tr>
						</thead>
						<tbody>
							<tr>
								<td class="border px-4 py-2">John Doe</td>
								<td class="border px-4 py-2">AFAS-001</td>
								<td class="border px-4 py-2">Active</td>
								<td class="border px-4 py-2"><button class="text-blue-500">Edit</button></td>
							</tr>
							<tr>
								<td class="border px-4 py-2">Jane Smith</td>
								<td class="border px-4 py-2">AFAS-002</td>
								<td class="border px-4 py-2">Active</td>
								<td class="border px-4 py-2"><button class="text-blue-500">Edit</button></td>
							</tr>
						</tbody>
					</table>
				</div>
			</div>
			<div class="bg-white p-6 rounded-lg shadow">
				<h3 class="text-xl font-semibold mb-4">Application Management</h3>
				<p>Overview of pending and processed applications.</p>
				<div class="mt-4">
					<h4 class="font-semibold">Pending Applications</h4>
					<ul class="list-disc list-inside">
						<li>Ahmed Hassan - Submitted 2 days ago</li>
						<li>Maria Rodriguez - Submitted 1 week ago</li>
					</ul>
					<h4 class="font-semibold mt-4">Processed Applications</h4>
					<ul class="list-disc list-inside">
						<li>John Doe - Approved</li>
						<li>Jane Smith - Approved</li>
					</ul>
				</div>
			</div>
			<div class="bg-white p-6 rounded-lg shadow">
				<h3 class="text-xl font-semibold mb-4">Reporting & Analytics</h3>
				<p>Membership growth, country distribution, and trends.</p>
				<div class="mt-4 grid md:grid-cols-3 gap-4">
					<div class="text-center">
						<h4 class="font-semibold">Membership Growth</h4>
						<img
							src="https://via.placeholder.com/200x150?text=Chart"
							alt="Growth Chart"
							class="mx-auto"
						/>
					</div>
					<div class="text-center">
						<h4 class="font-semibold">Country Distribution</h4>
						<img
							src="https://via.placeholder.com/200x150?text=Map"
							alt="Distribution Map"
							class="mx-auto"
						/>
					</div>
					<div class="text-center">
						<h4 class="font-semibold">Trends</h4>
						<img
							src="https://via.placeholder.com/200x150?text=Trends"
							alt="Trends Chart"
							class="mx-auto"
						/>
					</div>
				</div>
			</div>
			<div class="bg-white p-6 rounded-lg shadow">
				<h3 class="text-xl font-semibold mb-4">Communication Tools</h3>
				<p>Bulk email to all or segmented groups.</p>
				<div class="mt-4">
					<form>
						<div class="mb-4">
							<label for="recipient" class="block text-sm font-medium text-gray-700"
								>Recipient Group</label
							>
							<select
								id="recipient"
								class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md"
							>
								<option>All Members</option>
								<option>Full Members</option>
								<option>Student Members</option>
							</select>
						</div>
						<div class="mb-4">
							<label for="subject" class="block text-sm font-medium text-gray-700">Subject</label>
							<input
								type="text"
								id="subject"
								class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md"
							/>
						</div>
						<div class="mb-4">
							<label for="message" class="block text-sm font-medium text-gray-700">Message</label>
							<textarea
								id="message"
								rows="4"
								class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md"
							></textarea>
						</div>
						<button
							type="submit"
							class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
							>Send Email</button
						>
					</form>
				</div>
			</div>
		</div>
	</main>
</div>
