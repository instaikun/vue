<template>
  <footer>
    <div class="footer">
      <div class="footer-logo">
       estra inc.
      </div>
      <nav class="footer-nav">
        <ul>
         <li>home</li>
         <li>about</li>
         <li>service</li>
         <li>works</li>
         <li>price</li>
         <li>contact</li>
        </ul>
      </nav>
      <div class="small">
       <small>Copyright 2019 estra inc. All Rights Reserved.</small>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  background-color: black;
  color: white;
  height: 50px;
  width: 100%;
  position: relative;
}

.footer {
  display: flex;
}

.footer-logo {
  margin-left: 10px;
  font-weight: bold;
}

.footer-nav {
  margin: 0 0 0 auto;
}

.footer-nav ul {
  display: flex;
}

.footer-nav li {
  margin-left: 15px;
  cursor: pointer;
}

.small {
  font-size: 8px;
  text-align: center;
  position: absolute;
  top: 100%;
  left: 50%;
  transform: translate(-50%, -100%);
}
@media screen and (max-width:768px){
  .footer-logo{
    margin: 0 auto;
  }

  .footer-nav{
    display: none;
  }
}
</style>