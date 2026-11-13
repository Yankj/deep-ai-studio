# Deep AI Studio

深度 AI 内容创作、行业洞察与复盘沉淀库。面向长期更新：先对齐一手信号，再按「道 / 法 / 术」分层剖析，最后把可复用的写作规范、发布规范和每期产出归档下来。

## 这个仓库是什么

不是信息搬运站，而是一套可迭代的内容工作室：

- **术**：把近期关键事实、时间线与一手信源快速对齐
- **法**：拆清传导路径、各方博弈与决策机制
- **道**：用第一性原理看产业结构、人才模型与商业本质

每期产出都按同一套规范打磨：从读者已经看到的现象切入，用总分结构抛出有抓手的核心判断，语言精简，收尾落到下一个可验证的观察点。若内容计划登陆抖音等平台，再额外走一遍合规校验。归档时统一使用**兼顾深度、犀利与可发布性的合规终稿**。

## 目录导航

```text
.
├── README.md                          # 仓库定位、框架与期数索引
├── guidelines/
│   ├── writing-playbook.md            # 写作与打磨规范
│   └── douyin-publishing-guide.md     # 抖音发布规范与风控复盘
└── issues/
    └── 2026-11-13-jensen-huang-exit/  # 第 001 期
        ├── README.md                  # 期数总览卡片
        ├── article-final.md           # 合规终稿
        ├── retrospective.md           # 全过程复盘
        └── cover-3x4.jpg              # 3:4 竖版封面
```

- 写作规范：[guidelines/writing-playbook.md](./guidelines/writing-playbook.md)
- 抖音发布与风控：[guidelines/douyin-publishing-guide.md](./guidelines/douyin-publishing-guide.md)

## 历史期数

| 期数 | 日期 | 主题 | 状态 | 归档 |
| :--- | :--- | :--- | :--- | :--- |
| 001 | 2026-11-13 | 英伟达创始人仓促退场与全球算力格局重洗 | 合规终稿已归档 | [issues/2026-11-13-jensen-huang-exit](./issues/2026-11-13-jensen-huang-exit/) |

## 如何新增一期

1. 先对齐一手信号与时间线，再按 [写作规范](./guidelines/writing-playbook.md) 起草，完成后做一遍发布前自检。
2. 在 `issues/YYYY-MM-DD-slug/` 下放入总览卡片、合规终稿、复盘，必要时附 3:4 封面。
3. 把该期加入上方索引表。
4. 若计划公开发布，对照 [抖音发布规范](./guidelines/douyin-publishing-guide.md) 做风控检查；仓库为公开仓库，不归档未脱敏的高风险原文。
