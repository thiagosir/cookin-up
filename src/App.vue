<script lang="ts">
import Banner from './components/Banner.vue';
import Rodape from './components/Rodape.vue';
import BotaoPrincipal from './components/BotaoPrincipal.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';

export default {
  components: { Banner, ConteudoPrincipal, Rodape, BotaoPrincipal }
}
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
  <Rodape />
</template>

<style scoped>

</style>
