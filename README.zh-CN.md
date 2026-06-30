# 学术新人自救工具箱

[English](README.md) | 中文

一个不断成长的小网站，写给刚入学的博士新生：汇总会议截止日期追踪网站和会议官网资源，帮你不再错过投稿窗口。

**在线访问：** 通过 GitHub Pages 发布，中文版见 [zh.html](https://alexli-77.github.io/academic-survival-kit/zh.html)，英文版见首页。

## 内容

- **会议截止日期追踪** —— 汇总多个会议投稿截止日期的网站（SE Deadlines、ML Deadlines、AI Deadlines、CSConf、WikiCFP、PLSE Deadlines、AI/ML Conference Tracker、Bibby Conference Deadlines）。
- **会议官网与CMS** —— 等你确定了目标会议名字之后，真正去查注册、日程、场地的地方（conf.researchr.org、DBLP、OpenReview）。

后续会陆续加入更多分类（写作工具、经费与差旅资助、自媒体与影响力）。

## 本地开发

这是一个纯静态的单文件 `index.html`（英文版）/ `zh.html`（中文版），内联了 CSS/JS，不需要构建步骤。直接用浏览器打开，或者本地起个服务：

```bash
python3 -m http.server 8000
```

## 协议

MIT
