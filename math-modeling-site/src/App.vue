<template>
  <div class="home-page">
    <!-- 顶部导航栏 -->
    <nav class="navbar">
      <div class="nav-container">
        <div class="logo">南开大学数学建模协会</div>
        <ul class="nav-links">
          <li><a href="#about">关于我们</a></li>
          <li><a href="#resources">学习资源</a></li>
          <li><a href="#events">赛事活动</a></li>
          <li><a href="#join">加入我们</a></li>
        </ul>
      </div>
    </nav>

    <!-- 主视觉区域 -->
    <section class="hero">
      <div class="hero-content">
        <h1>南开大学数学建模协会</h1>
        <p>我们致力于推广数学建模文化，举办各类赛事与培训活动，帮助同学们提升建模能力与科研思维，欢迎加入我们！</p>
        <div class="hero-buttons">
          <a href="#about" class="btn btn-primary">关于我们</a>
          <a href="#resources" class="btn btn-secondary">学习资源</a>
        </div>
      </div>
    </section>

    <!-- 底部信息 -->
    <footer class="footer">
      <div class="footer-container">
        <p>&copy; 2025 南开大学数学建模协会 | All Rights Reserved</p>
      </div>
    </footer>
  </div>
</template>

<script setup>
// 这里可以添加后续交互逻辑
</script>

<style scoped>
/* 全局样式重置 */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.home-page {
  font-family: "Microsoft YaHei", sans-serif;
  color: #333;
}

/* 导航栏样式 */
.navbar {
  background-color: #2c3e50;
  padding: 1rem 0;
}
.nav-container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 2rem;
}
.logo {
  color: white;
  font-size: 1.5rem;
  font-weight: bold;
}
.nav-links {
  display: flex;
  list-style: none;
  gap: 2rem;
}
.nav-links a {
  color: white;
  text-decoration: none;
  transition: color 0.3s;
}
.nav-links a:hover {
  color: #27ae60;
}

/* 主视觉区域 */
.hero {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  min-height: calc(100vh - 80px - 60px);
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
  padding: 2rem;
}
.hero-content h1 {
  font-size: 2.8rem;
  margin-bottom: 1.5rem;
}
.hero-content p {
  font-size: 1.2rem;
  max-width: 800px;
  margin: 0 auto 2rem;
  line-height: 1.6;
}
.hero-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
}
.btn {
  padding: 0.8rem 2rem;
  border-radius: 5px;
  text-decoration: none;
  font-weight: 500;
  transition: background-color 0.3s;
}
.btn-primary {
  background-color: #27ae60;
  color: white;
}
.btn-primary:hover {
  background-color: #219653;
}
.btn-secondary {
  background-color: transparent;
  color: white;
  border: 2px solid white;
}
.btn-secondary:hover {
  background-color: rgba(255, 255, 255, 0.1);
}

/* 底部样式 */
.footer {
  background-color: #2c3e50;
  color: white;
  text-align: center;
  padding: 1.5rem 0;
}
.footer-container {
  max-width: 1200px;
  margin: 0 auto;
}
</style>
