# AI 产品拆解 Skill

从真实场景体验出发，逆向拆解 AI 产品的商业、用户、技术、模型和数据，形成有证据的产品评测、人机分工、Agent 分析与总架构图。

## 标准流程

1. 商业与市场
2. 场景与用户体验
3. 技术系统逆向拆解
4. 逐个拆解关键 Agent
5. 模型与成本
6. 基础数据与壁垒
7. 问题诊断与架构总结

每条结论区分页面事实、合理推断和尚未确认。未实测的能力不伪造评分；推导的提示词、工具接口和数据结构不当作产品真实内部实现。

## 在项目中使用

把本仓库中的 `SKILL.md`、`agents/`、`references/` 放到项目的 `.agents/skills/ai-product-teardown/` 下。

调用示例：

```text
使用 $ai-product-teardown，深度拆解 https://产品地址，输出评测、人机分工、Agent 分析和总架构图。
```

也可以提供截图、任务回放、实际成品和体验记录。

## 文件

- [SKILL.md](SKILL.md)：触发范围、七阶段流程和交付检查
- [证据与评测规范](references/evidence-and-evaluation.md)
- [Agent 深度拆解模板](references/agent-analysis.md)
- [报告模板](references/report-template.md)
- [界面配置](agents/openai.yaml)
