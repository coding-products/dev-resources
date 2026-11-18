# dev-resources

开发常用资源索引：动效、音效、图标、UI。

多数项目**不需要 fork**，用包管理器安装即可。这个仓库只做导航和选型参考，不复制源码。

> 数据截至 2026-11-18，Star 数会变化。许可证以仓库 LICENSE 为准。

---

## 动效

| 项目 | Star | 许可证 | 说明 | 怎么用 |
|---|---|---|---|---|
| [juliangarnier/anime](https://github.com/juliangarnier/anime) | 74.9k | MIT | 轻量 JS 动画引擎 | `pnpm add animejs` |
| [hakimel/reveal.js](https://github.com/hakimel/reveal.js) | 72.6k | MIT | HTML 演示框架 | 直接引用 |
| [motiondivision/motion](https://github.com/motiondivision/motion) | 35.3k | MIT | React / JS 动画库，Framer Motion 后继 | `pnpm add motion` |
| [airbnb/lottie-web](https://github.com/airbnb/lottie-web) | 32.5k | MIT | After Effects 动画渲染到 Web | `pnpm add lottie-web` |
| [pmndrs/react-spring](https://github.com/pmndrs/react-spring) | 29.3k | MIT | 基于弹簧物理的 React 动画 | `pnpm add @react-spring/web` |
| [michalsnik/aos](https://github.com/michalsnik/aos) | 28.1k | MIT | 滚动进入动画 | `pnpm add aos` |
| [formkit/auto-animate](https://github.com/formkit/auto-animate) | 14.0k | MIT | 零配置自动动画 | `pnpm add @formkit/auto-animate` |
| [theatre-js/theatre](https://github.com/theatre-js/theatre) | 13.0k | Apache-2.0 | 可视化动效编辑器 | 动效调试 |
| [tsparticles/tsparticles](https://github.com/tsparticles/tsparticles) | 9.1k | MIT | 粒子背景 | `pnpm add @tsparticles/react` |
| [lewislulu/html-ppt-skill](https://github.com/lewislulu/html-ppt-skill) | 9.1k | MIT | HTML 演示文稿生成技能 | Agent Skill |
| [vueuse/motion](https://github.com/vueuse/motion) | 2.8k | MIT | Vue 组合式动画 | `pnpm add @vueuse/motion` |
| [gl-transitions/gl-transitions](https://github.com/gl-transitions/gl-transitions) | 2.3k | MIT | GLSL 转场集合 | 视频/WebGL 转场参考 |
| [ColorlibHQ/velora-ui](https://github.com/ColorlibHQ/velora-ui) | 64 | MIT | 动画 shadcn 组件 + 落地页模板 | 按组件复制 |
| [scriptituk/xfade-easing](https://github.com/scriptituk/xfade-easing) | 127 | MIT | FFmpeg xfade 缓动扩展 | 与 `cc-ffmpeg-xfade` 配套 |

**选型**：React 优先 `motion`；需要弹簧手感用 `react-spring`；Vue 用 `@vueuse/motion` 或 `motion`；视频转场看 `gl-transitions` 和 `xfade-easing`。

---

## 音效 / 音频

| 项目 | Star | 许可证 | 说明 | 怎么用 |
|---|---|---|---|---|
| [goldfire/howler.js](https://github.com/goldfire/howler.js) | 25.5k | MIT | 现代 Web 音频播放库 | `pnpm add howler` |
| [Tonejs/Tone.js](https://github.com/Tonejs/Tone.js) | 14.9k | MIT | Web Audio 框架，做交互音乐 | `pnpm add tone` |
| [katspaugh/wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) | 10.5k | BSD-3-Clause | 音频波形播放器 | `pnpm add wavesurfer.js` |
| [QwenAudio/CosyVoice](https://github.com/QwenAudio/CosyVoice) | 24.4k | Apache-2.0 | 多语言语音生成 | 模型部署 |
| [kapishdima/soundcn](https://github.com/kapishdima/soundcn) | 951 | MIT | 700+ UI 音效，带预览 | `npx soundcn` |
| [romainsimon/uisfx](https://github.com/romainsimon/uisfx) | 945 | MIT | 界面音效库（Vue） | 按需引入 |
| [OpenMOSS/MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD) | 1.4k | Apache-2.0 | 多说话人对话合成 | 模型部署 |

**选型**：网页音频播放用 `howler`；需要合成/交互音乐用 `Tone.js`；波形可视化用 `wavesurfer`；UI 反馈音用 `soundcn` 或 `uisfx`。

**已排除**：`bbc/peaks.js`（LGPL-3.0）、`SPlayer`（AGPL-3.0）、`fish-speech`（自定义非商用条款）。

---

## 图标

| 项目 | Star | 许可证 | 说明 | 怎么用 |
|---|---|---|---|---|
| [FortAwesome/Font-Awesome](https://github.com/FortAwesome/Font-Awesome) | 77.0k | CC BY 4.0 / OFL / MIT | 经典图标字体与 SVG | `pnpm add @fortawesome/fontawesome-free` |
| [google/material-design-icons](https://github.com/google/material-design-icons) | 54.3k | Apache-2.0 | Material Symbols 官方图标 | 按需下载 |
| [feathericons/feather](https://github.com/feathericons/feather) | 26.0k | MIT | 简洁线条图标 | `pnpm add feather-icons` |
| [tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons) | 23.9k | MIT | Tailwind 官方图标 | `pnpm add @heroicons/react` |
| [microsoft/fluentui-system-icons](https://github.com/microsoft/fluentui-system-icons) | 11.0k | MIT | Fluent 系统图标 | 按需下载 |
| [Remix-Design/RemixIcon](https://github.com/Remix-Design/RemixIcon) | 8.5k | 自定义（允许商用，禁止单独售卖） | 中性风格图标系统 | `pnpm add remixicon` |
| [iconoir-icons/iconoir](https://github.com/iconoir-icons/iconoir) | 4.6k | MIT | 1,383 个 SVG 图标 | `pnpm add iconoir-react` |
| [dicebear/dicebear](https://github.com/dicebear/dicebear) | 10.1k | MIT | 头像生成：种子字符串 → 63 种风格 SVG，七语言实现 | `pnpm add @dicebear/core` |
| [lucide-icons/lucide](https://github.com/lucide-icons/lucide) | 25.8k | ISC | shadcn 默认图标库 | `pnpm add lucide-react` |
| [tabler/tabler-icons](https://github.com/tabler/tabler-icons) | 22.7k | MIT | 5000+ 图标，多框架 | `pnpm add @tabler/icons-react` |
| [iconify/iconify](https://github.com/iconify/iconify) | 6.4k | MIT | 统一 200+ 图标集 | `pnpm add @iconify/react` |
| [simple-icons/simple-icons](https://github.com/simple-icons/simple-icons) | 26.2k | CC0 1.0 | 品牌 Logo 图标 | `pnpm add simple-icons` |
| [phosphor-icons/phosphor-home](https://github.com/phosphor-icons/phosphor-home) | 7.8k | MIT | 多字重图标系统 | `pnpm add @phosphor-icons/react` |

**选型**：shadcn 项目用 `lucide`；需要品牌图标用 `simple-icons`；图标数量大用 `iconify`；Tailwind 项目用 `heroicons`。

**注意**：Font Awesome 免费版是 CC BY 4.0（图标）+ OFL（字体）+ MIT（代码），商用需保留署名；Pro 版是商业授权。RemixIcon 为自定义许可，允许商用但禁止单独售卖图标。

---

## UI / 组件

| 项目 | Star | 许可证 | 说明 | 适合 |
|---|---|---|---|---|
| [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 128.5k | MIT | 可组合、可访问的组件 | React 项目默认 |
| [ant-design/ant-design](https://github.com/ant-design/ant-design) | 100.3k | MIT | 企业级 UI 设计语言 | 中后台 |
| [mui/material-ui](https://github.com/mui/material-ui) | 99.4k | MIT | 完整 React 组件库 | 快速成型 |
| [tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) | 98.8k | MIT | 原子化 CSS | 几乎所有新项目 |
| [storybookjs/storybook](https://github.com/storybookjs/storybook) | 91.6k | MIT | 组件开发与文档工作台 | 组件库建设 |
| [react-hook-form/react-hook-form](https://github.com/react-hook-form/react-hook-form) | 44.9k | MIT | 表单状态管理 | 复杂表单 |
| [saadeghi/daisyui](https://github.com/saadeghi/daisyui) | 42.9k | MIT | Tailwind 组件主题 | 快速原型 |
| [vuetifyjs/vuetify](https://github.com/vuetifyjs/vuetify) | 41.0k | MIT | Vue 组件框架 | Vue 中后台 |
| [chakra-ui/chakra-ui](https://github.com/chakra-ui/chakra-ui) | 40.7k | MIT | SaaS 风格组件系统 | React 产品 |
| [ueberdosis/tiptap](https://github.com/ueberdosis/tiptap) | 39.1k | MIT | Headless 富文本编辑器 | 文档/编辑器 |
| [floating-ui/floating-ui](https://github.com/floating-ui/floating-ui) | 32.8k | MIT | 浮层定位引擎 | 弹层/下拉 |
| [mantinedev/mantine](https://github.com/mantinedev/mantine) | 32.0k | MIT | 功能完整的 React 组件库 | 中后台 |
| [heroui-inc/heroui](https://github.com/heroui-inc/heroui) | 31.3k | Apache-2.0 | 动效友好的 React UI 库 | 产品界面 |
| [tailwindlabs/headlessui](https://github.com/tailwindlabs/headlessui) | 28.8k | MIT | 无样式可访问组件 | 自定义设计系统 |
| [TanStack/table](https://github.com/TanStack/table) | 28.6k | MIT | Headless 表格 | 数据表格 |
| [element-plus/element-plus](https://github.com/element-plus/element-plus) | 27.9k | MIT | Vue 3 组件库 | 后台管理系统 |
| [quasarframework/quasar](https://github.com/quasarframework/quasar) | 27.2k | MIT | Vue 全栈框架 | 多端应用 |
| [youzan/vant](https://github.com/youzan/vant) | 24.4k | MIT | 移动端 Vue 组件库 | H5 / 小程序 |
| [magicuidesign/magicui](https://github.com/magicuidesign/magicui) | 23.4k | MIT | 动效组件库 | 营销页 |
| [radix-ui/primitives](https://github.com/radix-ui/primitives) | 19.5k | MIT | 无样式可访问基础组件 | 设计系统底座 |
| [tusen-ai/naive-ui](https://github.com/tusen-ai/naive-ui) | 18.6k | MIT | Vue 3 组件库 | 中后台 |
| [satnaing/shadcn-admin](https://github.com/satnaing/shadcn-admin) | 16.8k | MIT | shadcn 后台模板 | 快速起后台 |
| [primefaces/primevue](https://github.com/primefaces/primevue) | 14.4k | MIT | Vue 组件库 | 企业应用 |
| [unovue/shadcn-vue](https://github.com/unovue/shadcn-vue) | 10.8k | MIT | shadcn 的 Vue 版 | Vue 项目 |
| [vbenjs/vue-vben-admin](https://github.com/vbenjs/vue-vben-admin) | 33.8k | MIT | Vue3 + shadcn 后台 | 中大型后台 |
| [TanStack/virtual](https://github.com/TanStack/virtual) | 7.2k | MIT | 大列表虚拟滚动 | 长列表/表格 |

**选型**：React 用 `shadcn-ui` + `tailwindcss`；Vue 用 `shadcn-vue` 或 `element-plus`；移动端用 `vant`；后台模板看 `shadcn-admin` / `vue-vben-admin`。

---

## 使用原则

1. **优先装包，不 fork**：fork 只在需要改源码时做。
2. **先看许可证**：优先 MIT / Apache-2.0 / BSD / ISC；LGPL、AGPL、非商业协议要单独评估。
3. **动效克制**：尊重 `prefers-reduced-motion`，不要为动效牺牲首屏。
4. **音效默认关闭**：给用户开关，不要自动播放。
5. **图标统一一套**：混用多套图标会让界面显得杂乱。
6. **UI 库只选一个**：同一个项目里不要同时引入多个组件库。

---

<sub>由 [LawyerCH](https://github.com/LawyerCH) 维护 · 资源来自 GitHub Stars 与日常使用</sub>
