<template>
  <div>
    <section class="h-screen container mx-auto flex justify-center">
      <div class="lg:flex block">
        <div class="w-full lg:w-1/2 xl:w-2/5">
          <img :src=" require('@/assets/images/ope.png') " class="w-full lg:w-full pt-8" alt="">
        </div>

        <div class="w-full lg:w-1/2 bottom-0 lg:flex lg:items-center lg:justify-center lg:h-screen xl:w-3/5">
          <div>
            <p class="block py-6 lg:py-0 font-normal text-xl text-base px-10 lg:px-16 leading-snug lg:leading-tight 2xl:text-3xl xl:px-48">
              I'm Aramide Oluwaseun a Graphic Designer with 6+ years of experience in the management of the design process
              from conceptualization to implementation. Analytical and creative at solving business problems and management of lasting business relationships.
              <span class="block mt-4"> I am very curious individual who is always ready to learn new things and new ways to solve small and big problems, this curiosity allows me to discover, develop and create something out of nothing.
              I  love nature and every object I can find around me as well.</span>
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="h-screen flex justify-center items-center bg-gray-700">
      <div class="">
        <h1 class="font-bold text-6xl xl:text-7xl text-white my-4 flex justify-center mx-auto">My Works</h1>
        <p class="text-xl flex justify-center mx-auto">Check out some of my works below.</p>
        <div class="grid grid-cols-3 my-6">
          <div class="bg-white h-96 w-2/6">

          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
