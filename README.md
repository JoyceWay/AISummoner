# aisummoner.com — 部署包（Atlas 搬家）

## 里面是什么

- `index.html`：AI Learning Atlas（24 周学习地图），源文件 `atlas-v3-masterpiece.html`（batch 12，274,825 字节），只改了一处：JSON-LD 里的 provider URL 从 `https://conjurerlab.com/atlas` 改成 `https://aisummoner.com`。回主站链接仍指 conjurerlab.com（思想站），不动。字体走 Google Fonts CDN，favicon 已内嵌，无本地依赖。
- `favicon.svg`：B2 灯笼 + 硅基底。
- `llms.txt` / `sitemap.xml` / `robots.txt`：agent 友好三件套（search=yes / ai-input=yes / ai-train=no），与 conjurerlab.com 同标准。

## 怎么上线（她点的步骤）

1. **GitHub 建库：JoyceWay/AISummoner**（她建，Muse 的令牌建不了库）。建完告诉 Muse 一声。
2. Muse 把这个文件夹推到库里。
3. **Cloudflare（Puchiing 账号）建 Pages 项目**，连这个库，部署。
4. Pages 项目里**挂域名 aisummoner.com**。
5. Muse curl 验 live（首页 200、字节数对得上、Atlas 能打开）。

## 搬完之后（上线后再做，别提前）

- conjurerlab.com/atlas 要去掉（或跳到 aisummoner.com），不然两个地方都有 Atlas。
- Atlas 以后只改这个库，不改 conjurerlab.com 那个。
