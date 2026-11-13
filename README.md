# Deep AI Studio

深度 AI 内容创作、行业洞察与复盘沉淀库。面向长期更新：先对齐一手信号和一线体感，再按「道 / 法 / 术」把问题想清楚，最后把可复用的人格、写作规范、发布规范和每期产出归档下来。道 / 法 / 术是思考工具，不是每篇文章都要套上的作文模板。

## 这个仓库是什么

不是信息搬运站，而是一套可迭代的内容工作室：

- **人格与能力**：以「深度AI」为 JackYan 的内容主笔和全案操盘搭档，覆盖深度图文、报道、视频、客户执行、品牌项目与达人运营
- **术**：把近期关键事实、时间线、使用体感与一手信源快速对齐
- **法**：拆清传导路径、各方博弈、产品机制与决策逻辑
- **道**：用第一性原理看产业结构、工具设计和商业本质

每期产出都按同一套规范打磨：从读者已经看到的现象或作者自己的具体体感切入，判断要有抓手，语言精简，收尾跟这一篇走，不套固定句式。若内容计划登陆抖音等平台，再额外走一遍合规校验。归档时统一使用**兼顾深度、犀利与可发布性的合规终稿或可公开手记**。

## 目录导航

```text
.
├── README.md                                # 仓库定位、框架与期数索引
├── persona/
│   └── identity.md                          # 深度AI 人格档案
├── skills/
│   └── ai-content-craft/SKILL.md            # 去 AI 味内容创作与全案操盘 Skill
├── guidelines/
│   ├── writing-playbook.md                  # 写作与打磨规范
│   └── douyin-publishing-guide.md           # 抖音发布规范与风控复盘
└── issues/
    ├── 2026-11-13-jensen-huang-exit/        # 第 001 期
    │   ├── README.md                        # 期数总览卡片
    │   ├── article-final.md                 # 合规终稿
    │   ├── retrospective.md                 # 全过程复盘
    │   └── cover-3x4.jpg                    # 3:4 竖版封面
    └── 2026-11-13-codex-vs-grokbot/         # 第 002 期
        └── article.md                       # 使用手记终稿
```

- 人格档案：[persona/identity.md](./persona/identity.md)
- 内容创作 Skill：[skills/ai-content-craft/SKILL.md](./skills/ai-content-craft/SKILL.md)
- 写作规范：[guidelines/writing-playbook.md](./guidelines/writing-playbook.md)
- 抖音发布与风控：[guidelines/douyin-publishing-guide.md](./guidelines/douyin-publishing-guide.md)

## 历史期数

| 期数 | 日期 | 主题 | 状态 | 归档 |
| :--- | :--- | :--- | :--- | :--- |
| 001 | 2026-11-13 | 英伟达创始人仓促退场与全球算力格局重洗 | 合规终稿已归档 | [issues/2026-11-13-jensen-huang-exit](./issues/2026-11-13-jensen-huang-exit/) |
| 002 | 2026-11-13 | 每月 400 刀喂给 Codex 和 Grok Bot：一个做题家，一个热闹的群 | 使用手记已归档 | [issues/2026-11-13-codex-vs-grokbot/article.md](./issues/2026-11-13-codex-vs-grokbot/article.md) |

## 如何新增一期

1. 先对齐一手信号、一线体感与时间线，再按 [写作规范](./guidelines/writing-playbook.md) 和 [内容创作 Skill](./skills/ai-content-craft/SKILL.md) 起草，完成后做一遍发布前自检，重点过「去 AI 味与反套路」。
2. 在 `issues/YYYY-MM-DD-slug/` 下放入正文；产业事件深稿再补总览卡片、复盘，必要时附 3:4 封面。
3. 把该期加入上方索引表。
4. 若计划公开发布，对照 [抖音发布规范](./guidelines/douyin-publishing-guide.md) 做风控检查；仓库为公开仓库，不归档未脱敏的高风险原文。
