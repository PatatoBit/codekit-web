<section class="background">
	<div class="wrapper wrapper-center fullcenter">
		<h1>Why our clients</h1>
		<h1>choose Ensome?</h1>

		<p class="max-w-100 mt-5 text-center">
			Doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi
			architecto beatae vitae dicta sunt explicabo.
		</p>

		<div class="carousel carousel-center md:w-full md:p-0 px-10 space-x-4 mt-7 w-[100vw]">
			<div class="carousel-item card shadow">
				<img src="/icons@2x.jpg" alt="Machine Learning" />

				<h3>Machine learning</h3>
				<p>
					At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium
					voluptatum deleniti atque corrupti quos dolores.
				</p>
			</div>
			<div class="carousel-item card shadow">
				<img src="/icons@2x-1.jpg" alt="Machine Learning" />
				<h3>Embed analytics</h3>
				<p>
					At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium
					voluptatum deleniti atque corrupti quos dolores.
				</p>
			</div>
			<div class="carousel-item card shadow">
				<img src="/icons@2x-2.jpg" alt="Machine Learning" />
				<h3>Access control</h3>
				<p>
					At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium
					voluptatum deleniti atque corrupti quos dolores.
				</p>
			</div>
		</div>
	</div>
</section>

<style lang="scss">
	.background {
		background-color: var(--tertiary);
	}

	.card {
		width: calc(75rem / 3 - 7rem);
		aspect-ratio: 1;
		padding: 2rem;

		background-color: white;
	}

	.carousel-item {
		display: flex;
		flex-direction: column;
		gap: 1rem;
	}

	img {
		width: 70px;
		height: 70px;
	}
</style>
