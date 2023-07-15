<section class="bg-[#003049] h-screen sm:p-10 p-5">
	<div class="flex justify-between">
		<div>LOGO</div>
		<nav>
			<ul class="flex space-x-2 text-xl">
				<li><a class="hover:underline hover:text-yellow-600" href="#about-me">About Me</a></li>
				<li><a class="hover:underline hover:text-yellow-600" href="#projects">Projects</a></li>
				<li><a class="hover:underline hover:text-yellow-600" href="#contact">Contact</a></li>
			</ul>
		</nav>
	</div>
	<div class="flex justify-between items-center sm:pt-32 sm:pr-48">
		<div class="flex flex-col h-[100%] justify-center">
			<div class="md:ml-20 mt-20 mb-20">
				<h1 class="md:text-6xl text-4xl font-bold text-[#f77f00]">Bharath Mohan</h1>
				<p class="mt-4 text-2xl font-light text-gray-200">Unemployed ☹️</p>
				<a href="#about-me">
					<button class="btn variant-filled-primary mt-4 hover:underline"> About Me </button>
				</a>
			</div>
		</div>
		<div class="flex flex-col space-y-4">
			<a href="https://github.com/broxdeez/">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="none"
					stroke="currentColor"
					stroke-width="2"
					stroke-linecap="round"
					stroke-linejoin="round"
					class="lucide lucide-github hover:stroke-yellow-600"
					><path
						d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"
					/><path d="M9 18c-4.51 2-5-2-7-2" /></svg
				>
			</a>
			<a href="https://www.linkedin.com/in/bharath-mohan/">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="none"
					stroke="currentColor"
					stroke-width="2"
					stroke-linecap="round"
					stroke-linejoin="round"
					class="lucide lucide-linkedin hover:stroke-yellow-600"
					><path
						d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"
					/><rect width="4" height="12" x="2" y="9" /><circle cx="4" cy="4" r="2" /></svg
				>
			</a>
			<a href="https://www.instagram.com/bharathm_1/">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="none"
					stroke="currentColor"
					stroke-width="2"
					stroke-linecap="round"
					stroke-linejoin="round"
					class="lucide lucide-instagram hover:stroke-yellow-600"
					><rect width="20" height="20" x="2" y="2" rx="5" ry="5" /><path
						d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"
					/><line x1="17.5" x2="17.51" y1="6.5" y2="6.5" /></svg
				>
			</a>
		</div>
	</div>
</section>

<section class="bg-white h-[500px] border-b-2 flex flex-col sm:flex-row items-center" id="about-me">
	<div class="flex flex-col justify-around p-10 sm:space-y-5 sm:w-1/2">
		<h2 class="h2 text-black">About Me</h2>
		<p class="text-black text-xl">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Id corrupti ab aperiam laboriosam,
			nobis voluptate rerum cupiditate ullam, amet doloremque
		</p>
	</div>
	<!-- headshot -->
	<div
		class="flex mx-auto bg-gradient-to-b from-blue-950 rounded-full sm:w-80 sm:h-80 w-40 h-40 sm:mt-20"
	>
		<img src="./bharath.png" alt="headshot" />
	</div>
</section>

<section class="bg-[#457b9d] md:h-[700px] border-b-2 p-5" id="projects">
	<h2 class="h2 text-center mt-10">Projects</h2>
	<!-- <div class="flex md:flex-row flex-col space-y-10 md:space-x-10 mt-10 md:justify-center items-center mb-10"> -->
	<div class='flex flex-col md:flex-row md:space-x-10 md:justify-center p-5 md:p-14'>
		<a
			href="https://broxdeez-moviedb.vercel.app/"
			class="flex flex-col mb-5 justify-center items-center space-y-5 max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-2xl hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700"
		>
			<img class="w-60 h-60 rounded-full object-cover" src="./project 1.png" alt="project_1" />
			<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Movie DB</h5>
			<p class="font-normal p-3 text-gray-700 dark:text-gray-400">
				Collection of latest movies fetched from TMDB api
			</p>
		</a>
		<a
			href="https://broxdeez-recipe.vercel.app/"
			class="flex flex-col mb-5 justify-center items-center space-y-5 max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-2xl hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700"
		>
			<img class="w-60 h-60 rounded-full object-cover" src="./project 2.png" alt="project_1" />
			<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Recipe</h5>
			<p class="font-normal p-3 text-gray-700 dark:text-gray-400">
				Recipe cards fetched from spoonacular api with instructions and ingredients
			</p>
		</a>
		<a
			href="https://broxdeez-svelte-form.vercel.app/"
			class="flex flex-col mb-5 justify-center items-center space-y-5 max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-2xl hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700"
		>
			<img class="w-60 h-60 rounded-full object-cover" src="./project 3.png" alt="project_1" />
			<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
				Skeleton Forms
			</h5>
			<p class="font-normal p-3 text-gray-700 dark:text-gray-400">
				Form created using Skeleton UI component with persisted storage
			</p>
		</a>
	</div>
</section>

<section class="bg-white h-[800px]" id="contact">
	<h1 class="h1 text-center text-black p-10">Contact Me</h1>
	<div class="flex items-center justify-center p-12">
		<div class="mx-auto w-full max-w-[550px]">
			<form action="" method="">
				<div class="mb-5">
					<label for="name" class="mb-3 block text-base font-medium text-[#07074D]">
						Full Name
					</label>
					<input
						type="text"
						name="name"
						id="name"
						placeholder="Full Name"
						class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"
					/>
				</div>
				<div class="mb-5">
					<label for="email" class="mb-3 block text-base font-medium text-[#07074D]">
						Email Address
					</label>
					<input
						type="email"
						name="email"
						id="email"
						placeholder="example@domain.com"
						class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"
					/>
				</div>
				<div class="mb-5">
					<label for="subject" class="mb-3 block text-base font-medium text-[#07074D]">
						Subject
					</label>
					<input
						type="text"
						name="subject"
						id="subject"
						placeholder="Enter your subject"
						class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"
					/>
				</div>
				<div class="mb-5">
					<label for="message" class="mb-3 block text-base font-medium text-[#07074D]">
						Message
					</label>
					<textarea
						rows="4"
						name="message"
						id="message"
						placeholder="Type your message"
						class="w-full resize-none rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"
					/>
				</div>
				<div>
					<button
						class="hover:shadow-form rounded-md bg-[#6A64F1] py-3 px-8 text-base font-semibold text-white outline-none"
					>
						Submit
					</button>
				</div>
			</form>
		</div>
	</div>
</section>
