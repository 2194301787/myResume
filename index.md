---
layout: default
title: 简历
theme: jekyll-theme-cayman
---

# 个人信息

- 郑浚伟/男/1997
- 本科/广东白云学院/软件工程
- 工作年限：3年

- 期望职位：WEB前端开发
- 期望城市：珠海

# 联系方式

- 手机：+86 13267967221
- Email：zjw2194301787@gmail.com
- QQ：2194301787

## 珠海创奇思技术有限公司 （ 2023年7月 ~ 2025年7月 ）

### 積金易（eMPF）平台项目

使用技术：
React、React Native、dotCMS、jQuery、ECharts JS

- 参与香港积金局主导的强积金数字化改革项目（eMPF），涵盖 Web 网站、低代码平台及移动端 App 的开发与优化。
- 作为核心开发人员，不仅完成了项目模块的日常迭代和维护，还主导可复用组件库的编写，显著提高团队的开发效率与代码一致性。
- 在 React Native 端提出并实现组件级性能优化方案，通过减少重绘、引入动画优化与渲染机制改进，显著降低界面交互卡顿。
- 基于 dotCMS 构建低代码模块，提升内容管理与快速交付能力，支持业务方灵活配置页面与流程。

### 医管局 HA Go - SuperApp 平台化架构开发

使用技术：
React、React Native、Java (Android)、Swift (iOS)、TypeScript、Metro (Metro Config)、Multi-bundle、自定义 Native Modules

- 参与香港医管局官方 App（HA Go）的超级应用（Super App）平台化改造：构建支持多医疗机构、多业务模块动态接入的底层容器架构。
- 设计并实现原生级 Multi-bundle 动态加载引擎：在 Android (Java) 与 iOS (Swift) 端深度定制 ReactInstanceManager，通过拦截 Intent 参数实现业务包的动态路径映射与注入，解决了大型 App 包体积膨胀问题。
- 开发动态 Bundle 安全校验与兜底机制：在原生端实现一套完整的 Bundle 校验逻辑，支持从本地 Asset 或远程存储空间（Data/SDCard）灵活读取资源，并在加载异常时自动执行版本回滚，确保医疗服务的高可用性。
- 主导跨项目公共组件库（super-app-common）的模块化开发：通过提取各业务模块的共用逻辑（如鉴权、网络请求、加密工具等），构建了标准化的公共依赖库，实现了代码的高度复用。

## 惟客云 （ 2021年7月 ~ 2022年6月 ）

使用技术：
Vue.js、Taro、JavaScript、Vuex、Webpack

- 主导基于 Vue Slot 的高度可复用布局架构设计：通过抽象通用组件的插槽（Slot）接口，构建了标准化的页面布局容器，显著提升了跨模块业务组件的开发灵活性与代码复用率。
- 负责复杂交互场景下的单页应用（SPA）性能优化：针对多个高频业务模块，设计并实现了多级路由切换下的复杂状态管理，并结合 keep-alive 策略优化组件缓存，有效消除了页面跳转时的卡顿感。
- 深度定制 Taro 跨端富文本渲染引擎：针对原生组件渲染瓶颈，封装并优化了 Taro 富文本标签（Rich-Text），通过预解析与按需加载技术，显著提升了移动端复杂内容的加载速度与渲染性能。
- 持续驱动系统架构迭代与前端工程化建设：负责核心业务模块的日常功能演进与代码重构，通过模块化解耦与构建脚本优化，保障了系统在高频更迭下的稳定性与可维护性。

## 个人项目

### AI 发型合成 Pro (AI Hair Synthesis)

使用技术: Node.js (Express)、ComfyUI (Workflow API)、WebAssembly (Mediapipe)、Canvas

- 自主设计并开发了一款基于 AI 的实时发型模拟与合成系统：通过前端轻量化 AI 模型与后端高性能生成流结合，实现了从“上传照片”到“发型自动对齐”再到“AI 渲染优化”的完整闭环。

- 实现基于 WebAssembly 的端侧实时 AI 交互：利用 Mediapipe (Face Landmarker / Image Segmenter) 在浏览器端实现亚秒级的人脸关键点检测与头发区域分割，通过 Canvas API 实现了发型素材的实时缩放、旋转与手动微调功能。

- 构建基于 ComfyUI Workflow 的自动化生成流水线：使用 Node.js 封装后端接口，实现了前端 Canvas 画布内容与 ComfyUI 生产环境的异步通信；通过解析 Workflow JSON 动态注入参数，实现了“去发留脸”与“局部重绘（Inpaint）”的自动化处理。

- 开发智能排队与状态轮询机制：针对 AI 生成耗时较长的问题，设计并实现了一套基于 Prompt ID 的任务状态监控系统，支持实时反馈排队位置与生成进度，显著优化了用户在长耗时任务下的交互体验。

# 技能清单

以下均为我熟练使用的技能

- Web开发：JS/TypeScript/Node
- 前端框架：React/React Native/Vue/NextJS/Express
- 前端工具：Eslint/Prettier/Webpack/Vite
- 原生开发：Java (Android SDK)、Swift (iOS SDK)
- 数据库相关：MySQL/MongoDB
- 版本管理：Svn/Git
- 云和开放平台：AWS/微信应用开发/ComfyUI

---

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
