# 前端 AI 手记 · 资料仓库

> 柯里 · 前端工程师 / AI 编程实战
> 公众号「前端AI手记」配套资料仓库。每篇文章末尾的「钩子」资料，都汇集在这里。
> 关注公众号，在对话框发送关键词，自动拿到对应资料链接。

## 这个仓库是干嘛的

我写「前端 × AI 编程」的实战文章——组件生成、老项目重构、设计稿转码、TS 补全、AI 调试。
每篇文章末尾都会给一个钩子：在公众号对话框回复对应关键词，就能领到这篇文章的配套资料（速查表 / Checklist / 可复制模板）。

所有资料统一放在这个仓库，链接永远不变，你不用记一堆网盘地址。

## 资料清单

| 关键词 | 资料 | 对应文章 | 下载 |
| --- | --- | --- | --- |
| `速查表` | 前端 AI 编程提示词速查表（3 页 A4） | 《用 Cursor 写 Vue 组件，我总结出 6 个能直接抄的提示词》 | [prompt-cheatsheet.pdf](prompt-cheatsheet.pdf) |
| `review清单` | AI 代码审查 Checklist（1 页 A4） | 《AI 生成的前端代码，我 review 完发现 5 个通病》 | [code-review-checklist.pdf](code-review-checklist.pdf) |
| `还原度` | 4 组设计稿转码对照表（1 页 A4） | 《同一张设计稿转前端代码，我测了 4 个 AI 工具，还原度差距比想象大》 | [design2code-compare.pdf](design2code-compare.pdf) |
| `报错` | 9 组报错问答实录（1 页 A4） | 《同一个前端报错，我分别问了 Cursor、Copilot 和 Claude Code》 | [error-debug-qa.pdf](error-debug-qa.pdf) |
| `12场景` | 12 场景提效评估表（1 页 A4） | 《前端用 AI 提效的 12 个真实场景，我按「省多少时间」排了个序》 | [ai-frontend-scenarios.pdf](ai-frontend-scenarios.pdf) |
| `rules` | 前端 .cursorrules 完整配置（Vue3 + TS 中后台模板） | 《怎么让 AI 真正懂你的项目：一份前端 .cursorrules 该怎么写》 | [cursor-rules-config.pdf](cursor-rules-config.pdf) |
| `TS` | TS 类型补全实测记录（统计 + 避坑） | 《我让 AI 给一个 3 万行的前端项目补 TypeScript 类型，结果有点意外》 | [ts-type-completion.pdf](ts-type-completion.pdf) |
| `工作流` | AI 前端工作流图（阶段表 + 交接清单） | 《我的 AI 前端工作流：从需求评审到提测，哪几步交出去，哪几步必须自己来》 | [ai-workflow.pdf](ai-workflow.pdf) |
| `8工具` | 2026 前端 AI 工具表（8 工具 + 官网链接） | 《2026 前端 AI 工具清单：我实际在用的 8 个（附各自的使用场景）》 | [fe-ai-tools.pdf](fe-ai-tools.pdf) |

> 在公众号对话框发送上方加框的关键词（如「速查表」），即可自动获取下载链接。

## 怎么获取

1. **公众号关键词回复（推荐）**：微信搜「前端AI手记」关注后，在对话框发送关键词。
2. **GitHub 直接下载**：本仓库为公开仓库，点上方文件名即可在线预览 / 下载。
3. **国内加速下载（GitHub 打不开时用这个）**：下面是通过 jsDelivr CDN 加速的直链，国内网络可直接下载。

| 资料 | 国内加速直链 |
| --- | --- |
| 前端 AI 编程提示词速查表 | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/prompt-cheatsheet.pdf` |
| AI 代码审查 Checklist | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/code-review-checklist.pdf` |
| 4 组设计稿转码对照表 | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/design2code-compare.pdf` |
| 9 组报错问答实录 | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/error-debug-qa.pdf` |
| 12 场景提效评估表 | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/ai-frontend-scenarios.pdf` |
| 前端 .cursorrules 配置 | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/cursor-rules-config.pdf` |
| TS 类型补全实测记录 | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/ts-type-completion.pdf` |
| AI 前端工作流图 | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/ai-workflow.pdf` |
| 2026 前端 AI 工具表 | `https://cdn.jsdelivr.net/gh/zhongzht/fe-ai-cheatsheet@main/fe-ai-tools.pdf` |

> Markdown 源同样可加速：把上面链接末尾的 `.pdf` 换成 `.md` 即可。

## 仓库结构

```
fe-ai-cheatsheet/
├── README.md                       # 本说明
├── prompt-cheatsheet.pdf           # 提示词速查表
├── code-review-checklist.pdf       # 代码审查 Checklist
├── design2code-compare.pdf         # 4 组设计稿转码对照表
├── design2code-compare.md          # ↑ Markdown 源
├── error-debug-qa.pdf              # 9 组报错问答实录
├── error-debug-qa.md               # ↑ Markdown 源
├── ai-frontend-scenarios.pdf       # 12 场景提效评估表
├── ai-frontend-scenarios.md        # ↑ Markdown 源
├── cursor-rules-config.pdf         # 前端 .cursorrules 完整配置
├── cursor-rules-config.md          # ↑ Markdown 源（含使用说明）
├── ts-type-completion.pdf          # TS 类型补全实测记录
├── ts-type-completion.md           # ↑ Markdown 源
├── ai-workflow.pdf                 # AI 前端工作流图
├── ai-workflow.md                  # ↑ Markdown 源
├── fe-ai-tools.pdf                 # 2026 前端 AI 工具表
└── fe-ai-tools.md                  # ↑ Markdown 源
```

## 更新计划

仓库随推文持续更新。每发一篇带配套资料的新文章，会同步补充到仓库与上方清单。

## 关于作者

柯里，前端工程师，正在把 AI 变成真实的开发生产力。
只写自己在项目里跑通的东西——不搬运资讯，不做没用过的评测。

你用 AI 写代码遇到的问题，欢迎在公众号对话框直接发给我，很可能成为下一篇的选题。
