<script> 
export default {
  name:'header'
}
</script>

<template>
<header>
    <div class="container d-flex justify-content-beetween align-center h-100">
      <nav class="main-menu">
        <ul class="d-flex">
          <li><a href="#">uomo</a></li>
          <li><a href="#">donna</a></li>
          <li><a href="#">bambino</a></li>
        </ul>
      </nav>

      <div class="box-logo">
        <div class="logo">
          <img src="img/boolean-logo.png" alt="Logo Boolean">
        </div>
      </div>
      
      <nav class="social-menu">
        <ul class="d-flex">
          <li><a href="#"><i class="fa-regular fa-user"></i></a></li>
          <li><a href="#"><i class="fa-regular fa-heart"></i></a></li>
          <li><a href="#"><i class="fa-solid fa-bag-shopping"></i></a></li>
        </ul>
      </nav>
    </div>
   </header>
</template>

<style lang="scss" scoped>
header{
  position: fixed;
  left: 0;
  right: 0; 
  background-color: #FA6903;
  height: 80px;
  color: white;
  box-shadow: 0 1px 3px grey;
  z-index: 999;
}

header .container{
  padding: 0 10px;
}

header nav ul{
  list-style: none;
}

header nav ul a{
  color: white;
  text-decoration: none;
  font-weight: bold;
  text-transform: capitalize;
}

header nav ul a:hover{
  text-decoration: underline;
}

header nav.main-menu  a{
  padding-right: 20px;
}

header nav{
  width: 30%;
}

header nav.social-menu ul{
  justify-content: flex-end;
}

header nav.social-menu  a{
  padding-left: 5px;
}

header .logo{
  width: 165px;
}
</style>
