<footer class="footer sm:footer-horizontal text-base-content p-10 wrapper">
	<aside>
		<img src="/logo_blue.jpg" alt="Ensome logo" class="w-30" />
	</aside>

	<nav>
		<h6 class="footer-title">About</h6>
		<a class="link link-hover">Home</a>
		<a class="link link-hover">About us</a>
		<a class="link link-hover">Services</a>
		<a class="link link-hover">Solutions</a>
	</nav>
	<nav>
		<h6 class="footer-title">Information</h6>
		<a class="link link-hover">Contacts</a>
		<a class="link link-hover">Our team</a>
		<a class="link link-hover">About us</a>
		<a class="link link-hover">FAQ</a>
	</nav>
	<nav>
		<h6 class="footer-title">Service</h6>
		<a class="link link-hover">Pages</a>
		<a class="link link-hover">Elements</a>
		<a class="link link-hover">Site map</a>
		<a class="link link-hover">Pricing</a>
		<a class="link link-hover">FAQ</a>
	</nav>
</footer>

<section class="wrapper block md:hidden">
	<div class="collapse collapse-arrow bg-base-100">
		<input type="radio" name="my-accordion-2" />
		<div class="collapse-title font-semibold border-b-2 border-gray-400 rounded-none">
			Quick link
		</div>
		<div class="collapse-content text-sm">Hello world</div>
	</div>
	<div class="collapse collapse-arrow bg-base-100">
		<input type="radio" name="my-accordion-2" />
		<div class="collapse-title font-semibold border-b-2 border-gray-400 rounded-none">Service</div>
		<div class="collapse-content text-sm">Hello world</div>
	</div>
	<div class="collapse collapse-arrow bg-base-100">
		<input type="radio" name="my-accordion-2" />
		<div class="collapse-title font-semibold border-b-2 border-gray-400 rounded-none">
			Contact info
		</div>
		<div class="collapse-content text-sm">Hello world</div>
	</div>
</section>

<section class="wrapper">
	<hr class="text-gray-300 h-10" />

	<div class="flex flex-row justify-between pb-5">
		<div class="flex-col gap-5 hidden md:flex">
			<h3>Contacts</h3>

			<div class="flex gap-10">
				<div class="flex flex-col">
					<p>+1 601-201-5580</p>
					<p class="font-bold">ensome@info.co.us</p>
				</div>

				<div class="flex flex-col">
					<p>1642 Washington Avenue, Jackson, MS, 39201</p>
					<p class="font-bold">Driving derections</p>
				</div>
			</div>

			<div class="flex flex-col"></div>
		</div>

		<div class="flex flex-col gap-3">
			<h3>Follow us</h3>

			<div class="flex gap-5 medias">
				<img src="/icon_facebook.jpg" alt="" />
				<img src="/icon_twitter.jpg" alt="" />
				<img src="/icon_linkedin.jpg" alt="" />
				<img src="/icon_youtube.jpg" alt="" />
				<img src="/icon_dribbble.jpg" alt="" />
				<img src="/icon_behance.jpg" alt="" />
			</div>
		</div>
	</div>
</section>

<section class="wrapper flex flex-col justify-between pb-5">
	<hr class="text-gray-300 h-10 hidden md:block" />

	<div class="flex flex-col md:flex-row justify-between">
		<div class="flex flex-row gap-5 label">
			<p class="font-bold">Privacy policy</p>
			<p class="font-bold">Terms of us</p>
		</div>
		<hr class="text-gray-300 my-3 md:hidden block" />

		<div>
			<p class="text-center label">© 2022 Ensome. All rights reserved.</p>
		</div>
	</div>
</section>

<style lang="scss">
	nav {
		display: flex;
		flex-direction: column;

		@media screen and (max-width: 768px) {
			display: none;
		}
	}

	.medias {
		img {
			width: 30px;
			height: 30px;
		}
	}
</style>
