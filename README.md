# 公众号历史条漫

一个用于创作微信公众号历史科普条漫的 Codex Skill。适合讲古代生活、普通人的处境，以及古装影视里的历史细节。

## 安装

将仓库克隆到 Codex 的个人 Skill 目录。如果你已安装本 Skill，可以直接使用。

```bash
git clone https://github.com/li-tiger/wechat-history-comics.git "${CODEX_HOME:-$HOME/.codex}/skills/wechat-history-comics"
```

在 Codex 中输入：

> 用 $wechat-history-comics 做一期公众号历史条漫，先给我选题。

## 创作流程

1. **选题。** 先给出 3–5 个候选题，每个附标题、看点和一个可画的开场。回复编号或直接指定题目。
2. **文案和分镜。** 选题确定后，输出标题、摘要、封面文案、逐屏画面、旁白、对白和参考资料。改稿后确认最新版。
3. **出图。** 你确认文案后，按分镜生成封面和正文图，检查文字、气泡和角色一致性，并按阅读顺序编号保存到当前工作区。此阶段需要可用的图片生成工具。

默认采用白底、黑线平涂和大气泡，正文为竖版。仓库内置白鹅阿满的角色设定图，也可以用你指定的角色和画风。

![白鹅阿满角色设定](assets/aman-goose.png)

完整流程见 [SKILL.md](SKILL.md)。
