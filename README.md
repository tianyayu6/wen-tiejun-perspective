# wen-tiejun-perspective

> 当你讨论三农、乡村振兴、县域经济、资本下乡时，普通 AI 很容易只给政策口号。
> This skill gives Codex a Wen Tiejun-inspired lens for rural revitalization, county economies, ecological transition, and dependency analysis.

[![Stars](https://img.shields.io/github/stars/tianyayu6/wen-tiejun-perspective?style=social)](https://github.com/tianyayu6/wen-tiejun-perspective/stargazers)
[![Forks](https://img.shields.io/github/forks/tianyayu6/wen-tiejun-perspective?style=social)](https://github.com/tianyayu6/wen-tiejun-perspective/network/members)
[![Issues](https://img.shields.io/github/issues/tianyayu6/wen-tiejun-perspective)](https://github.com/tianyayu6/wen-tiejun-perspective/issues)
[![Last commit](https://img.shields.io/github/last-commit/tianyayu6/wen-tiejun-perspective)](https://github.com/tianyayu6/wen-tiejun-perspective/commits/main)
[![License](https://img.shields.io/github/license/tianyayu6/wen-tiejun-perspective)](./LICENSE)

**[中文](#中文) | [English](#english)**

---

<a name="中文"></a>
## 中文

这个 skill 把温铁军公开课程、访谈、演讲和外部批评整理成一套可运行的思维框架。

用了之后，Codex 会先问：谁承担成本？谁获得收益？乡村是不是主体？资本是不是又把风险转嫁给了农民？  
它不是复读观点，而是用“危机-成本转嫁、去依附、乡土社会风险内部化、第三资产池、资源禀赋与村社理性”这五个镜片分析问题。

## 样例输出

用户问：

> 一个县想做 AI 智慧农业招商，靠谱不靠谱？

skill 会倾向于这样分析：

> 这不是一个简单的农业技术问题。你先看无人机服务谁，是服务村社和农户，还是服务外部资本圈地经营。技术本身没有错，但如果收益被平台拿走，风险留给农民，那就是把数字化包装成新的成本转嫁。先把土地、收益、数据和组织关系说清楚，再谈先进不先进。

## 一行安装

```bash
npx skills add tianyayu6/wen-tiejun-perspective
```

## 前置条件

- [ ] 已安装 Node.js 和 npm。验证：`node --version`、`npm --version`
- [ ] 可以运行 `npx`。验证：`npx --version`
- [ ] 你的 Codex / Agent 工具支持读取 Agent Skills。

## 使用示例

你可以直接这样说：

- “用温铁军的视角看一下这个乡村文旅项目。”
- “资本下乡这件事，温铁军会怎么拆？”
- “从三农和县域经济角度，分析一下返乡创业。”
- “粮食安全是不是只是产量问题？”

## 这个 skill 适合什么

- 三农、乡村振兴、县域经济、返乡创业
- 资本下乡、生态产业化、产业生态化
- 去依附、八次危机、全球化成本转嫁
- 粮食安全、大食物观、农村公共服务
- 判断一个乡村项目是不是只把政策词当包装

## 不适合什么

- 直接替代政策、法律、投资尽调
- 对 2025-2026 年最新动态凭记忆判断
- 把温铁军视角当成唯一正确答案
- 模仿本人语气发表未公开说过的原话

## 内容来源

主要基于：

- B 站课堂合集《中国经济闯关与乡村振兴》
- 《八次危机》课程说明
- 《去依附：中国化解第一次经济危机的真实经验》课程说明
- “资本过剩、乡村振兴与第三资产池”演讲实录
- 复旦中国研究院/观察者网 2024 访谈
- 中国人民大学、全球大学等机构资料
- 叶敬忠对“三农问题”概念边界的学术批评

完整研究笔记见 `references/research/`。

## 风险和限制

- 这不是温铁军本人观点，只是基于公开资料提炼的思维框架。
- 用户提供的 B 站课堂合集没有可用平台字幕，因此没有逐字转写。
- 很多研究来自温铁军团队，skill 会避免把团队成果全部归为个人原创。
- 遇到现实政策、地方项目、近期数据，必须先联网核验。

## Troubleshooting

| 问题 | 解决方法 |
|------|----------|
| `npx skills add` 找不到仓库 | 确认仓库地址是 `tianyayu6/wen-tiejun-perspective`，并检查网络。 |
| 安装后没有触发 | 重启 Codex / Agent 工具，确认它会扫描已安装 skills。 |
| 回答太宏观 | 让它落到“主体、资源、制度、收益分配、风险承担”五项检查。 |
| 涉及近期政策时回答不确定 | 要求它先查最新政策和地方执行材料，再做判断。 |

## 致谢

本 skill 使用 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 的人物 skill 结构生成。

---

<a name="english"></a>
## English

This skill gives Codex a Wen Tiejun-inspired analytical lens for rural China, rural revitalization, county-level economies, ecological transition, dependency, and crisis-driven development.

It is designed for structural analysis, not quote imitation.

## Install

```bash
npx skills add tianyayu6/wen-tiejun-perspective
```

## Example Prompts

- “Analyze this rural tourism project through Wen Tiejun’s lens.”
- “How should I think about capital entering rural areas?”
- “Is food security only about output?”
- “Use a dependency and county-economy perspective on this policy.”

## Best For

- Rural revitalization and county economies
- Capital entering rural areas
- Ecological industrialization
- Dependency and de-linking analysis
- Crisis, cost transfer, and rural risk absorption

## Limits

- This is not Wen Tiejun’s own statement.
- It is based on public courses, talks, interviews, and secondary critique.
- Recent policy or project analysis requires fresh fact checking.
- It should not replace legal, investment, or policy due diligence.

## Acknowledgements

Generated with the structure of [Nuwa Skill Maker](https://github.com/alchaincyf/nuwa-skill).
