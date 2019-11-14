<template>
  <div class="about">
<displayCard title="Sophia" Img="1"/>
<displayCard title="Mum" Img="2"/>
<displayCard title="Dad" Img="3"/>



  </div>
</template>

<script>
import displayCard from "../components/displayCard.vue"
export default {
  name: "about",
  components:{
    displayCard
  }
}
</script>