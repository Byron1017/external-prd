# 对外 PRD 文档 Skill

用于制作中文对外产品需求文档（PRD）。统一业务流程、功能需求和验收描述，采用仿宋、黑色文字、三级标题、自动目录、浅灰表头的简洁 Word 排版。

## 安装

将本仓库中的 `skills/external-prd` 整个目录复制到工具支持的 skill 目录。

Codex 默认位置：

- Windows：`%USERPROFILE%\.codex\skills\external-prd`
- macOS / Linux：`~/.codex/skills/external-prd`

如果配置了 `CODEX_HOME`，使用其下的 `skills/external-prd`。刷新或重新打开会话后，按客户端的技能加载方式使用。

## 使用示例

```text
请使用 $external-prd，读取附件需求，制作设备预约系统的对外 PRD，交付可编辑 Word 文档。
```

```text
请使用 $external-prd，整理现有 PRD 的章节、功能描述、多级目录和排版，保留已确认的业务规则。
```

可以同时提供客户需求、现有系统说明、截图、原型、确认记录和参考文档；有明确字体或版式要求时，在请求中说明。

## 文件说明

| 文件 | 用途 |
|---|---|
| `skills/external-prd/SKILL.md` | 技能入口及制作流程 |
| `references/content-structure.md` | 章节结构与功能写法 |
| `references/document-style.md` | 字体、字号、颜色、编号和目录规范 |
| `references/delivery-checklist.md` | 内容、Word 结构及渲染检查 |
| `assets/prd-outline.md` | 通用起稿大纲 |
| `agents/openai.yaml` | Codex 显示信息 |

表中 `references`、`assets`、`agents` 均位于 `skills/external-prd` 内。

本 skill 提供指令和排版规范，Word 生成与渲染由所用环境的文档工具完成。它不依赖特定商业系统或本地绝对路径。

## 发布与许可

可将此目录的内容作为 GitHub 仓库上传。项目采用 MIT 许可，见 LICENSE。
