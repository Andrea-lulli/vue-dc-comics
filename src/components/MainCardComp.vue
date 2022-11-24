<template>
  <div class="card-fumetti">
    <img :src="Prodotti.thumb" />
    <p>{{ Prodotti.series }}</p>
  </div>
</template>

<script>
export default {
  name: "MainCardComp",
  props: {
    Prodotti: Object,
  },
};
</script>

<style lang="scss" scoped>
.card-fumetti {
  flex-basis: 15%;
  margin: 20px 0;
  color: white;
  text-align: center;
}

div {
  img {
    width: 100%;
  }
}
</style>