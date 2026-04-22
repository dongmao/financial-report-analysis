# financial-report-analysis

> 基于 **2734篇海豚研究研报** 提炼的财报分析 Skill，支持 WorkBuddy AI 助手使用。
>
> 涵盖 **13个核心方法论**、**9个行业框架**，覆盖互联网/电商/SaaS/半导体/新能源/消费等 **30+行业**。

---

## 🎯 项目简介

本项目是一套**系统化财报分析框架**，将机构研究员的实战分析逻辑提炼为可复用的方法论体系。

### 核心能力

- **交互式分析引擎**：不是一次性输出，而是分阶段与用户对话式推进
- **13个核心方法论**：预期差驱动、毛利微观拆解、资本周期、AI Capex ROI、第二曲线、SaaS增长阶梯、品牌力四维等
- **9个行业框架**：覆盖中概互联网/美股科技/硬科技/消费品牌/SaaS广告/宏观策略/金融/加密/新兴市场
- **主动式信息收集**：自动识别缺失数据并追问用户
- **多轮迭代优化**：通过交互不断完善分析深度

---

## 📁 项目结构

```
financial-report-analysis/
├── skill/                          # 核心 Skill 文件（WorkBuddy 格式）
│   ├── SKILL.md                    # 主文件：交互SOP + 13个方法论 + 触发词
│   ├── checklists/
│   │   ├── financial-checklist.md # 财务数据完整性检查清单
│   │   └── risk-signals.md        # 风险信号识别清单
│   ├── frameworks/                 # 9个行业分析框架
│   │   ├── README.md              # 框架总索引
│   │   ├── internet-content-platforms.md   # 中概互联网/电商/本地生活
│   │   ├── us-tech-giants.md      # 美股科技巨头
│   │   ├── hard-tech-manufacturing.md       # 硬科技/半导体/新能源车
│   │   ├── consumer-brands-retail.md        # 消费品牌/零售/餐饮酒店
│   │   ├── saas-adtech.md         # SaaS/广告技术/金融科技
│   │   ├── macro-strategy.md      # 宏观策略/光伏储能
│   │   ├── financial-business-services.md    # 金融/商业服务
│   │   ├── cutting-edge-assets.md # 前沿资产/加密
│   │   └── emerging-markets-education.md    # 新兴市场/教育
│   └── templates/
│       └── analysis-report-template.md      # 分析报告模板
│
├── references/                     # 原始研报方法论提炼笔记
│   ├── batch-A-tencent-ali.md      # 腾讯/阿里专题
│   ├── batch-B-internet-mid.md     # 互联网中坚专题
│   ├── batch-C-us-internet.md      # 美股互联网专题
│   ├── batch-D-ev.md               # 新能源车专题
│   ├── batch-E-semi-ai.md          # 半导体/AI基建专题
│   ├── batch-F-consumer.md         # 消费品牌专题
│   ├── batch-G-saas-fintech.md     # SaaS/金融科技专题
│   ├── batch-H-macro-market.md     # 宏观/市场专题
│   ├── batch-I-misc.md             # 杂项公司专题
│   ├── internet-core-methods.md     # 互联网核心方法论
│   ├── internet-2nd-methods.md     # 互联网进阶方法论
│   ├── us-internet-methods.md      # 美股互联网方法论
│   ├── ev-methods.md              # 新能源车方法论
│   └── consumer-saas-methods.md    # 消费/SaaS方法论
│
├── examples/                        # 分析案例（待补充）
├── LICENSE
└── README.md
```

---

## 🧠 13个核心方法论

