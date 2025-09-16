<template>
  <div class="container">
    <header>
      <h1>钟馗 Wiki</h1>
      <p class="subtitle">中国神话 · 钟馗主题开源知识站</p>
    </header>
    <main>
      <section class="intro">
        <h2>项目简介</h2>
        <p>
          钟馗，中华神话中的著名神祇，以驱邪镇宅著称。本项目致力于收集、整理与传播钟馗相关的神话、传说、艺术与文化资料，打造开放、现代、易用的钟馗主题知识网站。
        </p>
      </section>
      <section class="links">
        <a href="https://github.com/zhenxinfrozen/zhongkui-wiki" target="_blank">GitHub 项目地址</a>
        <a href="https://rzx.me" target="_blank">开发者：颓废动画人</a>
      </section>
    </main>
    <footer>
      <span>© 2025 钟馗 Wiki · 颓废动画人</span>
    </footer>
  </div>
</template>

<script setup>
// 预留后续扩展
</script>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  background: #f7f7fa;
  color: #222;
  font-family: 'Segoe UI', 'PingFang SC', 'Hiragino Sans GB', 'Microsoft YaHei', Arial, sans-serif;
}
header {
  padding: 2rem 0 1rem 0;
  text-align: center;
  background: #fff;
  box-shadow: 0 2px 8px #eee;
}
.subtitle {
  color: #888;
  font-size: 1.1rem;
  margin-top: 0.5rem;
}
main {
  flex: 1;
  padding: 2rem 1rem 1rem 1rem;
  max-width: 700px;
  margin: 0 auto;
}
.intro {
  margin-bottom: 2rem;
}
.links {
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  margin-top: 1rem;
}
.links a {
  color: #2d5af1;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s;
}
.links a:hover {
  color: #e94f4a;
}
footer {
  text-align: center;
  padding: 1rem 0;
  background: #fff;
  color: #aaa;
  font-size: 0.95rem;
  border-top: 1px solid #eee;
}
</style>

