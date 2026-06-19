# Career Counselor / 职业规划师

> 一个面向应届毕业生的职业规划 AI 技能包。基于 OpenClaw 平台运行，可在 SkillHub 上安装使用。

## 它能做什么

- **从零规划**：不知道学完出来干什么 → 帮你找到方向
- **Offer 对比**：手里有几个 offer 在纠结 → 帮你算清楚选哪个
- **方向验证**：已经有想法但怕不靠谱 → 帮你验证可行性
- **情绪疏导**：焦虑迷茫、怕选错 → 先陪你理清楚再给路

## 核心设计

### 九大评估维度

院校层次、学历、专业细分、绩点、项目经历、实习经历、家庭条件、性格特质、城市偏好。九个维度交叉分析，给出真正针对个人的建议——不是套模板。

### 双模式咨询

- **轻咨询模式**：3 轮交互内出建议，适合快速判断
- **深度报告模式**：覆盖完整的 4 步协议（情绪承接→自我认知→信息评估→输出），输出包含 AI 替代性分析、前瞻预测、容错预案的完整规划报告

### 安全护栏

4 层机制：违法灰产拦截 → 高风险强警告 → 认知纠偏 → 利益保护。确保不推荐违法、不坑穷学生、不推追高方式。

## Quick Start

```bash
# 安装 skill
skillhub install career-counselor

# 或从本地 .skill 包安装
skillhub install career-counselor.skill
```

## 文件结构

```
career-counselor/
├── SKILL.md              # 技能核心定义（404行，完整 Agentic Protocol）
├── references/            # 引用文件（提问库、输出格式、行业数据、城市选择等）
│   ├── anti-patterns.md
│   ├── city-selection.md
│   ├── day-in-the-life.md
│   ├── emerging-roles.md
│   ├── fallback-matrix.md
│   ├── faq.md
│   ├── industry-data.md
│   ├── interaction-questions.md
│   ├── interaction-protocol.md
│   ├── job-hunt-toolkit.md
│   ├── offer-comparison.md
│   ├── onboarding-survival.md
│   ├── output-format.md
│   ├── parent-negotiation.md
│   ├── safety-and-evolution.md
│   ├── self-assessment.md
│   ├── special-groups.md
│   └── trend-forecast.md
├── assets/               # 资源文件
├── scripts/              # 辅助脚本
├── career-counselor.skill # 构建产物（发布到 SkillHub 的 .skill 包）
├── LICENSE
├── .gitignore
└── README.md
```

## 许可证

MIT License
