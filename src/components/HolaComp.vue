<template>
  <div id="container">
    <strong>Bienvenido a Book Break</strong>
    <p>Empecemos</p>
  </div>
</template>

<script lang="ts">

export default {
  name: 'Hola',
  props: {
    name: String
  }
}
</script>

<style scoped>
#container {
  text-align: center;
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 30px;
  line-height: 26px;
  color: #ffffff;
}

#container p {
  font-size: 26px;
  line-height: 22px;
  color: #ffffff;
  margin: 0;
}

</style>