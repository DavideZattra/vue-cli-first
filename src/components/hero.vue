<template>
  <div id="ms_jumbotron">
    
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptatibus odio nemo ea officiis temporibus sequi, molestiae hic quas eos voluptatum quibusdam fuga fugit illo repellat tempora aliquid molestias nulla alias!</p>
    <button>Lorem ipsum</button>
  </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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

button{

    border-radius: 10px;
    font-weight: 600;
    font-size: 1rem;
    color: white;
    background-color: grey;
    
}

#ms_jumbotron{
    margin: 0 auto;
    width: 600px;
}


</style>