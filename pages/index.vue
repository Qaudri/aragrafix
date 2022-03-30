<template>
  <body>
    <section class="h-screen container mx-auto flex items-center justify-center">
      <div class="flex">
        <div class="w-1/2 relative">
          <h1 class="font-black text-7xl text-gray-500">Hello</h1>
          <img :src=" require('@/assets/images/ope.png') " alt="">
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
