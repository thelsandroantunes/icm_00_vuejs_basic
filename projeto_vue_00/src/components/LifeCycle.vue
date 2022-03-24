<template>
  <h1> Meu nome é: {{nome}}</h1>
</template>

<script>
export default{
  name:'LifeCycle',
  data(){
    return {
      nome: 'Ainda não sei'
    }
  },
  created(){
    setTimeout(() => {
      this.nome = "Thelsandro"
    }, 1000)

  },
  mounted(){
    setTimeout(()=>{
      this.nome = "Thayná"
    }, 2000)

  }
}
</script>
