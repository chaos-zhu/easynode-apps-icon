<template>
  <div class="container">
    <div class="card">
      <h2>新增 icon 说明</h2>

      <p>📝 新增 icon 请提交 PR，PR 通过后会自动部署。</p>

      <p>🎨 注意：icon 背景必须 <strong>透明</strong> 且格式为 <strong>PNG</strong>。</p>

      <p>
        🔗 PR 提交仓库：
        <a href="https://github.com/chaos-zhu/easynode-apps-icon" target="_blank">
          https://github.com/chaos-zhu/easynode-apps-icon
        </a>
      </p>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: linear-gradient(135deg, #f7f8fa, #eef1f5);
  padding: 20px;
}

.card {
  max-width: 480px;
  text-align: center;
  background: white;
  padding: 32px 28px;
  border-radius: 16px;
  box-shadow: 0 8px 24px rgba(0,0,0,0.08);
  line-height: 1.8;
  color: #333;
}

h2 {
  margin-bottom: 16px;
  color: #222;
  font-size: 22px;
}

a {
  color: #007aff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
