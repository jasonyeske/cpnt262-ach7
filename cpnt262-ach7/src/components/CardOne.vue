<template>
    <div>

<CardContent :content="cardText" :img="cardImage" />





    </div>
</template>

<script setup>


import CardContent from "./CardContent.vue"
const cardText = {

title: "Card 1",
preview: "An image of someone in the rain",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1607708121955-e44b3dce5067?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=678&q=80"

}


</script>