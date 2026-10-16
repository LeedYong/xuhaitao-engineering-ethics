# xuhaitao-engineering-ethics

Agent skill generated from *《工程伦理》* by 徐海涛（电子工业出版社，2020 年第 1 版）with [book-to-skill](https://github.com/virgiliojr94/book-to-skill).

工程伦理课程知识库 Skill：覆盖工程概论、四大伦理理论（功利论/义务论/契约论/美德论）、职业伦理规范、伦理困境分析方法、内外部社会责任、工程风险与环境伦理、全球化工程伦理，以及 10 个经典案例分析（京杭大运河、奥的斯电梯、N 射线、奔腾芯片、怒江水电站、松花江水污染、三聚氰胺、三星半导体、福岛核事故、港珠澳大桥）。

适用于：工程伦理课程学习、期末备考（单选/多选/阐述/分析题）、工程决策伦理分析、案例分析答题模板。

## 安装

在任意 Agent Skills 兼容的主机（GitHub Copilot CLI、Claude Code、Amp、OpenClaw 等）上运行：

```bash
npx skills add https://github.com/LeedYong/xuhaitao-engineering-ethics --skill xuhaitao-engineering-ethics
```

## 使用

- 问 `xuhaitao-engineering-ethics` → 加载核心框架
- 问 `xuhaitao-engineering-ethics 关于<主题>`（如"工程风险"、"超文化规范"）→ 定位并讲解相关章节
- 问 `ch05`、`ch08` 等 → 深入指定章节
- 问"有什么章节？" → 查看完整章节索引

## 文件清单

```
SKILL.md                      # 主文件：核心框架 + 章节/主题索引
chapters/
  ch01-engineering-overview.md        # 工程概论
  ch02-ethical-framework.md           # 道德框架（四大伦理理论）
  ch03-professional-codes.md          # 职业伦理规范
  ch04-ethical-dilemmas.md            # 伦理困境
  ch05-internal-social-responsibility.md  # 内部社会责任
  ch06-external-social-responsibility.md  # 外部社会责任
  ch07-globalization-ethics.md        # 全球化工程伦理
  ch08-case-analysis.md               # 工程伦理案例及分析（10案例）
glossary.md                   # 全部关键术语定义（含章节标注）
patterns.md                   # 分析方法与决策模式
cheatsheet.md                 # 期末速查：题型策略/四论速查/清单背诵/分析题模板
```

## 内容说明

- 本仓库全部内容为**综合提炼的知识摘要**（synthesized summaries），非教材原文复制。
- 章节文件按 book-to-skill 规范生成，保留作者的命名与框架，压缩为可直接检索/引用的知识点。
- 页码标注基于书内页码（第 1 章 P1–34 … 第 8 章 P199–237）。
- 如需原书内容，请购买正版教材：《工程伦理》，徐海涛主编，电子工业出版社，ISBN 978-7-121-36497-6。
