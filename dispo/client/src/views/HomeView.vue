
<template>
  <div class="container_all">
    <Header></Header>

    <div class="main">
      <MainFirst></MainFirst>
      <MainSecond>
      </MainSecond>
    </div>
    <Footer></Footer>

  </div>
</template>
<script>
import Header from '@/components/Header.vue';
import MainFirst from '@/components/MainFirst.vue';
import MainSecond from '@/components/MainSecond.vue';
import Footer from '@/components/Footer.vue';
export default {
  components: {
    Header,
    MainFirst,
    MainSecond,
    Footer
}
}
</script>
<style scoped>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.container_all{
  height: 100vh;
  width: 100%;
  background-color: #EFF3F6;
}
.main{
  width: 84%;
  margin: auto;
  height: 610px;
  background-color: #ffffff;
  border-radius: 30px;
  display: flex;
  flex-direction: column;
  margin-top: 90px;
  justify-content: center;
}
</style>