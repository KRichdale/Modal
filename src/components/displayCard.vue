<template>
   <v-card
    class="mx-auto"
    max-width="344"
    outlined
  >
    <v-list-item three-line>
      <v-list-item-content>
        <div class="overline mb-4">"Go clean is the best"</div>
        <v-list-item-title class="headline mb-1">{{ title }}</v-list-item-title>
        <v-list-item-subtitle>Give them money!</v-list-item-subtitle>
      </v-list-item-content>

      <v-list-item-avatar
        
        size="70"
        
      ><img :src="require(`../assets/${Img}.png`)"></v-list-item-avatar>
    </v-list-item>

    <v-card-actions>
<vForm />
    </v-card-actions>
  </v-card>
</template>

<script>
import vForm from "./vForm.vue"
export default {
    name: "displayCard",
    props: {
        title: String,
        Img: String
    },components:{
      vForm
    }
}
</script>

<style>

</style>