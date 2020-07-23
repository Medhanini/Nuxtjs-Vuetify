<template>
  <v-layout>
    <v-flex class="text-center">
<v-sheet    v-if="!users" >
      <v-skeleton-loader  color="red" style="height:500px" class="mx-auto" type="image" >
       
      </v-skeleton-loader>
    </v-sheet>
      <blockquote class="blockquote">
        &#8220;simple test of vuetify component ( v-skeleton-loader ).&#8221;
        <footer>
          <small>
            <em>&mdash;Mohamed Hanini</em>
          </small>
        </footer>
      </blockquote>
    </v-flex>
  </v-layout>
</template>
<script>
export default {
    data(){
        return{
           // users : true
        }
    }
}
</script>
