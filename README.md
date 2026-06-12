# cursor-skills

个人 Cursor Agent Skills 私人仓库。

## 安装

将需要的 skill 文件夹复制到 Cursor skills 目录：

```bash
mkdir -p ~/.cursor/skills
cp -R pcba-teardown-analysis ~/.cursor/skills/
```

重启 Cursor 或新开 Agent 对话后即可使用。

## Skills

| Skill | 说明 |
|-------|------|
| [pcba-teardown-analysis](./pcba-teardown-analysis/) | PCBA 拆机方案分析（硬件工程师视角，面向产品经理） |

## 更新

```bash
cd ~/.cursor/skills/pcba-teardown-analysis
git pull   # 若该目录本身是 git submodule 或单独 clone
```

或重新从本仓库复制覆盖对应 skill 目录。
