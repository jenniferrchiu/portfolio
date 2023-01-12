<template>
  <div class="box">
    <div id="sticky">
      <Header/>
    </div>
    <div style ="flex: 0 0 400px; margin-top:10px">
      <Home/>
    </div>
  </div>
</template>

<style>
  body {
    margin-top: 100px;
    margin-bottom: 100px;
    margin-left: 300px;
    margin-right: 300px;
  }
  .box {
    display:flex;
    column-gap:5em;
  }

  #sticky {
    position: sticky;
    top: 0;
    align-self: flex-start; /* <-- this is the fix */
  }
</style>

<script>
export default {
  name: 'IndexPage'
}
</script>
