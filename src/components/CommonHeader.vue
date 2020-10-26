<template>
  <header>
      <h3 class="header-logo">estra inc.</h3>
      <nav class="header-nav">
        <ul class="header-list">
          <li><a href="#">home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">service</a></li>
          <li><a href="#">works</a></li>
          <li><a href="#">price</a></li>
          <li><a href="#">contact</a></li>
        </ul>
      </nav>
      <div id="hamburger">
        <span></span>
        <span></span>
        <span></span>
      </div>
  </header>
</template>

<style scoped>
  header {
  width: 100%;
  height: 50px;
  background-color: black;
  display: flex;
  color: white;
  align-items: center;
 }

 .header-logo {
  margin-left: 20px;
 }

 .header-nav {
  margin: 0 10px 0 auto;
 }

 .header-list {
  display: flex;
  font-size: 12px;
  font-weight: bold;
 }

 .header-list li {
  margin-left: 15px;
  cursor: pointer;
  color: white;
 }

 @media screen and (max-width:768px){
  #hamburger{
    width:40px;
    height: 40px;
    position: absolute;
    cursor: pointer;
    z-index: 100;
    right: 20px;
    transition: 0.4s;
  }

  #hamburger span{
    position: absolute;
    left: 2px;
    display: block;
    width: 35px;
    height: 2px;
    background-color: #fff;
    transition: 0.8s;
  }

  #hamburger span:nth-of-type(1){
    top: 10px;
  }
  #hamburger span:nth-of-type(2){
    top: 20px;
  }#hamburger span:nth-of-type(3){
    top: 30px;
  }

  .header-nav{
    display: none;
  }
 }
</style>