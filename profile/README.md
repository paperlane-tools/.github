<div align="center">

# 纸巷工具 · paperlane-tools

**一组围绕「课程资料 / 题库 / 自动化」的小工具。**

单文件优先 · 本地优先 · 能预览就不直接写

</div>

---

## 这里有什么

| | 项目 | 一句话 | 形态 |
|---|---|---|---|
| ① | [quiz-helper](https://github.com/paperlane-tools/quiz-helper) | 浏览器里的答题助手 | Tampermonkey 用户脚本 |
| ② | [materials-helper](https://github.com/paperlane-tools/materials-helper) | 资料任务的自动完成 | 用户脚本 + Python CLI |
| ③ | [bank-editor](https://github.com/paperlane-tools/bank-editor) | 题库编辑、拆分、合并、AI 整理 | Python / tkinter |
| ④ | [android-client](https://github.com/paperlane-tools/android-client) | 在安卓上跑上面两个脚本的多开客户端 | Kotlin + WebView |

## 几条小原则

- **单文件能装** —— 浏览器脚本就一个 `.user.js`，拖进 Tampermonkey 就能用，不依赖构建。
- **本地优先** —— 题库、配置、登录态都留在本机；能查本地就不问 AI。
- **可撤销** —— 批量操作先预览再落库，误操作能 `Ctrl+Z`。
- **不打扰** —— 自动运行时只在角落写日志，需要你确认时才弹窗。
- **说清楚边界** —— 做不了的题型就整套跳过，不硬编答案。

## 关于这个名字

`paper` + `lane`：纸面的东西，走一条自己的通道。
不写平台名，也不写用途——工具就是工具，自己知道就好。

<sub>Personal tooling. Use at your own discretion.</sub>
