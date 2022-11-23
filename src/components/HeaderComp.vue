<template>
  <header class="">
    <div class="conteiner">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="logo" />
      </div>
      <nav >
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Comics</li>
          <li>Comics</li>
          <li>Comics</li>
          <li>Co</li>
          <li>Comics</li>
          <li>Comics</li>
          <li>Comics</li>
          <li>Comics</li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
        name: "HeaderComp"
    }
  
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 15px 0;
  background-color: white;
}

div img {
  width: 27%;
}

ul {
  display: flex;

  li {
    list-style-type: none;
    margin: 0 5px;
  }
}

.conteiner {
  width: 80%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.logo{
  flex-basis: 20%;
  justify-content: start;
  display: flex;
}
nav{
flex-basis: 80%;
 justify-content: end;
  display: flex;
}
</style>
