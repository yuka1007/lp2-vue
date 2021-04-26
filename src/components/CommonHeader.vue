<template>
  <header class="header">
    <div class="header-wrap">
       <h1 class="header-logo">estra inc.</h1>
       <nav class="header-nav">
        <ul>
          <li><a href="#">home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">service</a></li>
          <li><a href="#">works</a></li>
          <li><a href="#">price</a></li>
          <li><a href="#">contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style scoped>
#hamburger {
  display: none;
}

#top-header {
  height: 70px;
  line-height: 70px;
  background: rgba(0, 0, 0, 1);
}

.header-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #fff;
  line-height: 70px;
}

.header-nav li {
  display: inline-block;
  margin-right: 35px;
  font-size: 16px;
}

.header-nav a {
  color: #fff;
}

#firstview {
  height: 100%;
  background: url(../img/eyecatch.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}

.catchcopy {
  position: absolute;
  top: 60%;
  left: 10%;
  font-size: 60px;
  font-style: italic;
  font-weight: bold;
  color: #fff;
  line-height: 1;
}

</style>
