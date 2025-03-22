<section class="wrapper fullcenter py-15">
	<div class="flex flex-col md:flex-row justify-between w-full">
		<div class="flex flex-col">
			<h1>Trusted by the best</h1>
			<h1>in the business</h1>
		</div>

		<div class="button">
			<div class="btn">Previous</div>
			<div class="btn">Next</div>
		</div>
	</div>

	<div
		class="carousel carousel-center md:w-full md:p-0 px-10 space-x-4 mt-7 w-[100vw] overflow-visible"
	>
		<div class="carousel-item card shadow">
			<p>
				“Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam,
				nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea
				voluptate velit esse quam nihil molestiae consequatur, vel illum.”
			</p>

			<h3>Alex Bern</h3>
			<p>CEO by PixelPerfect</p>
		</div>
	</div>
</section>

<style lang="scss">
	.background {
		background-color: var(--tertiary);
	}

	.card {
		width: calc(75rem / 2 - 7rem);
		padding: 2rem;

		background-color: white;
	}

	.carousel-item {
		display: flex;
		flex-direction: column;
		gap: 1rem;
	}
</style>
