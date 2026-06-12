# PCBA 拆机分析 Skill — 安装说明

## 1. 解压

将 `pcba-teardown-analysis` 文件夹放到：

```
~/.cursor/skills/pcba-teardown-analysis/
```

macOS / Linux 终端示例：

```bash
mkdir -p ~/.cursor/skills
unzip pcba-teardown-analysis-skill.zip -d ~/.cursor/skills/
```

若解压后多了一层目录，确保最终路径为：

`~/.cursor/skills/pcba-teardown-analysis/SKILL.md`

Windows 路径示例：

`C:\Users\你的用户名\.cursor\skills\pcba-teardown-analysis\`

## 2. 使用

1. 重启 Cursor，或新开一个 Agent 对话
2. 发送 PCBA / 拆机照片，Skill 会自动启用
3. 也可在对话中手动输入：`@pcba-teardown-analysis`

## 3. 首次使用注意

Agent 会先追问两件事（需回复后才会分析）：

- 背面照片（或回复「没有背面」）
- 产品信息：什么产品、是否主板、是否有其他小板

## 4. 更新

用新版本 zip 覆盖 `~/.cursor/skills/pcba-teardown-analysis/` 即可。
