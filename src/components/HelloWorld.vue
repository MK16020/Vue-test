<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
          <v-card class="mx-auto" max-width="400px">
            <v-img src="" alt=""></v-img>
            <v-card-text down >hello</v-card-text>
          </v-card>
     
  
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only
#f66e0f blue
#00a3e4 orange
 -->
<style scoped>
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;

}
</style>


