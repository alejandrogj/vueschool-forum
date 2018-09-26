<template>
  <div class="col-full">
    <h1>Not found</h1>
    <p>Oops!
      <router-link :to='{name: "Home"}'>
        go home
      </router-link>
    </p>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  h1 {
    font-size: 100px;
  }
  p {
    font-size: 50px;
    font-weight: 100;
  }
  div {
    text-align: center;
  }
</style>


