# 贡献指南 🤝

感谢你对 Financial Product Workflow 的关注！欢迎贡献代码、PRD 模板、自运营设计或工具集成方案。

---

## 📋 行为准则

- **专业严谨**：金融产品设计需要专业态度
- **合规第一**：所有设计必须符合金融监管要求
- **用户导向**：以用户体验为核心
- **尊重他人**：保持友好、包容的讨论氛围

---

## 🚀 如何贡献

### 1. 报告问题 (Issues)

发现问题？请创建 Issue 并包含：
- 问题描述（清晰、具体）
- 工作流节点缺失或不当
- MBTI 匹配合理性讨论
- 合规风险点
- 工具集成问题

### 2. 提交代码 (Pull Requests)

贡献代码前请：
1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

### 3. 贡献 PRD 模板

欢迎分享 PRD 模板：
- 产品类型（基金/保险/理财等）
- 使用场景（拉新/激活/留存等）
- 自运营设计亮点
- 合规检查清单

### 4. 工具集成方案

贡献工具集成脚本：
- Jira/Confluence API 集成
- 原型工具 API 集成（Figma/墨刀）
- 数据工具 API 集成（神策/GrowingIO）
- 降级方案（无 API 时的处理）

---

## 📝 代码风格

### 提示词模板

```markdown
【角色定义】
你是一位 [专家角色]，擅长 [核心能力]。

【STAR 背景】
- 情境 (Situation)：[具体业务场景]
- 任务 (Task)：[核心任务]
- 行动 (Action)：[分析框架/方法论]
- 结果 (Result)：[预期目标]

【合规约束】
- 所有输出需符合金融产品销售合规要求
- 不得出现"保本""稳赚""预期收益"等违规表述
- 风险提示必须完整

【输入】
- [具体输入信息]

【输出要求】
- [格式要求]
- [质量标准]
- [交付物清单]
```

### 脚本规范

- Python 脚本遵循 PEP 8
- 添加必要的注释和文档字符串
- 错误处理完善
- 支持降级方案（API 不可用时的处理）

---

## 🔧 开发环境

### 前置要求

- OpenClaw v1.0+
- Python 3.8+
- Git

### 本地测试

```bash
# 克隆仓库
git clone https://github.com/lj22503/financial-product-workflow.git

# 进入项目目录
cd financial-product-workflow

# 在 OpenClaw 中测试技能
# 使用 /clawhub install local 命令安装本地技能
```

---

## ⚠️ 合规要求

**所有贡献必须遵守：**

- ❌ 不得推荐具体产品
- ❌ 不得承诺收益/保本
- ❌ 不得使用"稳赚""必涨""预期收益"等违规表述
- ✅ 必须包含风险提示
- ✅ 符合金融产品销售管理办法
- ✅ 符合广告法要求

---

## 📐 工作流节点说明

### 战略层（2 人）

| 角色 | MBTI | 职责 |
|------|------|------|
| 内部战略 | INTJ | 产品资源梳理、技术能力评估、合规能力评估 |
| 外部战略 | ENFJ | 渠道资源梳理、合作伙伴对接、监管政策跟踪 |

### 执行层（6 节点）

| 节点 | MBTI | 职责 |
|------|------|------|
| 需求分析 | INTP | 市场调研、竞品分析、用户访谈、需求优先级 |
| 产品设计 | ENFP | 功能设计、流程设计、原型设计、PRD 文档、自运营设计 |
| 技术评审 | ISTJ | 技术方案、工作量评估、风险评估、排期计划 |
| 开发跟进 | ENTJ | 需求交底、进度跟踪、问题协调、变更管理 |
| 测试验收 | ISFJ | 功能测试、合规测试、性能测试、UAT 验收 |
| 上线运营 | INFJ | 上线发布、数据监控、用户反馈、迭代优化 |

---

## 📖 资源

- [SKILL.md](SKILL.md) - 技能说明文档
- [STAR 框架](references/star-framework.md) - STAR+ 合规前置框架详解
- [自运营设计](references/self-operation-design.md) - 自运营设计指南
- [工具集成](references/tool-integration.md) - 工具集成指南
- [OpenClaw 文档](https://docs.openclaw.ai) - OpenClaw 官方文档

---

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)。贡献代码即表示你同意将贡献内容以 MIT 许可证发布。

---

## 🙏 致谢

感谢所有为本项目做出贡献的开发者！

**特别感谢：**
- 金融产品设计师
- 合规审核者
- 工具集成贡献者

---

## 📬 联系方式

- GitHub Issues: [提交问题](https://github.com/lj22503/financial-product-workflow/issues)
- 邮箱：[联系作者](mailto:your-email@example.com)
