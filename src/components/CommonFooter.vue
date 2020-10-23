<template>
  <footer id="footer">
    <small>Copyright 2019 estra inc. All Rights Reserved</small>
    <div class="flex between">
      <p class="footer-logo">estra inc.</p>
      <nav class="footer-nav">
        <ul>
          <li><a href="#">home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">service</a></li>
          <li><a href="#">works</a></li>
          <li><a href="#">price</a></li>
        </ul>
    </nav>
    </div>
  </footer>
</template>

<style scoped>
/* footer */

#footer {
  width: 100%;
  height: 100px;
  background-color: #000;
  position: relative;
}

.footer-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #f2f2f2;
  line-height: 80px;
}


.footer-nav li {
  display: inline-block;
  margin-right: 35px;
  font-size: 16px;
  list-style-type: none;
  padding: 0;
}


.footer-nav a {
  color: #f2f2f2;
  text-decoration: none;
  padding: 0;
  font-weight: lighter;
}

small {
  color: #fff;
  font-weight: lighter;
  font-size: 12px;
  position: absolute;
  transform: translate(-50%, -50%);
  left: 50%;
  bottom: 0;
}
</style>