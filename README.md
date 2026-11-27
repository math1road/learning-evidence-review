# 错题复盘｜learning-evidence-review

一个中文 AI Skill：用脱敏的成绩单、批改试卷或错题记录，先对账再诊断——核对原题与批改、按类别整理错题、每类配三倍新类题巩固，最后用延时独立重做验证是否真掌握。原分不改，证据与判断分开。

## 怎么装

这个技能只有一个 `SKILL.md` 文件，没有脚本、不联网，任何支持 SKILL.md 技能格式的 AI 工具都能用。

**第 1 步（所有工具通用）**：新建一个文件夹，名字必须是 `learning-evidence-review`，把本仓库的 `SKILL.md` 放进去。
> 注意：从 GitHub 点 “Download ZIP” 解压出来的文件夹会叫 `learning-evidence-review-main`，要把 `-main` 删掉。

**第 2 步：按你用的工具放到对应位置**

| 你用的工具 | 放到哪里 | 怎么调用 |
|---|---|---|
| Codex（CLI / App） | `~/.agents/skills/` | 新对话输入 `$learning-evidence-review 帮我复盘这份脱敏错题记录` |
| Cursor 等读 `~/.agents/skills/` 的工具 | `~/.agents/skills/` | 直接描述需求，或点名技能 |
| Claude Code | `~/.claude/skills/` | 输入 `/learning-evidence-review`，或直接描述需求 |
| Claude App / 网页版 | 把文件夹压缩成 zip，在设置的技能页上传 | 直接描述需求，Claude 会自动调用 |
| 其他支持 SKILL.md 的工具 | 该工具的技能目录 | 按该工具说明 |

`~` 指你的用户主目录（Mac：`/Users/你的用户名`；Windows：`C:\Users\你的用户名`）。放好后**新开一个对话**才会生效。

## 边界

仅处理获得授权的脱敏学习资料；不要提供姓名、学校、准考证号等不必要的身份信息。示例均为虚构数据。

Math1Road · 教数学的陈老师｜讲座《我是怎么用AI辅助孩子学习的》配套材料
