# 快速参考指南

> **主要配置文件：`_data/site-content.yml`**

## 一分钟修改指南

### 🌐 网站基本信息

```yaml
site_info:
  title: "您的网站标题"
  description: "您的网站描述"
  header_text: "欢迎"
```

### 👤 关于页面

```yaml
about:
  content: |
    ## 您的标题
    您的内容（支持 Markdown）
```

### 📁 导航菜单

```yaml
navigation:
  - title: "页面名称"
    url: "/页面路径/"
    icon: "fa-图标名称"
    position: 1
```

### 🔗 社交链接

```yaml
social:
  github:
    username: "your-username"
    enabled: true
```

### 🎨 主题设置

```yaml
theme:
  color_theme: "auto"  # auto/dark/light
```

## 常用图标

| 图标 | 代码 |
|------|------|
| 首页 | `fa-home` |
| 用户 | `fa-user` |
| 作品集 | `fa-briefcase` |
| 图库 | `fa-images` |
| 分类 | `fa-folder` |
| 标签 | `fa-tags` |
| 搜索 | `fa-search` |
| 归档 | `fa-archive` |
| GitHub | `fa-github` |
| 邮箱 | `fa-envelope` |

## 文件位置

| 内容 | 位置 |
|------|------|
| 博客文章 | `_posts/` |
| 作品项目 | `_portfolio/` |
| 图片资源 | `assets/img/` |
| 主要配置 | `_data/site-content.yml` |

## 命令速查

```bash
# 本地预览
bundle exec jekyll serve

# 安装依赖
bundle install
```

---
详细说明请查看 [CONTENT-GUIDE.md](CONTENT-GUIDE.md)
