<template>
  <div class="bg-gray-600 py-10">
    <div class="">
      <h1 class="text-4xl font-bold text-white flex justify-center mx-auto lg:text-6xl">Logo design</h1>
      <VueSlickCarousel :autoplay="true" :cssEase="'ease'" :pauseOnHover="true" :variableWidth="true" :arrows="false" :dots="false" :adaptiveHeight="true"
       class="gap-20 mt-8 w-full ">

        <div class="bg-white relative mx-6" style="min-width: 400px;">
          <img :src="require('@/assets/images/portfolio/logo design/IMG_20191029_194327_299.jpg')" class="" />
        </div>   

        <div class="bg-white relative mx-6" style="min-width: 400px;">
          <img :src="require('@/assets/images/portfolio/logo design/IMG_20191029_194327_299.jpg')" class="" />
        </div>        
        
        <div class="bg-white relative mx-6" style="min-width: 400px;">
          <img :src="require('@/assets/images/portfolio/logo design/IMG_20191029_194327_299.jpg')" class="" />
        </div>           
        
        <div class="bg-white relative mx-6" style="min-width: 400px;">
          <img :src="require('@/assets/images/portfolio/logo design/IMG_20191029_194327_299.jpg')" class="" />
        </div>           
        
        <div class="bg-white relative mx-6" style="min-width: 400px;">
          <img :src="require('@/assets/images/portfolio/logo design/IMG_20191029_194327_299.jpg')" class="" />
        </div>           
        
        <div class="bg-white relative mx-6" style="min-width: 400px;">
          <img :src="require('@/assets/images/portfolio/logo design/IMG_20191029_194327_299.jpg')" class="" />
        </div>   
      </VueSlickCarousel>
    </div>

    <div class="mt-20 ">
      <h1 class="text-4xl font-bold text-white flex justify-center mx-auto lg:text-6xl">Flyer design</h1>
      <VueSlickCarousel :rtl="true" :autoplay="true" :cssEase="ease" :pauseOnHover="true" :variableWidth="true" :arrows="false" :dots="false" :adaptiveHeight="true" class="gap-4 mt-8 w-full ">

        <div class="bg-white relative mx-6" style="width: 400px;">
          <img :src="require('@/assets/images/portfolio/flyers/1st.jpg')" class="w-full" />
        </div>   

        <div class="bg-white relative mx-6" style="width: 400px;">
          <img :src="require('@/assets/images/portfolio/flyers/3.jpg')" class="w-full" />
        </div>        
        
        <div class="bg-white relative mx-6" style="width: 400px;">
          <img :src="require('@/assets/images/portfolio/flyers/Charmaine_SourceSmart_eflyerdesign_flatII_corrected_Upwork.jpg')" class="w-full" />
        </div>           
        
        <div class="bg-white relative mx-6" style="width: 400px;">
          <img :src="require('@/assets/images/portfolio/flyers/Ife2.jpg')" class="w-full" />
        </div>           
        
        <div class="bg-white relative mx-6" style="width: 400px;">
          <img :src="require('@/assets/images/portfolio/flyers/Raboni.jpg')" class="w-full" />
        </div>           
        
        <div class="bg-white relative mx-6" style="width: 400px;">
          <img :src="require('@/assets/images/portfolio/flyers/WA_September.jpg')" class="w-full" />
        </div>   
      </VueSlickCarousel>
    </div>

  </div>
</template>

<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
export default {
  name: 'MyComponent',
  components: { VueSlickCarousel },
}
</script>

<style>

</style>