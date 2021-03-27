<template>
  <div>
  <div class="hello">
    <h1>{{msg}}</h1>
    <h2>Knox College class of 2023. He/him/his</h2>
    <h3>Computer Science Major</h3>
    
  </div>
  <div id="pdfv">
    <pdf src="./static/test.pdf"></pdf>
  </div>
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

<script>
import pdf from 'vue-pdf'

export default {
  components: {
    pdf
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 0px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 0px;
}
.hello {
  padding: 0px;
}
.pdfv{
  background-color: paleturquoise;
  
  }

</style>