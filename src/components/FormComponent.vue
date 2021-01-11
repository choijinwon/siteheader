<template>
  <div class="search-form">
    <input type="text" v-model="inputValue" placeholder="검색어를 입력하세요">
    <button type="reset">x</button>
  </div>
</template>

<script>
export default {
 template:'Sechar',
 props: {
  value: String,
},

 methods: {
    
 },

}
</script>

<style>
 @import '../src/assets/style/style.css';
</style>