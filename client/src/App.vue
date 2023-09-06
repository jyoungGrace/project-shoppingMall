<script setup>
  import CommonHeader from "@/components/common/CommonHeader.vue";
  
</script>

<template>
  <!-- header -->
  <CommonHeader/>
  <!-- // header -->


  <!-- 컨텐츠 시작 -->
  <section>
     <RouterView />
  </section>
  <!-- // 컨텐츠 시작 -->


</template>


<script>
  export default {
    name: 'App'
  }
</script>

<style scoped>

</style>