<template>
    <div>

<CardContent :content="cardText" :img="cardImage" />





    </div>
</template>

<script setup>


import CardContent from "./CardContent.vue"
const cardText = {

title: "Card 3",
preview: "An image of someone smoking a cigar at sunset",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1646330188637-6592be5b4f25?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"

}


</script>