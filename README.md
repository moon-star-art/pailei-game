# 牌垒 · PaiLei（网页版）

回合制策略攻防卡牌游戏。经营据点、调配手牌军队、侦察敌方动向，在攻与守之间读懂对手。

> 本仓库仅提供**可玩的发布版本**（不含源码）。

## 在线游玩（推荐）

- 官方链接：<https://pailei-game.app.workbuddy.host/?sharecode=LDFAXG3D2N>
- GitHub Pages 镜像：<https://moon-star-art.github.io/pailei-game/>

## 下载到本地游玩

点击右侧 **Code → Download ZIP** 下载解压，由于游戏基于现代浏览器模块化脚本，直接双击 `index.html` 可能被浏览器安全策略拦截，请用任一静态服务器托管本目录后访问，例如：

```bash
# 方式一：Python
python -m http.server 8080

# 方式二：Node.js
npx serve .
```

然后浏览器打开 <http://localhost:8080>。

## 游戏特色

- 🏰 据点攻防：占领中立据点、扩张版图，直捣敌方大本营
- 🃏 手牌即军队：每种牌都有独立的攻/防/机动属性，出牌顺序决定战局
- 🎲 每局随机：开局手牌随机、守方迎战顺序随机且保密
- 🤖 蒙特卡洛胜率采样 AI，三档进攻倾向
- 🎵 8 首 CC0 民谣风 BGM 随机连播 + 全套操作音效

## 反馈

游戏内主页点击「反馈」一键提交（直达开发者邮箱备用通道），或发邮件至 3291822404@qq.com。

## 音乐致谢

BGM 来自 troubadour 的 Fantasy Song Pack Vol.1（CC0 公共领域），可自由使用。
