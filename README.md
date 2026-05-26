# 查理 Token H5 Demo

"查理 Token / AI Learning Gear"的纯静态 H5 demo。页面模拟实体 NFC Token 被扫描后的完整体验流程：识别 Token → 启动 AI Agent → 完成方法训练 → 点亮能力徽章 → 生成成长罗盘。

## 在线体验

已部署至 Cloudflare，四个 Token 入口：

- [数学 Token](https://charlie-token-demo.shenqili123.workers.dev/?token=math)
- [语文 Token](https://charlie-token-demo.shenqili123.workers.dev/?token=chinese)
- [英语 Token](https://charlie-token-demo.shenqili123.workers.dev/?token=english)
- [能量 Token](https://charlie-token-demo.shenqili123.workers.dev/?token=energy)

## 本地预览

直接用浏览器打开 `index.html` 即可，或使用本地服务器：

```bash
python -m http.server 5173
```

然后访问 `http://localhost:5173/?token=math` 等地址。

## 部署

无构建静态站点，已通过 GitHub 连接 Cloudflare 自动部署。推送代码即自动更新：

```bash
git add .
git commit -m "描述修改内容"
git push
```

## NFC 写入 URL

将以下公网地址写入不同实体 Token：

- 数学 → `https://charlie-token-demo.shenqili123.workers.dev/?token=math`
- 语文 → `https://charlie-token-demo.shenqili123.workers.dev/?token=chinese`
- 英语 → `https://charlie-token-demo.shenqili123.workers.dev/?token=english`
- 能量 → `https://charlie-token-demo.shenqili123.workers.dev/?token=energy`
