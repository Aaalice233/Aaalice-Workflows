# Aaalice Workflow v0.5 更新日志

## ✨ 本次更新

### 🖼️ 图像反推

- 调整默认识别阈值：普通标签由 **0.35** 降至 **0.2**，保留更多画面细节；角色标签由 **0.75** 提升至 **0.8**，减少不确定的角色误判。
- 上述参数已同步到工作流的默认侧边栏预设。

## 🧩 ComfyUI 内核

本版继续基于 **v0.31.1**，与上一版要求一致。

> **秋叶启动器用户：**请确认已切换到上述 ComfyUI 内核版本。如果版本列表中找不到该版本，请打开启动器左下角「设置」，关闭国内镜像相关功能后刷新版本列表；国内镜像的版本更新通常较慢。

## 📦 插件更新

- **ComfyUI-Aaalice-Nodes** 更新至 **v0.14.5**（详见下方专项）
- **ComfyUI-Autocomplete-Aaalice** 更新至 **v1.13.4**（详见下方专项）

## 🎨 ComfyUI-Aaalice-Nodes v0.14.4 → v0.14.5

### 🖼️ Booru Gallery

- 修复 Gelbooru 的凭据填写、分级筛选和图片加载问题，支持直接粘贴账户页面提供的 API 凭据片段。
- 画廊搜索、排除标签和标签编辑框已适配原始 Booru 标签补全。

## 🛠️ ComfyUI-Aaalice-Workflow-Hub（安装工具）

自上一版工作流发布以来，本次无功能性变化，当前最新版为 **v1.2.2**。

建议通过 ComfyUI-Manager 或启动器把 Workflow Hub 更新到最新版，获得上述改进。

## 🔤 ComfyUI-Autocomplete-Aaalice v1.13.3 → v1.13.4

- 在 Booru 查询和标签设置中选择补全项时，会保留下划线和括号等原始格式，避免标签被改写后搜索不到。

## ⚠️ 重要提醒

> 新版 ComfyUI-Aaalice-Nodes 和旧版 ComfyUI-Danbooru-Gallery 可能存在一些神奇的冲突，记得卸载旧版插件！

## 💬 交流与安装

- Discord 服务器：<https://discord.gg/R48n6GwXzD>
- 安装教程（需先加入服务器）：<https://discord.com/channels/1349298998988771359/1375453996663312414/1535274403384786964>