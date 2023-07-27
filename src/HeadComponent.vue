<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://i.pinimg.com/564x/eb/aa/59/ebaa5967f9fc5fb780d9e835bf691b97.jpg',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://i.pinimg.com/564x/0d/4f/bb/0d4fbbace6f32890442e4c984f1905eb.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': 'https://i.pinimg.com/564x/b2/fa/30/b2fa30ddaa40c9150f8d50de3f4593e2.jpg',
    'alt': 'Picture 3',
  },
  {
    'src': 'https://i.pinimg.com/564x/b6/75/38/b67538023dcecba057369f4cde7c17d8.jpg',
    'alt': 'Picture 4',
  },
  {
    'src': 'https://i.pinimg.com/564x/4f/d0/ce/4fd0ceb0db65a5fb21c45149bf657fe4.jpg',
    'alt': 'Picture 5',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
<section class="bg-white dark:bg-gray-900">
    <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16">
        <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white">Hewan Sehat Anda Ceria</h1>
        <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-48 dark:text-gray-400">Tak Kenal Hewan Maka Tak Akan Sayang Hewan nya.</p>
       
    </div>
</section>

</template>
