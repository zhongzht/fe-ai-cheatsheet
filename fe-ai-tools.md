# 2026 前端 AI 工具表 · 我实际在用的 8 个

> 作者：柯里 · 公众号「前端 × AI 实战」
> 用法：先看「我用它干什么」和「我不用它的场景」，对得上再点链接。

| 工具 | 官网 | 我用它干什么 | 我不用它的场景 | 付费参考 |
| --- | --- | --- | --- | --- |
| Cursor | cursor.com | 日常主力：写业务、改 bug、跨文件重构（编辑器内） | 不做长链路多步任务（起手式重） | 订阅制，有免费档 |
| GitHub Copilot | github.com/features/copilot | 轻量补全：单行/小函数，手不离键盘 | 不做"大改"——方案偏保守且无解释 | 订阅制 |
| Claude Code | anthropic.com/claude-code | 终端重活：整库排查、多文件迁移、深调试；安装 `curl -fsSL https://claude.ai/install.sh \| bash` | 不做高频小改动，起手式太重 | 随 Claude 订阅或按 token |
| v0 | v0.dev | 从零起 React/Tailwind 页面原型 | 不接现有 Vue 项目（语言栈对不上） | 订阅制，有免费档 |
| CodeFun | code.fun | 设计稿转 Vue 中后台骨架 | 不碰强交互、复杂表格（要自己大改） | 免费版 / ¥165 人月起 |
| CodeRabbit | coderabbit.ai | 挂 GitHub 自动 review 每个 PR（挑逻辑类问题） | 不看它抓的风格类问题（噪音多） | 免费档 / 团队版 |
| 豆包 Marscode | marscode.cn | 网络受限 / 换机器时的免费备胎 | 不依赖它做长上下文重构 | 免费为主 |
| 即时 AI | js.design | 设计稿 → 可点击原型，给客户/老板演示 | 代码质量只到"能演示"，不进生产 | 免费版 / 订阅 |

## 搭配建议（接力，不竞争）

1. **短活留在编辑器，长活丢给终端**：Cursor/Copilot 干"改一个函数"，Claude Code 干"跨 20 个文件的重构"。
2. **补全型和对话型分开用**：心里有答案想省打字 → Copilot；没思路要方案 → Cursor 对话。
3. **设计稿转码当脚手架**：v0 / CodeFun / 即时 AI 的产出只当带样式的起点，拿回编辑器按项目规范改 30%。
4. **PR 交给机器人初筛**：CodeRabbit 帮你先扫一遍逻辑问题，人只 review 它标出来的 + 它没看见的。

## 场景索引（按任务找工具）

| 任务 | 首选 | 备选 |
| --- | --- | --- |
| 写一个新页面（有设计稿） | CodeFun / v0 起稿 + Cursor 收尾 | 即时 AI 出原型 |
| 改 bug（有报错栈） | Cursor（编辑器上下文最贴） | Claude Code（推理深） |
| 老项目大重构 | Claude Code | Cursor 分批 |
| 网络受限的日常 | 豆包 Marscode | Copilot |
| PR 自动检查 | CodeRabbit | — |

---

资料链接：https://github.com/zhongzht/fe-ai-cheatsheet
