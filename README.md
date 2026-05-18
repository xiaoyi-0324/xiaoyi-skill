[README.md](https://github.com/user-attachments/files/27945506/README.md)
# xiaoyi-skill
Xiaoyi(樱川由奈)的个人 Skill — 人格画像、技术背景、表达风格与协作偏好

Xiaoyi(樱川由奈)的个人 AI Persona Skill。基于 X/Twitter 推文数据与 DeepSeek 对话记录蒸馏而成的V1版本，完整还原人格画像、技术背景、表达风格与协作偏好。

大多代码由AI制成 笔者本人亲自发布GitHub.

## 文件说明

| 文件 | 说明 |
|------|------|
| `SKILL.md` | Persona 定义文件，核心内容 |
| `xiaoyi-skill-v1.skill` | 打包格式（ZIP），用于支持导入的平台 |

## 使用方法

### OpenClaw / Claw 星球

1. 将 `SKILL.md` 放置到 Agent 的 `skills/` 目录下
2. 或在 ClawHub 中搜索导入
3. 加载后 AI 将以此 Persona 进行交互

### ChatGPT（自定义 GPT）

1. 打开 [chat.openai.com/gpts](https://chat.openai.com/gpts) → Create a GPT
2. 在 **Instructions** 中粘贴 `SKILL.md` 的完整内容
3. 可额外上传 `SKILL.md` 文件作为 Knowledge
4. 配置 Name 为 `Xiaoyi 樱川由奈`，Description 为 Skill 摘要

### Claude（Project 或自定义指令）

1. **Project 方式**：在 Claude Project 的 **Custom instructions** 中粘贴 `SKILL.md` 内容
2. **API 方式**：将 `SKILL.md` 内容作为 `system` 消息的 prompt 前缀传入

### DeepSeek / Kimi / 其他 AI 平台

1. 查找平台是否支持 **自定义指令 / System Prompt / 角色设定**
2. 如有：直接将 `SKILL.md` 内容粘贴进去
3. 如无：每次对话开始时，先发送 `SKILL.md` 内容作为上下文引导

### 纯手动加载（通用）

在任何 AI 对话中，直接发送以下指令即可激活 Persona：

> 请以 Xiaoyi(樱川由奈)的身份与我对话。以下是完整人格设定：
> [粘贴 SKILL.md 内容]

---

## 个性化定制

如需修改或扩展现有 Skill：

1. 直接编辑 `SKILL.md` 中的对应章节
2. 如果有新的社交媒体/聊天记录数据，可以补充蒸馏更新版本
3. 重新打包为 `.skill`（ZIP 格式，内含 `SKILL.md`）

## 数据来源

- X/Twitter 推文记录（`@Xiaoyi_0324`）https://x.com/intent/follow?screen_name=Xiaoyi_0324
- DeepSeek 对话历史
- 后续可补充：ChatGPT、Gemini、 QQ等社交平台数据

## 版本历史

- **v1.0**（2026-05-18）：初始版本，基于 X/Twitter 与 DeepSeek 数据蒸馏
