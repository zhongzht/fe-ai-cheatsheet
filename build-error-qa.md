# 构建报错问答实录

> 3 类前端构建 / 编译报错 × 该贴什么信息 × 3 个 AI 工具怎么答 · 附可复制提问模板  
> 作者：柯里 · 公众号「前端AI手记」

## 一、类型编译错误（vue-tsc / tsc）

- **典型**：`npm run build` 卡在 tsc，报 `Type 'X' is not assignable to type 'Y'` / `Property 'z' does not exist on type`
- **首选工具**：Cursor / Claude Code（会主动读 tsconfig、.d.ts、最近改动的接口定义）
- **必喂信息**：完整 tsc 报错 + 报错指向的接口 / 类型文件
- **常见根因**：后端接口改了字段、前端类型没同步；升级后类型收紧

## 二、依赖升级后构建崩

- **典型**：`npm i` 后 `vite build` 直接红，报 `Cannot find module 'xxx'` / peer dependency conflict
- **首选工具**：Claude Code（读 package.json 版本范围 + node_modules 里包的 changelog / 实际导出）
- **必喂信息**：package.json 相关依赖行 + 完整报错
- **常见根因**：大版本把默认导出改成具名导出；peer 依赖范围冲突

## 三、webpack / vite 配置类报错

- **典型**：`Module parse failed` / `No loader configured for` / `Invalid configuration object`
- **首选工具**：Cursor（圈出第一个 Error 块 + config 片段更高效）
- **必喂信息**：报错里第一个 Error 块 + webpack/vite.config 相关片段
- **常见根因**：缺 loader、配置项改名、路径写错

## 可复制提问模板

```
【环境】node vX / vite vX / vue-tsc vX
【完整报错】（贴完整 stack，不要只贴最后一行）
【相关文件】报错指向的类型 / 配置片段
【我试过】xxx
请：1) 定位根因 2) 给出最小改动方案 3) 说明为什么
```

---

资料链接：https://github.com/zhongzht/fe-ai-cheatsheet
