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


button{

  padding: 5px 5px;
  border-radius: 10px;
  font-weight: 600;
  font-size: 1.5rem;
  color: white;
  background-color: grey;
    
}

#ms_jumbotron{

  width: 600px;
  margin: 0 auto;
  padding: 20px 40px;
  color: white;
  font-size: 1.3rem;
  background-color: rgb(204, 204, 204);

}


</style>