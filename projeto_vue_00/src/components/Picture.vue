<template>
<div>
  <img :src="avatar" :alt="descricao">
  <MudarImagem @mudar-imagem="mudarImagem" />
</div>
</template>

<script>
import MudarImagem from './MudarImagem.vue'
export default {
  components: { MudarImagem },
  data() {
    return {
      avatar: "/img/avatar.png",
      descricao: "Ucrânia"

    }
  },
  methods: {
    mudarImagem() {
      this.avatar = "/img/avatar2.png"
    }
  }
}
</script>
