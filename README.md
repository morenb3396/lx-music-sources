# LX Music 音源

保存五个原始自定义音源脚本，供 LX Music 通过 HTTP/HTTPS 地址导入。原脚本内容保持不变。

## 导入

LX Music 桌面版 2.7.0 及以上：设置 → 自定义源管理 → 在线导入（不同版本按钮名称可能不同），粘贴下表中的完整地址。导入后选择需要启用的音源。

| 音源 | 导入地址 |
| --- | --- |
| 全豆要聚合音源 v4.0 | https://raw.githubusercontent.com/morenb3396/lx-music-sources/main/sources/quandouya-v4.js |
| 统一音乐源 v1.0.0 | https://raw.githubusercontent.com/morenb3396/lx-music-sources/main/sources/unified-v1.js |
| 野草音源 | https://raw.githubusercontent.com/morenb3396/lx-music-sources/main/sources/yecao.js |
| 野花音源 | https://raw.githubusercontent.com/morenb3396/lx-music-sources/main/sources/yehua.js |
| 长青 SVIP v1.3.0 | https://raw.githubusercontent.com/morenb3396/lx-music-sources/main/sources/changqing-v1.3.js |

每个链接导入一个脚本，LX Music 同时启用一个自定义源。目录、README 或 ZIP 的链接不能批量导入全部五个脚本。全豆要脚本自身已包含多个后端及回退逻辑。

## 说明

- 本仓库仅保存脚本，不托管音乐文件。第三方服务的可用性、音质及授权由相应服务决定。
- 原作者信息保留在各脚本头部；未为第三方脚本新增开源许可证。
- 已检查副本与原文件一致，尚未验证 LX Music 实际导入及播放。

参考：[官方自定义源文档](https://lxmusic.toside.cn/desktop/custom-source)、[v2.7.0 发布说明](https://github.com/lyswhut/lx-music-desktop/releases/tag/v2.7.0)。
