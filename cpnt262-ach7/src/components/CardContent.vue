<template>
    <div class="border-2 border-black flex flex-col justify-center items-center">

<h1 class="text-3xl">{{ props.content.title }}</h1>
<img class="w-72" :src="props.img.url" />
<p>{{props.content.preview}}</p>
<button class="bg-gray-300  ">
   Enter Page
</button>
    </div>
</template>

<script setup>

import { defineProps } from 'vue';
const props = defineProps({
   content: {
      type: Object,
   
   } ,
   img:{
       type: Object,
   },

});

</script>


