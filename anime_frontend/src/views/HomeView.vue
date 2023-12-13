<template>
  <main>
    <section class="text-gray-600 body-font">
      <div class="container mx-auto flex px-5 py-24 items-center justify-center flex-col">
        <iframe class="lg:w-2/6 md:w-3/6 w-5/6 mb-10 object-cover object-center rounded" src="https://lottie.host/embed/338fa1ab-3603-4dee-b191-452aee68aa96/bGZtBGV40v.json"></iframe>
        <!-- <img class="lg:w-2/6 md:w-3/6 w-5/6 mb-10 object-cover object-center rounded" alt="hero" src="https://dummyimage.com/720x600"> -->
        <div class="text-center lg:w-2/3 w-full">
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Welcome to Cookhook, your go-to destination for culinary exploration!</h1>
          <p class="mb-8 leading-relaxed">
            Immerse yourself in the culinary lifestyle with Cookhook. Embrace meggings, DIY techniques, and echo park vibes. Our app celebrates the diverse and trendy aspects of food culture.
          </p>
          <div class="flex justify-center">
            <RouterLink :to="{'name': 'signup'}" class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">
              Sign up
            </RouterLink>
            <RouterLink :to="{'name': 'login'}" class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg">
              Sign in
            </RouterLink>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>
