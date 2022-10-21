<template>
  <div id="app">
    <Header />
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>
<script>
import Header from "@/components/Header.vue";

export default {
  components: {
    Header
  }
};
</script>

<style>

body {
  
  
  background-image: linear-gradient(to right, #e3f8f5 , #f3f7f6);

}
.container {
  max-width: 900px;
}
.card {
  /* background-image: linear-gradient(to right, #1675ac , #218377); */
  background-image: linear-gradient(to right, #1675ac , #36d6c3);
}
.card-body {
  color: #f9ffee;
}
.card-body a {
  color: #efbb35;
}
</style>
