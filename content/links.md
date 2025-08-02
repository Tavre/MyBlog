---
title: "友情链接"
date: 2025-01-01T00:00:00+08:00
draft: false
hidemeta: true
showToc: false
TocOpen: false
showbreadcrumbs: false
---

### 友链列表

{{< rawhtml >}}
<div class="friends-container">
  <div class="friend-card">
    <div class="friend-info">
      <img src="https://q1.qlogo.cn/g?b=qq&nk=2726730791&s=640" alt="Tavre Blog" class="friend-avatar">
      <div class="friend-details">
        <h3 class="friend-name">AcoFork Blog</h3>
        <p class="friend-desc">分享网络技术、服务器部署、内网穿透、静态网站搭建、CDN优化、容器化部署等技术教程与实践经验的个人技术博客，专注于云原生、无服务器架构和前后端开发，作者为afoim/二叉树树</p>
        <a href="https://2x.nz" class="friend-link">访问网站</a>
      </div>
    </div>
  </div>
  
  <!-- 更多友链可以在这里添加 -->
  <!-- 
  <div class="friend-card">
    <div class="friend-info">
      <img src="头像链接" alt="网站名称" class="friend-avatar">
      <div class="friend-details">
        <h3 class="friend-name">网站名称</h3>
        <p class="friend-desc">网站描述</p>
        <a href="网站链接" class="friend-link">访问网站</a>
      </div>
    </div>
  </div>
  -->
</div>

<style>
.friends-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 20px 0;
}

.friend-card {
  background: var(--entry);
  border-radius: 12px;
  padding: 20px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border: 1px solid var(--border);
}

.friend-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.15);
}

.friend-info {
  display: flex;
  align-items: flex-start;
  gap: 15px;
}

.friend-avatar {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
}

.friend-details {
  flex: 1;
}

.friend-name {
  margin: 0 0 8px 0;
  font-size: 1.2em;
  font-weight: 600;
  color: var(--primary);
}

.friend-desc {
  margin: 0 0 12px 0;
  color: var(--secondary);
  font-size: 0.9em;
  line-height: 1.4;
}

.friend-link {
  display: inline-block;
  padding: 6px 12px;
  background: var(--theme);
  color: var(--primary);
  text-decoration: none;
  border-radius: 6px;
  font-size: 0.85em;
  transition: background 0.3s ease;
  border: 1px solid var(--border);
}

.friend-link:hover {
  background: var(--tertiary);
}

/* 暗色主题适配 */
body.dark .friend-card {
  background: var(--entry);
}

body.dark .friend-link {
  background: var(--tertiary);
}

body.dark .friend-link:hover {
  background: var(--theme);
}
</style>
{{< /rawhtml >}}

---

## 申请友链

如果您希望与本站交换友情链接，请发送邮件到：**tavre@qq.com**

### 邮件格式
请在邮件中包含以下信息：
```
网站名称：您的网站名称
网站链接：https://your-website.com
网站描述：简短的网站介绍（50字以内）
网站头像：头像图片链接（可选）
联系方式：您的邮箱或其他联系方式
```
请在申请前将本站链接添加至您博客中的友链