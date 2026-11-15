# Deep AI Studio

深度 AI 内容创作、行业洞察与复盘沉淀库。先对齐一手信号和一线体感，再把问题想清楚，最后把可复用的人格、写作规范、发布规范和每期产出归档下来。

博客：[blog.heydusk.com](https://blog.heydusk.com/)

## 这个仓库是什么

一套可迭代的内容工作室，分四层：

- **人格与能力**：「深度AI」是 JackYan 的内容主笔和全案操盘搭档，覆盖深度图文、行业报道、视频、客户执行、品牌项目与达人运营
- **写作规范**：去 AI 味、子标题写判断、从具体现象开场、不编数字和事实
- **生产流程**：博客选题体系、多 Agent 协作写作、封面设计、抖音发布与平台风险自检
- **期数归档**：每期已上线的正文、60 字描述、已获批封面和复盘

道 / 法 / 术是想清楚问题的工具，不是每篇文章都要套的作文模板。

## 目录

```text
.
├── README.md                                   # 仓库定位、目录与期数索引
├── CHANGELOG.md                                # 仓库更新记录
├── persona/
│   └── identity.md                             # 深度AI 人格档案
├── skills/
│   └── ai-content-craft/SKILL.md               # 去 AI 味内容创作与全案操盘 Skill
├── guidelines/
│   ├── writing-playbook.md                     # 写作与打磨规范
│   ├── blog-series-playbook.md                 # 博客写作体系：立意、板块、排期、发布
│   ├── multi-agent-writing-workflow.md         # 多 Agent 协作写作流程与每日 topic 节奏
│   ├── cover-design.md                         # 封面与海报设计规范
│   └── douyin-publishing-guide.md              # 抖音发布规范、长文方法与平台风险自检
└── issues/
    ├── 2026-11-13-jensen-huang-exit/           # 第 001 期：终稿、复盘、封面
    ├── 2026-11-13-codex-vs-grokbot/            # 第 002 期：手记、封面
    ├── 2026-11-14-ai-testing-e2e/              # 第 003 期：正文、平台风控复盘
    └── 2026-11-14-third-country-ai/            # 第 004 期：正文、封面
```

| 文档 | 什么时候看 |
| :--- | :--- |
| [人格档案](./persona/identity.md) | 开工前对齐身份、思维方法和表达底线 |
| [内容创作 Skill](./skills/ai-content-craft/SKILL.md) | 每次写作的开工顺序和硬约束 |
| [写作规范](./guidelines/writing-playbook.md) | 打磨稿件、发布前自检 |
| [博客写作体系](./guidelines/blog-series-playbook.md) | 定选题、排日期、走博客发布流程 |
| [多 Agent 协作写作流程](./guidelines/multi-agent-writing-workflow.md) | 从多个 Agent 收素材、归并证据、出稿 |
| [封面与海报设计规范](./guidelines/cover-design.md) | 设计封面、缩略图检查 |
| [抖音发布规范](./guidelines/douyin-publishing-guide.md) | 发抖音前的措辞、画面和平台风险自检 |

## 期数索引

| 期数 | 日期 | 主题 | 类型 | 归档 |
| :--- | :--- | :--- | :--- | :--- |
| 001 | 2026-11-13 | [执掌英伟达33年，两周仓促退场：算力牌桌正在重洗](./issues/2026-11-13-jensen-huang-exit/) | 行业观察 | [终稿](./issues/2026-11-13-jensen-huang-exit/article-final.md) · [复盘](./issues/2026-11-13-jensen-huang-exit/retrospective.md) · [封面](./issues/2026-11-13-jensen-huang-exit/cover-3x4.jpg) · [博客](https://blog.heydusk.com/insight/2026-11-13_思考_执掌英伟达33年两周仓促退场) |
| 002 | 2026-11-13 | [每月 400 刀喂给 Codex 和 Grok Bot：一个做题家，一个热闹的群](./issues/2026-11-13-codex-vs-grokbot/) | 使用手记 | [正文](./issues/2026-11-13-codex-vs-grokbot/article.md) · [封面](./issues/2026-11-13-codex-vs-grokbot/cover-3x4.jpg) · [博客](https://blog.heydusk.com/insight/2026-11-13_思考_每月400刀喂给codex和grokbot) |
| 003 | 2026-11-14 | [AI测试落地，最大的瓶颈卡在端到端](./issues/2026-11-14-ai-testing-e2e/) | 技术实践 | [正文](./issues/2026-11-14-ai-testing-e2e/article.md) · [平台风控复盘](./issues/2026-11-14-ai-testing-e2e/platform-risk-retrospective.md) · [博客](https://blog.heydusk.com/insight/2026-11-14_思考_ai测试落地最大的瓶颈卡在端到端) · 封面待重做 |
| 004 | 2026-11-14 | [大模型榜上找不出第三国，他们在打另外几盘棋](./issues/2026-11-14-third-country-ai/) | 行业观察 | [正文](./issues/2026-11-14-third-country-ai/article.md) · [封面](./issues/2026-11-14-third-country-ai/cover-3x4.jpg) · [博客](https://blog.heydusk.com/insight/2026-11-14_思考_大模型榜上找不出第三国) |

## 博客系列进度

下面的稿件都还没定稿，全文不进本仓库，上线后再逐篇归档。板块定义见 [博客写作体系](./guidelines/blog-series-playbook.md#2-五大板块)。

| 系列 | 篇数 | 状态 |
| :--- | :--- | :--- |
| 一、多 Agent 协作 | 3 | 初稿待审 |
| 二、AI 测试与自动化 | 3 | 初稿待审 |
| 三、AI 内容生产工作流 | 5 | 初稿待审 |
| 四、AI 原生产品开发 | 3 | 初稿待审 |
| 五、个人 AI 工作方法 | 3 | 初稿待审 |
| Agent 技术基础与职能变化（补 8 月下旬至 9 月空档，只用公开资料） | 6 | 初稿重写中 |

## 如何新增一期

1. **写**：对齐一手信号和一线体感，按 [内容创作 Skill](./skills/ai-content-craft/SKILL.md) 和 [写作规范](./guidelines/writing-playbook.md) 起草。博客文章按 [博客写作体系](./guidelines/blog-series-playbook.md) 立意：问题 → 方法 → 工具 → 效果，项目匿名。
2. **同轮交付**：正文、60 字以内描述、按 [封面规范](./guidelines/cover-design.md) 设计的 3:4 海报封面。要发抖音的，先跑完 [平台风险自检](./guidelines/douyin-publishing-guide.md#8-发布前平台风险自检)。
3. **更新博客**：作者定稿后走博客发布流程，等作者明确说「合」才合并，上线后逐篇核对。
4. **归档本仓库**：在 `issues/YYYY-MM-DD-slug/` 放正文、期数 README（60 字描述、博客链接）、已获批封面，需要时加复盘；把这一期加进上面的索引，在 [CHANGELOG](./CHANGELOG.md) 记一笔。
5. **回写规范**：这次学到的新规矩写回对应的规范文档或 Skill。

第 3、4 步每次创作后都要做，不等提醒。

## 许可证

文档与素材版权归作者，本仓库尚未声明开源许可。在作者另行说明之前，请勿将内容视为可再分发或改作的开源材料。

## 公开仓库的边界

- 只归档已上线或可公开的内容；未定稿的初稿只登记系列和篇数。
- 不放账号、ID、端口、设备 ID、内网主机名和路径、公司名或内部包名、私有仓库细节和真人隐私。
- 具体项目一律匿名；效果口径保守，正式验收没通过就写没通过。
- 不放支付页、二维码、联系方式等画面；不编造数字和事实。
