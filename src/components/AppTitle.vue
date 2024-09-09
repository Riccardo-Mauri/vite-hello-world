<script>
export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    }
  },
  
}
</script>

<template>
  <div>
    <header>
      <h1>
        {{ message }}
      </h1>

    </header>
  </div>
</template>

<style scoped>
header{
  background-color: aquamarine;
  text-align: center;
  padding: 25px 0;
}
h1{
  color: lightcoral;
}
</style>
