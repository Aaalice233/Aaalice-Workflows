# 🎨 Aaalice Workflows

这里集中发布和维护我制作的 ComfyUI 工作流。推荐配合 [ComfyUI-Aaalice-Workflow-Hub](https://github.com/Aaalice233/ComfyUI-Aaalice-Workflow-Hub) 使用，可在 ComfyUI 内订阅仓库、查看版本与更新日志、下载工作流，并检查或补全插件依赖。

## ✨ 仓库内容

- 持续维护的 ComfyUI 工作流与历史版本
- 每个版本对应的工作流文件、更新日志和完整安装包
- 工作流所需图片资源与插件依赖信息
- 可供 Workflow Hub 直接读取的订阅目录

## 🖼️ 当前工作流

### Aaalice_Workflow

面向日常出图的一体化文生图工作流，包含基础生成、提示词处理、画廊与图像反推、潜空间放大、脸部细化、SeedVR2 / VSR 放大，以及可选的局部重绘等流程。

- 📚 [查看版本列表与下载](workflows/文生图/Aaalice_Workflow/README.md)
- 📝 各版本的详细变化请查看对应 `CHANGELOG.md`

## 🚀 推荐安装方式

1. 安装 [ComfyUI-Aaalice-Workflow-Hub](https://github.com/Aaalice233/ComfyUI-Aaalice-Workflow-Hub)。
2. 重启 ComfyUI，点击顶栏的 **“工作流中心”**。
3. 添加本仓库作为订阅源：

   ```text
   https://github.com/Aaalice233/Aaalice-Workflows
   ```

4. 在工作流中心选择需要的版本并下载；如提示缺少插件，可先查看依赖差异，再按需补全。
5. 打开工作流后，请先阅读画布中的 **“👀必看”** 和功能说明，再下载对应模型并执行。

> Workflow Hub 不会自动下载模型或 LoRA。模型文件、放置目录和特殊使用要求以工作流内的说明为准。

## 🧩 配套插件

以下是我维护并与工作流配合使用的插件：

- 🧰 [ComfyUI-Aaalice-Nodes](https://github.com/Aaalice233/ComfyUI-Aaalice-Nodes)：侧边栏控制面板、组跳转、提示词选择器、Booru 画廊、分辨率预设等。
- 📦 [ComfyUI-Aaalice-Workflow-Hub](https://github.com/Aaalice233/ComfyUI-Aaalice-Workflow-Hub)：订阅、下载、版本管理和依赖检查。
- ⌨️ [ComfyUI-Autocomplete-Aaalice](https://github.com/Aaalice233/ComfyUI-Autocomplete-Aaalice)：提示词与 Danbooru 标签自动补全增强版。
- 🖼️ [ComfyUI-Aaalice-Image-Picker](https://github.com/Aaalice233/ComfyUI-Aaalice-Image-Picker)：暂停工作流并人工筛选批次图像，支持单选、多选、局部缩放和超时策略。

工作流还会使用其他第三方节点；完整依赖请以 Workflow Hub 显示的对应版本清单为准。

## 🐱 Discord 社区与教程

- 💬 [加入 Discord 服务器](https://discord.gg/R48n6GwXzD)
- 🎓 [打开工作流安装与使用教程频道](https://discord.com/channels/1349298998988771359/1536643406787387392)

> ⚠️ 教程频道仅限服务器成员查看。请先加入上面的 Discord 服务器并登录 Discord，再打开教程频道链接。

## 🐛 问题反馈

- 工作流内容、模型配置或使用问题：可在 Discord 社区交流，或在本仓库提交 [Issue](https://github.com/Aaalice233/Aaalice-Workflows/issues)。
- 插件自身的问题：请前往对应插件仓库提交 Issue，并附上复现步骤、报错日志和 ComfyUI 版本。
