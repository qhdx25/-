<template>
  <div class="home">
    <h1>南开大学数学建模协会</h1>
    <p class="intro">
      我们致力于推广数学建模文化，举办各类赛事与培训活动，
      帮助同学们提升建模能力与科研思维，欢迎加入我们！
    </p>
    <div class="nav-links">
      <router-link to="/about">关于我们</router-link>
      <router-link to="/resources">学习资源</router-link>
    </div>
  </div>
</template>

<style scoped>
.home {
  text-align: center;
  padding: 4rem 2rem;
  min-height: 100vh;
  background-color: #242424;
  color: #fff;
}
h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}
.intro {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  opacity: 0.9;
}
.nav-links a {
  margin: 0 1rem;
  padding: 0.6rem 1.2rem;
  background: #42b983;
  color: white;
  text-decoration: none;
  border-radius: 4px;
}
</style>