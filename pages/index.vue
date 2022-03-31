<template>
  <body>
    <section class="h-screen container mx-auto flex justify-center">
      <div class="lg:flex block">
        <div class="w-full lg:w-1/2 relative">
          <img :src=" require('@/assets/images/ope.png') " class="w-full lg:w-full absolute top-10 lg:top-14 z-1" alt="">
        </div>

        <div class="w-full lg:w-1/2 relative lg:mt-0 bottom-0">
          <p class="font-normal md:text-lg text-base px-10 lg:text-xl lg:flex pt-32 lg:pt-0  lg:items-center lg:h-screen">
            I'm Aramide Oluwaseun a Graphic Designer with 6+ years of experience in the management of the design process
            from conceptualization to implementation. Analytical and creative at solving bussiness problems and management of lasting business relationships.
            I am very curious individual who is always ready to learn new things and new ways to solve small and big problems, this curiosity allows me to discover, develop and create something out of nothing.
            I  love nature and every object I can find around me as well.
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