| # | 方法论 | 核心内容 |
|---|--------|---------|
| 一 | 预期差驱动的分析主线 | 找市场预期与实际的偏差，作为叙事引擎 |
| 二 | 毛利微观拆解法 | 收入结构/成本结构/业务自身改善三维归因 |
| 三 | 业务生命周期定位与分阶段估值 | 导入期→成长期→成熟期→衰退期的分析策略 |
| 四 | 产业链传导逻辑 | 上中下游的量价传导和投资时钟 |
| 六 | 资本周期方法论 | 10阶段模型，资本开支/折旧比判断产能周期 |
| 七 | "剔除法"估算内生增速 | 已知增量 vs 剩余增速 |
| 八 | AI Capex→折旧→利润率传导链 | 云厂商Capex→芯片→代工→设备的ROI分析 |
| 九 | 预期差的"含金量"分类法 | 高/中/低含金量的判断标准 |
| 十 | 景气度与确定性的区分 | 景气驱动 vs 稳定成长 vs 周期成长的估值逻辑 |
| 十一 | 第二曲线判断框架 | 增长阶段→曲线质量→估值支撑 |
| 十二 | SaaS增长阶梯与估值锚定法 | 3阶段增速降档与估值切换陷阱 |
| 十三 | 品牌力四维评估法 | 定价/传导/复购/溢价来源稳定性 |
| 十四 | 观点先行的叙事结构 | 先说结论再用数据论证 |

---

## 📊 9个行业框架

| # | 框架 | 覆盖行业 | 代表公司 |
|---|------|---------|---------|
| 1 | `internet-content-platforms.md` | 中概互联网/电商/本地生活 | 腾讯/阿里/美团/拼多多/京东 |
| 2 | `us-tech-giants.md` | 美股科技巨头 | 苹果/微软/谷歌/亚马逊/Meta |
| 3 | `hard-tech-manufacturing.md` | 硬科技/半导体/新能源车 | 英伟达/台积电/比亚迪/宁德 |
| 4 | `consumer-brands-retail.md` | 消费品牌/零售/餐饮酒店 | 茅台/安踏/瑞幸/泡泡玛特 |
| 5 | `saas-adtech.md` | SaaS/广告技术 | AppLovin/Unity/Salesforce/Palantir |
| 6 | `macro-strategy.md` | 宏观策略/光伏储能 | 资本周期/景气度投资 |
| 7 | `financial-business-services.md` | 金融/商业服务 | 富途/顺丰/贝壳 |
| 8 | `cutting-edge-assets.md` | 前沿资产/加密 | Coinbase/MicroStrategy |
| 9 | `emerging-markets-education.md` | 新兴市场/教育 | Sea Limited/新东方 |

---

## 🚀 使用方式

### 方式一：在 WorkBuddy 中使用（推荐）

1. 将本项目克隆到 `~/.workbuddy/skills/financial-report-analysis/`
2. 在 WorkBuddy 中直接触发分析，例如：
   - "帮我分析一下腾讯的财报"
   - "拆解一下拼多多的补贴效率"
   - "分析特斯拉的第二曲线"

### 方式二：独立参考

- 直接阅读 `skill/SKILL.md` 了解分析方法论
- 按需查阅 `skill/frameworks/` 中的行业框架
- 使用 `skill/templates/analysis-report-template.md` 规范化输出

---

## 🔧 依赖工具

- **数据检索**：`neodata-financial-search` / `finance-data-retrieval`（WorkBuddy 插件）
- **AI 助手**：WorkBuddy（MiniMax-M2.7 powered）

---

## 📖 方法论来源

本框架的方法论提炼自 **海豚研究** 公众号大量实战研报，包括：

- 腾讯/阿里/美团/拼多多/京东等互联网巨头深度分析
- 美股科技（苹果/微软/谷歌/亚马逊/Meta）财报横向对比
- 半导体（英伟达/台积电/AMD）产能周期与 Capex 分析
- 新能源车（比亚迪/特斯拉/理想）量利关系研究
- 消费品牌（茅台/安踏/Lululemon）品牌力评估
- SaaS/广告技术（AppLovin/Unity/Palantir）增长阶梯模型
- 宏观策略（资本周期/景气度投资）方法论

---

## ⚠️ 免责声明

本框架仅供学习参考，不构成任何投资建议。投资有风险，决策需谨慎。

---

## 📄 License

MIT License - 详见 [LICENSE](LICENSE) 文件
