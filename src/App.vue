<script>
export default {
  data() {
    return
  }
}
</script>

<template>
  <body>
    <div class="helloWorld">
      Hello World!
    </div>
    <div class="hint">
      <p>Posiziona il cursore sopra il titolo!</p>
    </div>
  </body>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:wght@300;400;700&display=swap');

* {
  font-family: 'Noto Sans', sans-serif;
  color: white;
}

.helloWorld {
  font-weight: bold;
  font-size: 3rem;
  text-align: center;
  margin: 30px 0;
  text-shadow: 2px 2px 2px black;
  transition: all 0.5s ease-in-out;
}

.helloWorld:hover {
  color: red;
}

.hint {
  text-align: center;
}

</style>
