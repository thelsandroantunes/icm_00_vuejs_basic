<template>
<div>
  <Header />
  <PrimeiroComponente />
  <LifeCycle />
  <Pessoa />
</div>
</template>

<script>
import Header from './components/Header'
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
import Pessoa from './components/Pessoa.vue'
export default{

  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle,
    Pessoa,
    Header
  }
}

</script>

<style>
  body {
    background-color: #333;
    color: #FFF;
  }
</style>
