<div align="center">

# 🎬 lark-attendance

## 问一句「我这月打了几次卡」，日期参数系统自己补齐
## Ask 'did I clock in this month?'—date params fill themselves in

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

这是一个考勤打卡查询技能，用来查询自己的考勤打卡记录。它把时间区间等默认参数按规则自动填充，并给出填充示例，用户不用记参数格式就能直接问。技能文档同时列出可用的 API 资源和用户任务（user_tasks）接口，以及对应的权限表，方便确认能查什么、需要什么授权。

### ✨ 能做什么

- 查询本人考勤打卡记录，支持指定时间范围
- 默认参数按规则自动填充，并附填充示例
- 内置权限表，明确调用前需要哪些授权
- 列出可用 API 资源与 user_tasks 接口
- 查询类只读操作，不改动任何考勤数据

### 📦 包含的技能

- `lark-attendance` —— 见 [`lark-attendance/SKILL.md`](lark-attendance/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/lark-attendance.git
cp -r lark-attendance/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A focused skill for reading your own attendance clock-in records. Default parameters such as date ranges are filled in automatically by documented rules, with worked filling examples, so you can just ask in plain language instead of memorizing parameter formats. The skill also lays out the available API resources, the user-task endpoints, and a permission table, so it is clear what can be queried and what authorization it needs.

### ✨ What it does

- Read your own clock-in / clock-out records, scoped by date range
- Auto-fill default parameters by documented rules, with worked examples
- Ships a permission table so required authorization is explicit
- Documents the available API resources and user-task endpoints
- Read-only by design—never modifies attendance data

### 📦 Skills included

- `lark-attendance` — [`lark-attendance/SKILL.md`](lark-attendance/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/lark-attendance.git
cp -r lark-attendance/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
