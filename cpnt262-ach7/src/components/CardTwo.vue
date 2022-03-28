<template>
    <div>

<CardContent :content="cardTitle" :img="cardImage" />





    </div>
</template>

<script setup>


import CardContent from "./CardContent.vue"
const cardTitle = {

title: "Card 2",
preview: "Someone out in the wild",
}
const cardImage = {

url: "https://images.unsplash.com/photo-1646936218677-46019fc4a153?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"

}

</script>