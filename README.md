# 海外工具选词与验证 Skill

协助判断海外 SEO 工具、小游戏或 AI 产品选题是否值得做，并将实时搜索证据整理成首版页面与两周验证计划。Skill 会区分观察、推断和假设；缺少可靠搜索量或 SERP 数据时不会编造数值。

## 安装

将本仓库的 `SKILL.md` 放入 Codex 技能目录：

```sh
mkdir -p ~/.codex/skills/validate-overseas-tool-idea
curl -fsSL https://raw.githubusercontent.com/glows/validate-overseas-tool-idea-skill/main/SKILL.md -o ~/.codex/skills/validate-overseas-tool-idea/SKILL.md
```

重新打开 Codex 会话后，可给出一个关键词、竞品网址或站点类型，让助手按 Skill 调查。实时调查需要可用的网络搜索工具；没有实时数据时，Skill 会明确标为「未验证」。

## 文件

- [`SKILL.md`](SKILL.md)：完整工作方法与回答格式。
