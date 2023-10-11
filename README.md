<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-fgoavatarguess

_✨ FGO猜从者插件 ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/influ3nza/nonebot-plugin-fgoavatarguess.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-fgoavatarguess">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-fgoavatarguess.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

## 📖 介绍

FGO(Fate/GrandOrder，命运冠位指定)猜从者插件。本插件基于nonebot2开发。

## 💿 安装

<details open>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-fgoavatarguess

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-fgoavatarguess
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-fgoavatarguess
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-example
</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-example
</details>

打开 nonebot2 项目根目录下的 `pyproject.toml` 文件, 在 `[tool.nonebot]` 部分追加写入

    plugins = ["nonebot_plugin_example"]

</details>

## 🎉 使用
### 指令表
| 指令 | 权限 | 需要@ | 范围 | 说明 |
|:-----:|:----:|:----:|:----:|:----:|
| 猜从者 | 所有人 | 否 | 群聊/私聊 | 开始猜从者 |
| /quitfgo | 所有人 | 否 | 群聊/私聊 | 在猜从者进行时，停止猜从者 |
### 效果图
暂无
