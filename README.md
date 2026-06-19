# 解决方案架构师/售前顾问超级工作台 / Solution Architect & Presales Consultant Super Workbench

> **Author**: yinjianheng | **Version**: 1.1.0 | **Date**: 2026-06-16

## 一句话介绍

**解决方案架构师/售前顾问超级工作台** —— 面向解决方案架构师、售前顾问、方案专家、企业架构师的全栈自动化技能。一份 Skill，覆盖从客户材料分析到投标材料包交付的全链路。

## 核心能力

| 阶段 | 能力 | 输出物 |
|------|------|--------|
| 需求理解 | SPIN 需求挖掘、客户材料智能分析 | 结构化需求分析报告 |
| 调研会议 | 议程生成、纪要标准化、应答策略 | 会议纪要、预判应答手册 |
| 框架方案 | HLD 高层设计、架构方案 | 框架方案文档（12章标准） |
| 蓝图设计 | LLD 详细设计、功能/数据/集成 | 蓝图方案文档（10章标准） |
| 图表工场 | 13 类专业图（C4/DFD/BPMN等） | .drawio 源文件 + .png 预览 |
| PPT 工场 | 5 类汇报 PPT、6 配色方案 | .pptx 演示文稿 |
| 合同支持 | SOW、RFP 响应、投标包 | SOW 文档、投标材料 |

## 方法论文撑

- **C4 模型** — 系统上下文图 → 容器图 → 组件图，支持"地图式缩放"哲学
- **4+1 视图** — 逻辑/开发/进程/物理/场景
- **TOGAF 4A + ADM 9阶段** — 业务→应用→数据→技术，完整企业架构生命周期
- **ArchiMate 3.2** — The Open Group 企业架构建模标准，六层建模体系 + 14种标准 Viewpoints
- **Wardley Mapping** — 战略决策框架，价值链四阶段演变（Genesis → Custom → Product → Commodity）
- **FinOps** — 云财务管理框架，三阶段循环（Inform → Optimize → Operate）+ 10大最佳实践
- **零信任安全架构** — "永不信任，始终验证"安全设计原则
- **SPIN 需求挖掘法**
- **ADR 架构决策记录**
- **DFD Level 0-3 多层级数据流图**
- **BPMN 轻量版**

## 快速安装

```bash
cp -r ~/Desktop/sa-pro-workbench ~/.claude/skills/sa-pro-workbench
```

## 触发方式

直接说需求即可，支持 40+ 中文别名和 10+ 英文别名，覆盖：
解决方案架构师、售前、方案专家、SA、技术顾问、企业架构师、presales、solution architect...

## 依赖

- **必须**: 无（核心能力不依赖外部工具）
- **强烈建议**: draw.io 桌面版（图表编辑）
- **PPT**: Node.js + pptxgenjs 或 python-pptx

## 文件结构

```
sa-pro-workbench/
├── SKILL.md                          # 核心技能文件（1516行/~80KB）
├── _meta.json                        # 元数据
├── README.md                         # 本文件
└── references/
    └── drawio-xml-templates.md       # Draw.io XML 模板参考
```

## 版权声明

Copyright © 2026 **yinjianheng（殷健恒）**. All rights reserved.

本 Skill（sa-pro-workbench）为 **yinjianheng（殷健恒）** 独立原创作品，受《中华人民共和国著作权法》及国际版权条约保护。

- ✅ **允许**：个人学习、研究、非商业项目使用
- ❌ **禁止**：未经书面授权的商业用途（包括但不限于转售、捆绑销售、商业培训、SaaS化服务、企业内部分发）
- 📧 **商业授权**：yinjianheng@foxmail.com | WeChat: YJH-yinjianheng

**侵权必究**：已委托北京市盈科律师事务所定期扫描 Skill 市场，一经发现侵权行为将依法追究法律责任。

## 免责声明

1. **一般条款**：本 Skill 按"现状"提供，作者不保证其完整性、准确性或适用于特定用途。使用本 Skill 产生的任何后果由使用者自行承担。
2. **非官方背书**：作者与 The Open Group、Gartner、FinOps Foundation、Simon Brown、Simon Wardley 等组织或个人无任何隶属或背书关系。
3. **AI 生成内容**：本 Skill 是 AI 辅助工具，其输出内容可能存在偏差或错误。使用者应自行审查验证所有输出，不应将其视为专业法律、财务或技术建议。
4. **第三方内容**：本 Skill 引用的第三方框架、方法论、工具和标准（如 TOGAF、C4 Model、ArchiMate、Gartner 报告等）的版权归各自权利人所有。引用行为不构成作者与第三方权利人之间的任何关联或背书关系。
