# Harei Learning

这是一个用 GitHub Pages 搭建的中文学习资源导航网站。

## 页面

- `index.html`：主页，包含计算机科学、数学、音乐资源链接
- `books.html`：书单页面
- `style.css`：网站样式

## 网站地址

部署后网站地址应为：

https://hanshouniao.github.io/harei-learning/

## 如何更新

1. 在 GitHub 仓库中打开要修改的文件，例如 `index.html`。
2. 点击右上角铅笔图标编辑。
3. 修改文字或链接。
4. 点击 `Commit changes` 保存。
5. 等待 GitHub Pages 自动更新。

## 如何新增一个链接卡片

在 `index.html` 中复制类似这一段：

```html
<a class="resource-card" href="https://example.com" target="_blank" rel="noopener noreferrer">
  <span class="tag">分类标签</span>
  <h3>资源标题</h3>
  <p>资源说明。</p>
</a>
```

然后修改：
- `href` 里的网址
- `tag` 里的标签
- `h3` 里的标题
- `p` 里的说明
