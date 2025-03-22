<section class="background">
	<div class="wrapper py-10">
		<form action="" class="flex flex-col md:flex-row gap-2 justify-between">
			<div class="flex flex-col">
				<h1 class="md:text-start text-center text-white">Subscribe to our newsletter</h1>
				<p class="text-white hidden md:block">
					Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque
					laudantium.
				</p>
			</div>

			<div class="flex flex-col md:flex-row gap-2 self-center">
				<input type="email" placeholder="Your email" class="input w-full" />
				<button class="btn font-bold">Subscribe</button>
			</div>
		</form>
	</div>
</section>

<style>
	.background {
		background-color: var(--primary);
	}

	input {
		border: 1px solid white;
		background-color: transparent;
		color: white;
	}

	button {
		background-color: white;
		color: var(--primary);
	}
</style>
