<template>
  <div class="cont">
    <h1>안ㄴ여하세요</h1>
    <hr />
    <card-ui />
    <card-ui />
    <card-ui />
    <card-ui />
    <card-ui />
    <card-ui />
  </div>
</template>

<script>
// define -> 정의
import CardUi from './components/card-ui.vue'
  // 등록
export default {
  components: {
    CardUi,
}
}
</script>

<style>
  .cont{
    width: 500px;
    height: 500px;
    background-color: lightgray;
  }
  div{
    text-align: center;
}
</style>
