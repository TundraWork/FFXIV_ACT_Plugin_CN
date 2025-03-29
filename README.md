
> 温馨提示:下方有中文版本.

---

# FFXIV_ACT_Plugin_CN

FFXIV_ACT_Plugin for FFXIV CN client.

## About

This is a modified version of FFXIV_ACT_Plugin that provides the ability to run and generate combat logs compatible with FF Logs (only) with FFXIV CN client.

For more details about FFXIV_ACT_Plugin, please refer to [https://github.com/ravahn/FFXIV_ACT_Plugin](https://github.com/ravahn/FFXIV_ACT_Plugin).

### NOTES

* FFXIV_ACT_Plugin_CN is designed to support the current FFXIV CN client version, which is typically about four months behind the JP, NA, and EU client versions.
* FFXIV_ACT_Plugin_CN should be loaded on the original Advanced Combat Tracker. Do not use it with modified versions of ACT.

## Installing

The procedure is exactly the same as the original version.

Please referrer to [FFXIV_ACT_Plugin's README.md](https://github.com/ravahn/FFXIV_ACT_Plugin/blob/master/README.md).

## README for Developers

We are completely open to other developers in the FFXIV community. Whether you are a developer of plugins/tools for the FFXIV Chinese or Global version, we are happy to provide you with details of this modified FFXIV_ACT_Plugin version and to help your plugins/tools work with this version.

FFXIV_ACT_Plugin_CN currently has the following changes compared to the original FFXIV_ACT_Plugin:

* All built-in resources (like skills, abilities, buffs, regions, etc.) are patched and consistent with the FFXIV CN client.
* Patched Machina with network IPC opcodes of the latest FFXIV CN client version.
* Patched Machina so that it can automatically find the process of the FFXIV Chinese client.
* Changed some hardcoded memory offsets according to the FFXIV CN client version.
* Please contact us for more detailed changes.

### NOTES

* This version may have some changes not mentioned above. If your plugins/tools have some "advanced" mechanisms (like detecting game language from FFXIV_ACT_Plugin), please also get in touch with us.

## Contact Us

NOTE: Do NOT use these links if you are a user of FFXIV_ACT_Plugin_CN. Please [open an issue](https://github.com/TundraWork/FFXIV_ACT_Plugin_CN/issues) instead.

* [Telegram](https://t.me/YuzurihaAsano)
* [联系我们 - FFCafe](https://ffcafe.org/contact/) (if you can speak Chinese)

---

# FFXIV_ACT_Plugin_CN

适用于最终幻想14国服客户端的 FFXIV_ACT_Plugin

## 关于

这是一个修改版 FFXIV_ACT_Plugin ，它(仅)可以与最终幻想14国服客户端一起运行并且生成兼容 FF Logs 网站的战斗日志。

更多关于 FFXIV_ACT_Plugin 的细节请参考 [https://github.com/ravahn/FFXIV_ACT_Plugin](https://github.com/ravahn/FFXIV_ACT_Plugin) 。

### 注意

* FFXIV_ACT_Plugin_CN 只支持最终幻想14国服客户端版本（一般它会比日服、美服、欧服版本慢半年左右）。
* FFXIV_ACT_Plugin_CN 只支持运行在原版 ACT 上。请不要在修改版、整合版 ACT 上使用它。

## 安装

安装方法与原版 FFXIV_ACT_Plugin 完全一致。

请参考 [FFXIV_ACT_Plugin's README.md](https://github.com/ravahn/FFXIV_ACT_Plugin/blob/master/README.md) 。

## 给开发者的 README

我们非常欢迎最终幻想14大家庭内的其他开发者。无论你是最终幻想14国服版本还是其他地区版本客户端的 ACT 插件或其他工具开发者，我们都非常愿意为你提供关于此 FFXIV_ACT_Plugin 修改版本的细节，并帮助你使得你的插件或工具可以支持与此 FFXIV_ACT_Plugin 版本一起工作。

FFXIV_ACT_Plugin_CN 当前相比于原版 FFXIV_ACT_Plugin 有以下更改：

* 所有内置资源（包括技能，能力，状态，地区，等等）均已修改并与最终幻想14国服客户端一致
* 修改过的 Machina 库，拥有最终幻想14国服客户端的网络 IPC 指令码
* 修改过的 Machina 库，可以自动寻找到最终幻想14国服客户端进程
* 基于最终幻想14国服客户端版本修改了一些代码内的内存偏移值
* 请联系我们询问更详细的更改内容

### 注意

* 此版本客户端可能有上面未提到的更改，如果你的插件或工具拥有一些“高级”机制（例如通过 FFXIV_ACT_Plugin 获取最终幻想14客户端语言），也请与我们联系。

## 联系我们

注意：如果你是 FFXIV_ACT_Plugin_CN 插件用户，请**不要**使用以下链接联系我们。使用插件中遇到问题请[开一个新 issue](https://github.com/TundraWork/FFXIV_ACT_Plugin_CN/issues) 。

* [联系我们 - FFCafe](https://ffcafe.org/contact/)
* [Telegram](https://t.me/YuzurihaAsano)

---

**Something about the future**

Our team is shifting our focus from maintaining FFXIV_ACT_Plugin and Advanced Combat Tracker to creating a brand new FFXIV plugin ecosystem.

If you're interested in doing something big, and meet one of the following requirements, you can reach me at [Telegram](https://t.me/YuzurihaAsano) or [Discord](https://discord.gg/KYbkUnU).

- experienced at UX/UI designing
- have a good understanding of current ACT plugins (or at least FFXIV_ACT_Plugin)
- have a good understanding of FFXIV combat system (eg. how to calculate damage per potency, etc.)
- experienced at developing TypeScript plugin system

**Proposed features of the new project**

- Intuitive GUI, easy to use & configure
- Custom skins for GUI
- Local high-precision aDPS & rDPS tracking, without uploading logs to FFLogs
- Modern TypeScript plugin system
- Responsive data interfaces for plugins, no more "log lines" parsing
- Low-level network & memory data interfaces
- Custom in-game overlays based on webview
- Cactbot compatibility
- Custom user-scripts for creating triggers
- Remote data source support (analyse game instance running on PS4/other PCs)

**Roadmap of the new project**

- [x] [Done] Compatible with FFLogs
- [ ] [Ongoing] Calculate DPS from network data, with DoT simulation
- [ ] [Ongoing] GUI built with Electron
- [ ] Custom overlays like OverlayPlugin
- [ ] Compatible with cactbot raidboss
- [ ] Custom plugins with powerful API
- [ ] Custom triggers like Triggernometry
- [ ] PS4/Router Support
