<div align="center">

# 纸巷工具 · paperlane-tools

**一组围绕「课程资料 / 题库 / 自动化」的小工具。**

单文件优先 · 本地优先 · 能预览就不直接写

> 目前所有工具都面向 **易智教云课堂（`csgmooc.com`）**；其他平台的页面与接口不通用。

</div>

---

## 这里有什么

| | 项目 | 一句话 | 形态 | 状态 |
|---|---|---|---|---|
| ① | [quiz-helper](https://github.com/paperlane-tools/quiz-helper) | 浏览器里的答题助手 | Tampermonkey 用户脚本 | ✅ 稳定 |
| ② | [materials-helper](https://github.com/paperlane-tools/materials-helper) | 资料任务的自动完成 | 用户脚本 + Python CLI | ✅ 稳定 |
| ③ | [bank-editor](https://github.com/paperlane-tools/bank-editor) | 题库编辑、拆分、合并、AI 整理 | Python / tkinter | 🚧 半成品 |
| ④ | [android-client](https://github.com/paperlane-tools/android-client) | 在安卓上跑上面两个脚本的多开客户端 | Kotlin + WebView | 🚧 半成品 |
| ⑤ | [pipeline-legacy](https://github.com/paperlane-tools/pipeline-legacy) | 最早的 Python 识图/判题流水线 | Python + Playwright | ⚠️ 仅验证 |

> **pipeline-legacy 是早期验证版本，不是主推。** 日常使用请用 `quiz-helper`。
> 两个「半成品」已经能粗略使用，但仍有已知问题；欢迎自行扩展或提交 PR。

## 几条小原则

- **单文件能装** —— 浏览器脚本就一个 `.user.js`，拖进 Tampermonkey 就能用，不依赖构建。
- **本地优先** —— 题库、配置、登录态都留在本机；能查本地就不问 AI。
- **可撤销** —— 批量操作先预览再落库，误操作能 `Ctrl+Z`。
- **不打扰** —— 自动运行时只在角落写日志，需要你确认时才弹窗。
- **说清楚边界** —— 做不了的题型就整套跳过，不硬编答案。

## 关于这个名字

`paper` + `lane`：纸面的东西，走一条自己的通道。
不写平台名，也不写用途——工具就是工具，自己知道就好。

## 免责声明

本项目仅供**个人学习、技术研究与交流**使用。

- 不保证答案正确、功能完整或持续可用。
- 使用本项目产生的任何后果（包括但不限于账号异常、成绩问题、数据丢失、违反平台或学校规定）由使用者自行承担。
- 请遵守所在学校 / 教育机构及目标平台的服务条款；不要用于商业用途或大规模滥用。
- 本项目与目标平台及其运营方无任何关联，也未获得其授权或认可。
- 若相关权利方认为内容侵犯其权益，请联系删除。

## 许可证

各仓库均为 [MIT](LICENSE) © 2026 paperlane-tools。
