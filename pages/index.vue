<template>
  <body>
    <section class="h-screen container mx-auto flex justify-center">
      <div class="lg:flex block">
        <div class="w-full lg:w-1/2">
          <img :src=" require('@/assets/images/ope.png') " class="w-full lg:w-full pt-8" alt="">
        </div>

        <div class="w-full lg:w-1/2 bottom-0">
          <p class="block font-normal md:text-lg text-base px-10 lg:text-xl lg: lg:items-center lg:h-screen lg:px-16 leading-snug lg:leading-tight">
            I'm Aramide Oluwaseun a Graphic Designer with 6+ years of experience in the management of the design process
            from conceptualization to implementation. Analytical and creative at solving business problems and management of lasting business relationships.
            <span class="block mt-4"> I am very curious individual who is always ready to learn new things and new ways to solve small and big problems, this curiosity allows me to discover, develop and create something out of nothing.
            I  love nature and every object I can find around me as well.</span>

          </p>
        </div>
      </div>
    </section>
  </body>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
