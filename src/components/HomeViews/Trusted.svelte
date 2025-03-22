<script lang="ts">
	const images = ['/001_img_person_1.jpg', '/002_img_person_2.jpg'];
</script>

<section class="wrapper fullcenter py-15">
	<div class="flex flex-col md:flex-row justify-between w-full">
		<div class="flex flex-col">
			<h1>Trusted by the best</h1>
			<h1>in the business</h1>
		</div>

		<div class="button">
			<a class="btn" href="#slide0">Previous</a>
			<a class="btn" href="#slide1">Next</a>
		</div>
	</div>

	<div class="overflow-x-auto px-10">
		<div
			class="carousel carousel-center md:w-full md:p-0 px-10 space-x-4 mt-15 w-[100vw] overflow-visible"
		>
			{#each images as image, index}
				<div id={`slide${index}`} class="carousel-item relative card shadow">
					<div class="image">
						<img src={image} alt="Person 1" />
					</div>

					<p>
						“Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit
						laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure
						reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel
						illum.”
					</p>

					<div class="flex flex-col">
						<h3>Alex Bern</h3>
						<p>CEO by PixelPerfect</p>
					</div>
				</div>
			{/each}
		</div>
	</div>
</section>

<style lang="scss">
	.wrapper {
		min-height: 0;
	}

	.background {
		background-color: var(--tertiary);
	}

	.card {
		position: relative;
		width: calc(75rem / 2 - 7rem);
		padding: 5rem 2rem 2rem 2rem;
		background-color: white;
		overflow: visible;

		@media screen and (max-width: 768px) {
			width: calc(100vw - 10rem);
		}

		.image {
			position: absolute;
			top: -2.5rem;
			width: 80px;
			height: 80px;
		}
	}

	.carousel-item {
		display: flex;
		flex-direction: column;
		gap: 1rem;
	}
</style>
