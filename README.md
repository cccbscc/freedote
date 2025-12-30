# freedote
> 这是一个基于 Supabase 和 DeepSeek 开发的个人知识库，支持离线 / 云端双模式同步。
> 本项目网页代码完全由 Gemini 提供，个人只做整合与修饰功用。
## 核心功能
-  AI 智能整理 ：集成 DeepSeek 模型，支持 `@待办`、`@灵感` 指令自动分类，主要基础是文本润色。
-  双模切换 ：
  -  离线模式 ：基于 LocalStorage，数据记录在本地浏览器。
  -  云端同步 ：基于 Supabase，实现手机/电脑多端数据实时同步。
-  Markdown 支持 ：所见即所得的笔记体验，支持格式化排版与自定义编辑。
-  极速部署 ：纯静态 HTML/JS 编写，无需复杂的后端服务器，打开浏览器即可使用。
## 如何使用
1. 下载本项目中的 `index.html`。
2. 双击直接在浏览器打开即可使用“离线模式”。
3. 如需开启“云端模式”，访问网址[cccbscc.github.io/freedote/](https://cccbscc.github.io/freedote/)。
