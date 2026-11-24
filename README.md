<div align="center">
  
### [🇨🇳 简体中文](README.md) | [🇺🇸 English](README_EN.md)

</div>

# weilin-comfyui-prompt-all-in-one-2026

> 这是 WeiLin 原版提示词编辑器的旧版本节点库。本分支由使用者维护，并非原作者发布；保留原有节点类型、工作流兼容性与编辑器功能，并针对新版 ComfyUI 做适配。已针对 ComfyUI **v0.46.3**（commit `cab5f4e13b83c58482cd514afb22ca925e117638`）修复已知加载兼容问题。维护与更新不作保证，其他 ComfyUI 版本请以实际测试为准。

# Lora 提示词写法提示

<lora:xxxx:0.3:0.4>这种写法解释 0.3 是模型强度 0.4 是 CLIP 强度
如果你是<lora:xxxx:0.4>那么这种写法解释 模型强度和 CLIP 强度都是 0.4

# 概要说明

本项目可以让你在 ComfyUI 中像 WebUI 一样写提示词，从 Prompt-all-in-one 项目修改而来但已做了大部分的修改适配 ComfyUI，新增了许多不一样的功能，以及提示词补全的插件，提示词补全插件是从 ComfyUI-Custom-Scripts 项目修改而来，感谢你对本插件的支持。

如果你对本项目有兴趣赏一个 Star 吧！

# 安装教程，可以直接 git 本项目即可

> https://github.com/wale-jojo/weilin-comfyui-prompt-all-in-one-2026.git

# 安装插件详细介绍，手动安装版本

直接下载本项目最新的 Release 然后解压，放到 ComfyUI 直接启动 ComfyUI 即可使用本插件。
![](https://github.com/weilin9999/WeiLin-ComfyUI-prompt-all-in-one/blob/master/step/1.png)

# 节点使用方法

按以下操作使用即可
![](https://github.com/weilin9999/WeiLin-ComfyUI-prompt-all-in-one/blob/master/step/2.png)
![](https://github.com/weilin9999/WeiLin-ComfyUI-prompt-all-in-one/blob/master/step/3.png)
![](https://github.com/weilin9999/WeiLin-ComfyUI-prompt-all-in-one/blob/master/step/4.png)

# 插件设置预览

![](https://github.com/weilin9999/WeiLin-ComfyUI-prompt-all-in-one/blob/master/step/5.png)

# WeiLin-ComfyUI-Prompt-all-in-one 借鉴项目

WeiLin-ComfyUI-Prompt-all-in-one ComfyUI 版的 prompt-all-in-one，在基于 sd-webui-prompt-all-in-one-app https://github.com/Physton/sd-webui-prompt-all-in-one-app 项目上修改而来的 ComfyUI 版本，只需要在 ComfyUI 中添加本项目的 ComfyUI 节点即可使用可视化的 tag 编辑器 ，提示词补全使用了 https://github.com/pythongosssss/ComfyUI-Custom-Scripts 项目进行修改只用了补全功能并做了修改，项目使用的本地 LLM 大模型借鉴了https://github.com/thisjam/comfyui-sixgod_prompt仓库的代码

如果你喜欢本项目赏一个 star 吧！

# 本项目简要说明

本仓库是 WeiLin 原版项目的用户维护分支。欢迎提交问题反馈，但不保证会处理或持续更新。
