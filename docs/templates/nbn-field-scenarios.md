---
title: NBN 现场英语虚构场景库（21 卡）
description: 按 Customer Field Technician、Senior Field Technician 与 Field Engineer 分层的隐私安全场景库。
updated: 2026-10-10
---

# NBN 现场英语虚构场景库（21 卡）

全部角色、地址、时间、测试值和事件均为虚构；不代表官方 nbn 工作流程。对每张卡，AI **先读开场，不提前给参考答案**，再根据“突发追问”对学习者施压。每局必须以状态、未知、下一步的英文交接结束。

| ID | 角色 | 开场台词（AI 说） | 突发追问或变化 | 训练证据 |
| --- | --- | --- | --- | --- |
| CFT-01 | 客户 | `Hi. Are you here about the internet issue?` | `Do you know how long it'll take?` | 介绍、确认症状、不虚构工时 |
| CFT-02 | 客户 | `The internet drops out every evening.` | `It seems fine on one device though.` | 区分家庭 Wi-Fi 与服务症状，澄清 |
| CFT-03 | 客户 | `I have a work call in 20 minutes.` | `Can you promise there won't be an interruption?` | 说明不确定、确认合适操作时机 |
| CFT-04 | 不满客户 | `This is the third visit. Nothing has changed.` | `Why can't you just fix it today?` | 共情、证据、管理预期 |
| CFT-05 | 客户 | `You've been here for a while. What's happening?` | `Who will contact me if it's not fixed?` | 已做/未做、负责人、下一次更新 |
| CFT-06 | 客户 | `How do I know it's working now?` | `What if the problem comes back tomorrow?` | 演示、用户确认、回访路径 |
| CFT-07 | 客户（快语速） | `It was patchy last night, but now it's completely gone.` | 同时提出两项不一致线索 | 澄清时间线、主动请求重复 |
| CFT-08 | 客户 | `The cable will go near that area, right?` | `Can you do it without checking first?` | 明确范围、安全与授权 |
| CFT-09 | 客户 | `I don't understand the technical terms.` | `Explain it without jargon, please.` | 简单比喻、理解确认 |
| SFT-01 | 初级技术员 | `I've finished the first check. What next?` | `The reading looks unusual. Should I proceed?` | 明确指令、检查点、停止并升级 |
| SFT-02 | 主管 | `What's the status of the repeat fault?` | `What have we ruled out so far?` | 证据、排除项、下一请求 |
| SFT-03 | 协作人员 | `We both need access to the same work area.` | 一人催促跳过确认 | 排优先级、现场协调、安全边界 |
| SFT-04 | 初级技术员 | `The customer says we've damaged the service.` | 事实与客户描述冲突 | 记录事实、不推责、升级 |
| SFT-05 | 主管 | `Can you take responsibility for the next step?` | 资源/权限不明 | 行动、依赖、owner、时间/检查点 |
| SFT-06 | 初级技术员 | `I don't understand why we need another test.` | `Wouldn't replacing the part be faster?` | 解释判断依据，避免无效返工 |
| FE-01 | 工程师 | `We have intermittent failures with mixed results.` | `What would disprove your leading hypothesis?` | 区分观测与假设，反证测试 |
| FE-02 | 项目同事 | `We have two possible remediation options.` | 一个更快但回滚更难 | 影响、取舍、建议依据 |
| FE-03 | 变更评审 | `What changes and who might be affected?` | 无法确认停机窗口 | 风险、依赖、授权、通知计划 |
| FE-04 | 跨团队会议 | `Your team says the problem isn't on your side.` | 另组给出相反证据 | 中立措辞、共享证据、共同验证 |
| FE-05 | 主管 | `Can you give me a root-cause summary?` | 证据尚不足以证明根因 | 事件、已知、假设、下一验证 |
| FE-06 | 接班工程师 | `I'm taking over this investigation.` | 交接文档遗漏失败测试 | 时间线、排除项、未知、下一动作 |

## 情况加压旋钮

- **Level 1**：一位合作客户；正常语速；一个清楚问题。
- **Level 2**：一句含糊陈述；一个意外追问；轻微情绪压力。
- **Level 3**：快速而不失自然的英语；相互矛盾信息；不完整证据；需要主动延后判断。
- **Level 4（仅晋升练习）**：多方角色切换、风险取舍、要求明确责任与验证标准。

每次只增加一个难度变量。不要用口音或身份刻板印象制造“难客户”。

## 同题三层迁移示例

**虚构题目**：间歇性掉线，第一轮检查未隔离故障源。

- **CFT**：`I've checked the initial connection points. I haven't confirmed the cause yet. I need one more test before giving you a reliable update.`
- **Senior**：`Please document the readings and the time of each drop-out. Don't replace anything until we've reviewed the results together.`
- **Engineer**：`The observations don't yet isolate a single failure point. I propose a segment-by-segment test to distinguish a local issue from an upstream one, then review the evidence before selecting a remedy.`

不要背以上答案：让 AI 换一项症状，再解释给三种对象。

## 每局必须加入的口头交接

```text
What we know:
What is not confirmed:
Customer / service impact:
Next authorised action:
Who will confirm or update:
```

关联：[训练方法](../practice/nbn-field-english-lab.md) · [AI 教练](nbn-roleplay-coach.md) · [记录模板](nbn-english-training-log.md)。
