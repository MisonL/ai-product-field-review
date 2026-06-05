# AI Product Field Review

AI Product Field Review 是一个 Codex 插件，用于审查 AI 产品、Agent 方案和企业工作流自动化计划。它把产品定位、真实用户证据、工作流适配、默认值代价、指标漂移、组织节奏和发布叙事放在同一个审查框架里，帮助团队在 PRD、发布计划、共创反馈或复盘阶段发现隐藏风险。

这套审查协议最初来自一份 105 页、约 7.5 万字长文复盘的抽象提炼；这里保留的是可迁移的判断框架，而不是原始叙事本身。

## 适用场景

- 审查 AI 产品 PRD、路线图、需求文档和发布计划。
- 评估 Agent、AI 助手、AI 工作台、AI 原生入口和工作流自动化方案。
- 判断 AI 功能为什么有曝光和点击，但留存、信任或付费意愿弱。
- 把用户访谈、客户共创、内测反馈和销售反馈整理成产品判断。
- 检查 Demo、销售话术、发布稿是否超过当前交付边界。
- 做 AI 产品 pre-mortem、postmortem 或竞品策略审查。

## 安装

### 从 GitHub 安装

```bash
codex plugin marketplace add https://github.com/MisonL/ai-product-field-review
codex plugin add ai-product-field-review@ai-product-field-review
```

`@ai-product-field-review` 是本仓库 marketplace 的名称，来自 `.agents/plugins/marketplace.json`。

### 本地开发安装

```bash
codex plugin marketplace add /path/to/ai-product-field-review
codex plugin add ai-product-field-review@ai-product-field-review
```

安装后建议新开一个 Codex 线程，让技能元数据和正文稳定加载。

## 使用示例

```text
审查这份 AI 产品 PRD 的隐藏风险。
```

```text
检查这个 Agent 方案是否适配真实工作流。
```

```text
按用户证据审计我们的发布计划。
```

## 输出重点

插件会优先要求 Codex 基于用户提供的材料、日志、数据、访谈或可复现实验做判断，而不是用产品直觉补空。典型输出包括：

- 结论：推进、收窄、重定位、延后发布或停止。
- 关键证据：来自材料或真实行为的事实。
- 主风险：定位、工作流、权限、失败恢复、默认值、指标和叙事债。
- 用户证据质量：共创偏差、真实承诺、最薄弱证据。
- 建议改动：最小但关键的产品改动和验证实验。

## 隐私与来源说明

本插件提供的是可迁移的 AI 产品审查协议，不包含私有代码、密钥、客户数据、内部人名或不可公开的公司细节。使用时请不要把未脱敏的用户数据、合同、凭证或内部敏感材料粘贴到不受信任的运行环境。

## 许可证

MIT
