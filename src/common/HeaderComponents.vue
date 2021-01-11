<template>
    <div>
        <nav class="navbar">
            <div class="navbar__logo">
                <i class="fab fa-accusoft"></i>
                <a href="">SiteDream</a>
            </div>
            <ul class="navbar__menu " >
              <li><a href="">홈</a></li>
              <li><a href="">갤러리</a></li>
              <li><a href="">프로젝트</a></li>
              <li><a href="">공지사항</a></li>
              <li><a href="">문의사항</a></li>
            </ul>
            <ul class="navbar__icons">
                <li><i class="fab fa-twitter"></i></li>
                <li><i class="fab fa-facebook-f"></i></li>
            </ul>
            <a  class="navbar__toggleBtn" v-on:click="toggleShow" >
                <i class="fas fa-bars" ></i>
            </a>
        </nav>
    </div>
</template>

<script>

export default {
    data() {
        return {
            actvice:true,
            toggleBtn:""
        }
    },
      mounted() {
        const toogleBtn = document.querySelector(".navbar__toggleBtn");
        const menu = document.querySelector(".navbar__menu");
        const icons = document.querySelector(".navbar__icons");
            toogleBtn.addEventListener('click',() =>{
            menu.classList.toggle('active')
            icons.classList.toggle('active')
            });
    },
    methods: {
       toggleShow:function () {
      }
    },
}
</script>

<style>
</style>