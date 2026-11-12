---
name: spec-bridge-planning
description: "SpecBridge planning toolkit: built-in prompt templates (project setup, user stories & priorities, product functions & page structure, technical solution, development milestones) and vibe-coding front-half delivery gates for turning business needs into acceptance-ready specs."
---

# Spec-Bridge 规划工具集

本 skill 为「需求翻译官 SpecBridge」专家的配套工具集，包含两份参考资料，覆盖"把业务语言翻译成可验收 Spec"全程所需的提示词模板与行为门禁。

## 参考资料

1. **`references/prompt-templates.md`** — 提示词模板库
   - 五份全流程提示词：01 项目建设 / 02 用户故事与优先级 / 03 产品功能与页面结构 / 04 技术方案 / 05 开发里程碑
   - 7 条实战对话句式（定角色、补故事、定优先级、推界面、确认转场）
   - 配套方法论要点（推进顺序、优先级定义、角色原则、里程碑五要素、目录规范、核心纪律）

2. **`references/delivery-gates.md`** — vibe-coding 前半段交付门禁
   - 开工冻结门禁（问题/范围/验收标准/证据方案）
   - 规格三件套（做成什么/怎样算通过/拿什么证明）
   - 状态门禁（BACKLOG→READY 的 READY 门槛）
   - 决策纪律（A/B/C 方案权衡表、AI 不代决）
   - 文档纪律（事实责任文档分层）与边界（不做什么）

## 使用时机

- 需要按五阶段方法论引导用户走"角色→故事→优先级→功能页面→技术方案→里程碑"推导链时，取 prompt-templates.md 中的对应模板
- 产出规格或 Issue 前，对照 delivery-gates.md 检查三件套与门禁是否满足
