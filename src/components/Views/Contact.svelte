<section class="background">
	<div class="wrapper fullcenter hero-reverse">
		<div class="content">
			<h1>Left questions? Contact us now for a free consultation and free trial!</h1>

			<p class="hidden md:block pb-10">
				Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam,
				nisi ut aliquid ex ea commodi.
			</p>

			<div class="flex flex-col">
				<p class="label">Email address</p>
				<p>ensome@info.co.us</p>
			</div>

			<div class="flex flex-col">
				<p class="label">Phone number</p>
				<p>+1601-201-5580</p>
			</div>

			<div class="flex flex-col">
				<p class="label">Address</p>
				<p>1642 Washington Avenue, Jackson, MS, Mississippi, 39201</p>
			</div>
		</div>

		<form>
			<h2>Contact us</h2>

			<div class="flex flex-col">
				<label for="name">Name</label>
				<input type="text" placeholder="Andrea" />
			</div>

			<div class="flex flex-col">
				<label for="email">Email</label>
				<input type="email" placeholder="andrea@gmaol.com" />
			</div>

			<div class="flex flex-col">
				<label for="message">Theme</label>
				<input type="email" placeholder="Job" />
			</div>

			<div class="flex flex-col">
				<label for="message">Message</label>
				<input type="email" placeholder="Your message" />
			</div>

			<button class="btn btn-primary self-end justify-end mt-10">Send</button>
		</form>

		<button class="block md:hidden btn btn-primary w-full">Contact Us</button>
	</div>
</section>

<style lang="scss">
	form {
		width: 45rem;
		height: 35rem;
		background-color: white;

		border-radius: 0.5rem;
		padding: 2rem;

		display: flex;
		flex-direction: column;
		gap: 2rem;

		@media screen and (max-width: 768px) {
			display: none;
		}

		input {
			border-bottom: 1px solid rgb(189, 189, 189);
		}
	}

	.wrapper {
		gap: 15rem;
	}

	.background {
		background-color: var(--tertiary);
	}
</style>
