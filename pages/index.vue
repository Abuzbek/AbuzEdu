<template>
  <div class="container">
    <div class="overlay">
      <br>
    </div>
    <h1>
      Welcome to AbuzEducation
    </h1>
  </div>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style>
  .container{
    background:url('https://www.itl.cat/pngfile/big/291-2919409_developer-wallpaper.png') no-repeat center center  / cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
  }
  .container h1{
    font-size: 50px;
    color: white;
    font-family: sans-serif;
    position: relative;
  }
  .container .overlay{
    position: absolute;
    width: 100%;
    height: 100%;
    backdrop-filter: blur(5px);
    background: rgba(0, 0, 0, 0.5);
  }
</style>
