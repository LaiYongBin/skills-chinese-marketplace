# skills-chinese-marketplace

面向中文用户的 Claude Code 插件 Marketplace。

## 添加 Marketplace

```bash
/plugin marketplace add LaiYongBin/skills-chinese-marketplace
```

## 可用插件

### skills-chinese

将所有插件技能（skills）和命令（commands）的 `description` 字段汉化为中文。

**安装：**
```bash
/plugin install skills-chinese@skills-chinese-marketplace
```

**使用：**

| 命令 | 范围 |
|------|------|
| `/skills-chinese` | 仅翻译当前项目的 `.claude/skills` 和 `.claude/commands` |
| `/skills-chinese all` | 翻译全局插件 + 全局 skills + 当前项目 |
