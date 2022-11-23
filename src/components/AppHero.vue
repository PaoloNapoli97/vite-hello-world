<script>
export default {
  data() {
    return {
      Jumbotron: 'Sono una Jumbotron pezzotta'
    }
  }
}
</script>

<template>
    <div class="container">
        <h1>{{ Jumbotron }}</h1>
    </div>
</template>

<style scoped>
    .container{
        display: flex;
        align-items: center;
        justify-content: center;
        margin: auto;
        width: 90%;
        background-color: red;
        height: 600px;
    }

    h1{
        font-size: 80px;
    }
</style>
