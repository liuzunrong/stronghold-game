# 卫戍协议：盟约 · 个人联机入口

游戏原作者为 **[sganggs](https://github.com/sganggs)**。
原项目：[sganggs/Stronghold-Protocol](https://github.com/sganggs/Stronghold-Protocol)，当前本机部署版本为 **v0.1.2**。

本仓库仅提供个人联机入口与当前服务地址，不包含游戏素材。本网站与原作者、鹰角网络或 Yostar 无隶属关系，也未获得官方授权或认可。

**非官方同人。游戏名称、角色、美术、音乐、音效、文本与数据等素材版权归鹰角 / Yostar 等原权利人所有。仅供个人非商业使用，禁止任何形式的盈利。**

原项目自行编写的代码使用 GPL-3.0-or-later；游戏素材不适用 GPL。请阅读原项目的 [LICENSE](https://github.com/sganggs/Stronghold-Protocol/blob/main/LICENSE) 和 [NOTICE.md](https://github.com/sganggs/Stronghold-Protocol/blob/main/NOTICE.md)。本仓库的入口页面代码也以 GPL-3.0-or-later 发布。

## 联机

固定入口：https://liuzunrong.github.io/stronghold-game/

房主需要保持电脑开机，并运行“启动公网联机.cmd”。进入游戏后选择“同盟模拟”，创建房间并把房间码告诉朋友。支持 1–4 人合作和 AI 队友。

GitHub Pages 承载入口页面，游戏服务器运行在房主电脑，通过 Cloudflare Tunnel 提供公网连接。本机启动程序会更新 `server.json`；朋友无需随后台地址变化更换入口网址。临时隧道没有可用性保证，跨网络延迟及访问效果取决于网络条件。

不要将本机的部署私钥或配置中的凭据上传到任何公开仓库。
