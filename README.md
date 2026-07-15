# 小子博客 Hexo 迁移说明

## 安装

需要 Node.js 18+

```bash
npm install -g hexo-cli
```

## 初始化

```bash
hexo init blog
cd blog
npm install
```

## 安装推荐插件

```bash
npm install hexo-generator-searchdb
npm install hexo-generator-sitemap
npm install hexo-generator-feed
```

## Cloudflare Pages

Build command:

```bash
npm install && hexo generate
```

Build output directory:

```text
public
```

## 推荐主题方向

保留当前暖珊瑚橙风格：

- 主色：#df846c
- 背景：#fafafa
- 字体颜色：#333

建议制作自定义主题 `xiaozi-theme`
