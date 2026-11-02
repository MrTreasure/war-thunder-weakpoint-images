# War Thunder weakpoint image host

《战争雷霆》坦克弱点截图图床，仅维护 WebP 图片。

- `images/<country>/`：按国家简称与完整英文车型命名的 WebP，如 `USA-M1A1-Click-Bait-01m10s.webp`、`USSR-IS-3-front.webp`。
- 同车多张以视角或视频时间区分；哈希仅用于元数据校验，不写入图片文件名。
- 车型身份未核实的素材暂留本机资料库，确认后才按车型入图床。
- `catalog.json`：SHA-256、字节数、原采集帧哈希、来源、视频时间点、车型和核对状态。
- 仓库及分支历史不保留 PNG、视频、网页、源码、登录态和密钥。
- 待核对素材不代表已完成攻略；车型身份和攻击位置分开核对。

固定版本地址使用完整 Git commit：

```text
https://cdn.jsdelivr.net/gh/MrTreasure/war-thunder-weakpoint-images@<full-commit>/<path>
https://raw.githubusercontent.com/MrTreasure/war-thunder-weakpoint-images/<full-commit>/<path>
```

游戏画面归 Gaijin 等相关权利人所有，解说内容归原作者所有；来源署名保留，不宣称转载授权。带明确转载限制的图片不收入公开图床，公开文字证据仍可在本机资料库保留核对。
