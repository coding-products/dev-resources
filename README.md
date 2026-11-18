# dev-resources

开发常用资源索引：动效、音效、图标、UI。

多数项目**不需要 fork**，用包管理器安装即可。这个仓库只做导航和选型参考，不复制源码。

> 数据截至 2026-11-18，Star 数会变化。

---

## 动效

| 项目 | Star | 说明 | 怎么用 |
|---|---|---|---|
| [motiondivision/motion](https://github.com/motiondivision/motion) | 35.3k | React / JS 动画库，Framer Motion 后继 | `pnpm add motion` |
| [DavidHDev/react-bits](https://github.com/DavidHDev/react-bits) | 52.2k | React 动画与交互组件集合 | 按组件复制或 npm |
| [DavidHDev/vue-bits](https://github.com/DavidHDev/vue-bits) | 4.7k | Vue 版动画组件集合 | 按组件复制 |
| [juliangarnier/anime](https://github.com/juliangarnier/anime) | 74.9k | 轻量 JS 动画引擎 | `pnpm add animejs` |
| [airbnb/lottie-web](https://github.com/airbnb/lottie-web) | 32.5k | After Effects 动画渲染到 Web | `pnpm add lottie-web` |
| [hakimel/reveal.js](https://github.com/hakimel/reveal.js) | 72.6k | HTML 演示框架 | 直接引用 |
| [blasten/turn.js](https://github.com/blasten/turn.js) | 7.5k | HTML5 翻页效果 | 直接引用 |
| [ts1/flipbook-vue](https://github.com/ts1/flipbook-vue) | 772 | Vue 3D 翻页 | `pnpm add vue-flipbook` |
| [gl-transitions/gl-transitions](https://github.com/gl-transitions/gl-transitions) | 2.3k | GLSL 转场集合 | 视频/WebGL 转场参考 |
| [scriptituk/xfade-easing](https://github.com/scriptituk/xfade-easing) | 127 | FFmpeg xfade 缓动扩展 | 与 `cc-ffmpeg-xfade` 配套 |
| [ColorlibHQ/velora-ui](https://github.com/ColorlibHQ/velora-ui) | 64 | 动画 shadcn 组件 + 落地页模板 | 已 fork |
| [lewislulu/html-ppt-skill](https://github.com/lewislulu/html-ppt-skill) | 9.1k | HTML 演示文稿生成技能 | Agent Skill |

**选型**：React 项目优先 `motion` + `react-bits`；Vue 项目用 `vue-bits` + `flipbook-vue`；视频转场看 `gl-transitions` 和 `xfade-easing`。

---

## 音效 / 音频

| 项目 | Star | 说明 | 怎么用 |
|---|---|---|---|
| [kapishdima/soundcn](https://github.com/kapishdima/soundcn) | 951 | 700+ UI 音效，带预览和安装命令 | `npx soundcn` |
| [romainsimon/uisfx](https://github.com/romainsimon/uisfx) | 945 | 界面音效库（Vue） | 按需引入 |
| [SPlayer-Dev/SPlayer](https://github.com/SPlayer-Dev/SPlayer) | 7.4k | 跨平台音乐播放器 | 桌面端参考 |
| [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech) | 33.8k | 开源 TTS | 模型部署 |
| [QwenAudio/CosyVoice](https://github.com/QwenAudio/CosyVoice) | 24.4k | 多语言语音生成 | 模型部署 |
| [OpenMOSS/MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD) | 1.4k | 多说话人对话合成 | 模型部署 |

**选型**：给网页加反馈音用 `soundcn` 或 `uisfx`；语音合成看 `CosyVoice` / `fish-speech`。

---

## 图标

你 star 列表里暂时没有专门的图标库，下面是常用补充：

| 项目 | 说明 | 怎么用 |
|---|---|---|
| [lucide-icons/lucide](https://github.com/lucide-icons/lucide) | 线条风格，shadcn 默认图标库 | `pnpm add lucide-react` |
| [tabler/tabler-icons](https://github.com/tabler/tabler-icons) | 5000+ 图标，多框架 | `pnpm add @tabler/icons-react` |
| [iconify/iconify](https://github.com/iconify/iconify) | 统一 200+ 图标集 | `pnpm add @iconify/react` |
| [simple-icons/simple-icons](https://github.com/simple-icons/simple-icons) | 品牌 Logo 图标 | `pnpm add simple-icons` |
| [phosphor-icons/phosphor](https://github.com/phosphor-icons/phosphor) | 多字重图标系统 | `pnpm add @phosphor-icons/react` |

**选型**：shadcn 项目直接用 `lucide`；需要品牌图标用 `simple-icons`；图标集多时用 `iconify`。

---

## UI / 组件

| 项目 | Star | 说明 | 适合 |
|---|---|---|---|
| [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 128.5k | 可组合、可访问的组件 | React 项目默认 |
| [tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) | 98.8k | 原子化 CSS | 几乎所有新项目 |
| [saadeghi/daisyui](https://github.com/saadeghi/daisyui) | 42.9k | Tailwind 组件主题 | 快速出原型 |
| [tailwindlabs/headlessui](https://github.com/tailwindlabs/headlessui) | 28.8k | 无样式可访问组件 | 自定义设计系统 |
| [ueberdosis/tiptap](https://github.com/ueberdosis/tiptap) | 39.1k | Headless 富文本编辑器 | 文档/编辑器 |
| [element-plus/element-plus](https://github.com/element-plus/element-plus) | 27.9k | Vue 3 组件库 | 后台管理系统 |
| [youzan/vant](https://github.com/youzan/vant) | 24.4k | 移动端 Vue 组件库 | H5 / 小程序 |
| [tusen-ai/naive-ui](https://github.com/tusen-ai/naive-ui) | 18.6k | Vue 3 组件库 | 中后台 |
| [unovue/shadcn-vue](https://github.com/unovue/shadcn-vue) | 10.8k | shadcn 的 Vue 版 | Vue 项目 |
| [primefaces/primevue](https://github.com/primefaces/primevue) | 14.4k | Vue 组件库 | 企业应用 |
| [satnaing/shadcn-admin](https://github.com/satnaing/shadcn-admin) | 16.8k | shadcn 后台模板 | 快速起后台 |
| [vbenjs/vue-vben-admin](https://github.com/vbenjs/vue-vben-admin) | 33.8k | Vue3 + shadcn 后台 | 中大型后台 |
| [TanStack/virtual](https://github.com/TanStack/virtual) | 7.2k | 大列表虚拟滚动 | 长列表/表格 |

**选型**：React 用 `shadcn-ui` + `tailwindcss`；Vue 用 `shadcn-vue` 或 `element-plus`；移动端用 `vant`；后台模板看 `shadcn-admin` / `vue-vben-admin`。

---

## 使用原则

1. **优先装包，不 fork**：fork 只在需要改源码时做。
2. **动效克制**：尊重 `prefers-reduced-motion`，不要为动效牺牲首屏。
3. **音效默认关闭**：给用户开关，不要自动播放。
4. **图标统一一套**：混用多套图标会让界面显得杂乱。
5. **UI 库只选一个**：同一个项目里不要同时引入多个组件库。

---

<sub>由 [LawyerCH](https://github.com/LawyerCH) 维护 · 资源来自 GitHub Stars 与日常使用</sub>
