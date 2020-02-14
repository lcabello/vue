<template>
  <div class="container">
    <Header></Header>
    <hr>
    <List></List>
    <hr>
    <Footer></Footer>
  </div>
</template>

<script>
  import Header from './Header';
  import List from './List';
  import Footer from './Footer';

  export default {
    components: {
      Header,
      List,
      Footer
    }
  }
</script>

<style></style>
