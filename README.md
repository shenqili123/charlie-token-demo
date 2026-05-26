# 查理 Token H5 Demo

这是“查理 Token / AI Learning Gear”的纯静态 H5 demo。页面模拟实体 NFC Token 被扫描后的体验：识别 Token、启动 AI Agent、完成方法训练、点亮能力徽章，并生成成长罗盘。

## 本地预览

直接用浏览器打开 `index.html` 即可。四个入口可以用 URL 参数模拟：

- `index.html?token=math`
- `index.html?token=chinese`
- `index.html?token=english`
- `index.html?token=energy`

## 部署

这是无构建静态站点，可以直接部署到 Vercel、Netlify、Cloudflare Pages 或 GitHub Pages。

部署目录选择当前文件夹即可，构建命令留空，发布目录设为项目根目录。

## NFC 写入 URL

部署后可以把四个公网地址写入不同实体 Token：

- `https://your-domain.example/?token=math`
- `https://your-domain.example/?token=chinese`
- `https://your-domain.example/?token=english`
- `https://your-domain.example/?token=energy`

