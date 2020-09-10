<template>
  <div class="hello">
    
    <b-card
    title="String Conversion"
    class="mb-2 text-center"
  >
    <input type="text" v-model="str" v-uppercase>
    <p >{{str}}</p>
    </b-card>

</div>
</template>

<script>
export default {
  name: 'HelloWord',
  data(){
    return{
      str:''
    }
  },
  directives:{
  uppercase:{
    update(el){
    el.value = el.value.toUpperCase();
  },
  }

}

}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
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
