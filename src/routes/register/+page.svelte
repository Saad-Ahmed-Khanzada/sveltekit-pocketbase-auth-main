<script>
	import DiCode from 'svelte-icons/di/DiCode.svelte';
</script>

<div class="flex flex-col items-center h-full w-full pt-0">
	<!-- <div class="h-24 w-24 text-primary">
		<DiCode />
	</div> -->
	<h2 class="mt-0 text-center text-3xl font-bold tracking-tight text-base-content">
		Register for an account
	</h2>
	<p class="text-center mt-1">
		Or <a href="/login" class="text-primary font-medium hover:cursor-pointer">sign in</a> if you already
		have an account.
	</p>
	<div class="bg-white py-0 shadow-md rounded-lg w-full max-w-sm mt-0">
		<form method="POST" action="?/register" class="flex flex-col items-center space-y-2 w-full">
			<div class="form-control w-full max-w-xs">
				<label for="name" class="label font-medium pb-1">
					<span class="label-text">Name</span>
				</label>
				<input type="text" name="name" class="input input-bordered w-full max-w-xs" />
			</div>
			<div class="form-control w-full max-w-xs">
				<label for="email" class="label font-medium pb-1">
					<span class="label-text">Email</span>
				</label>
				<input type="email" name="email" class="input input-bordered w-full max-w-xs" />
			</div>
			<div class="form-control w-full max-w-xs">
				<label for="password" class="label font-medium pb-1">
					<span class="label-text">Password</span>
				</label>
				<input type="password" name="password" class="input input-bordered w-full max-w-xs" />
			</div>
			<div class="form-control w-full max-w-xs">
				<label for="passwordConfirm" class="label font-medium pb-1">
					<span class="label-text">Confirm Password</span>
				</label>
				<input
					type="password"
					name="passwordConfirm"
					class="input input-bordered w-full max-w-sm"
				/>
			</div>
			<div class="w-full max-w-xs pt-3">
				<button class="btn btn-primary w-full max-w-xs">Register</button>
			</div>
		</form>
	</div>
</div>
