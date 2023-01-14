<template>
  <div class="box">
    <div id="sticky" style="flex: 0 0 18vw">
      <Header/>
    </div>
    <div style ="flex: 0 0 30w; margin-top:1.5em;;">
      <Home/>
    </div>
  </div>
</template>

<style>
  body {
    margin-top: 20vh;
    margin-bottom:20vh;
    margin-left: 25vw;
    margin-right: 25vw;
  }
  .box {
    display:flex;
    column-gap:5em;
    margin-top:0px;
    padding-top:0px;
  }

  #sticky {
    position:-webkit-sticky;
    position: sticky;
    top: 0;
    align-self: flex-start;
  }
</style>

<script>
export default {
  name: 'IndexPage'
}
</script>
