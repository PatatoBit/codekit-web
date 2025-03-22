<nav class="wrapper pt-5 flex flex-row w-full justify-between">
	<div class="flex gap-20">
		<img src="/logo_blue.jpg" alt="Ensome Logo" />

		<a href="/">Home</a>
		<a href="/solutions">Solutions</a>
		<a href="/elements">Elements</a>
	</div>

	<button class="btn btn-primary hidden md:block"> Watch the demo </button>
</nav>

<style lang="scss">
	img {
		object-fit: contain;
		width: 7rem;
		height: autp;
	}

	a {
		align-self: center;
		&:hover {
			font-weight: 700;
		}

		@media screen and (max-width: 768px) {
			display: none;
		}
	}
</style>
