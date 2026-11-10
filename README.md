# aisummoner.com — 产品站

## 里面是什么

- `index.html`：首页（橱窗式）：品牌 + 橱窗（两样：Atlas 地图 / 地图的故事文章）。暖纸底 + 赤陶橙红 accent，与地图故事同色系。**SAT 单词卡已隐藏（2026-11-10）：产品未上线，橱窗/导航/llms.txt 里都不出现；等 Fable 下单页（11/16）做好再放回。**
- `atlas.html`：AI Learning Atlas（24 周学习地图），源文件 `atlas-v3-masterpiece.html`（batch 12，274,818 字节），只改了两处：JSON-LD 里的 provider URL 从 `https://conjurerlab.com/atlas` 改成 `https://aisummoner.com`；顶栏加了回网站首页指针 `← aisummoner.com`（与 `← conjurerlab.com` 并列）。回主站链接仍指 conjurerlab.com（思想站），不动。字体走 Google Fonts CDN，favicon 已内嵌，无本地依赖。URL：aisummoner.com/atlas。
- `atlas-story.html`：地图的故事文章《午夜硅基小馆：一家只在深夜营业的小馆，店员是个 AI》（源文件 `your_files/atlas-intro-article.md`，逐字转 HTML，文末地图链接已改成 aisummoner.com/atlas）。URL：aisummoner.com/atlas-story。
- `favicon.svg`：B2 灯笼 + 硅基底。
- `llms.txt` / `sitemap.xml` / `robots.txt`：agent 友好三件套（search=yes / ai-input=yes / ai-train=no），与 conjurerlab.com 同标准。
- `order.html`：待 Fable 建（单词卡下单页，窗口到 11/16）；下单页做好后，单词卡重新放回橱窗/导航/llms.txt。

## 定位（铁律）

- Atlas 是给想学 AI 的**成年人**的 6 个月 AI 工程学习地图，**不是给孩子的**；地图里**没有猫**（猫只在单词卡藏猫游戏里）。
- 单词卡是给孩子的定制礼物，$9.99 试营业。

## 上线（已上线 2026-11-10 11:11）

- GitHub：JoyceWay/AISummoner（她建的）。
- Cloudflare（Puchiing 账号）Pages 项目 aisummoner，连库自动部署；域名 aisummoner.com 已挂。
- 验 live：首页 200、274,818 字节的 Atlas 在 /atlas、/atlas-story、llms.txt / sitemap.xml / robots.txt / favicon.svg 均 200。
- Atlas 以后只改这个库。conjurerlab.com/atlas 已删（404）。
