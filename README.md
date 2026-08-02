# Mao Zedong Perspective Skill / 毛泽东视角 Skill

一个基于公开史料提炼的人物视角 Skill，用于战略判断、矛盾分析、调查研究、组织反馈和弱者竞争。

它不是毛泽东的“数字复活”，也不代表本人或历史定论。它提取的是公开材料中反复出现的思维框架，并将严重历史失败、伦理约束和现代迁移边界写入运行规则。

## 主要内容

- 6 个核心心智模型
- 10 条决策启发式
- 可执行的事实调查与反证协议
- 表达 DNA、思想谱系和历史时间线
- 对反右、大跃进、文化大革命、个人崇拜等的失效分析
- 史料版本说明，包括《毛泽东选集》第五卷的特殊版本边界

## 安装

### Codex

将整个仓库克隆或复制到：

```text
~/.codex/skills/mao-zedong-perspective/
```

Windows：

```text
%USERPROFILE%\.codex\skills\mao-zedong-perspective\
```

重新打开 Codex 或新建任务后即可调用。

### 其他 Agent Skills 运行环境

将仓库放入对应运行环境的 Skills 目录。不同产品的自动触发和工具能力可能不同，请以其文档为准。

## 调用示例

- `用毛泽东视角分析这个问题`
- `毛泽东会怎么看这件事？`
- `按毛主席的思路分析`
- `用毛选的方法拆解这个战略`
- `切换到毛泽东模式`

单独提到“主要矛盾”或“群众路线”不会自动触发，以减少误调用。

## 目录

```text
SKILL.md
references/
  research/       六维研究记录
  sources/        来源与版本清单
  synthesis.md    框架提炼稿
scripts/
  merge_research.py
  quality_check.py
```

## 验证

```bash
python3 scripts/quality_check.py SKILL.md
```

当前版本通过 6/6 自动检查，并完成已知立场、现代边缘问题、表达风格与历史伤害专项测试。

## 资料与版权说明

- 本仓库不收录《毛泽东选集》或其他书籍全文。
- 研究目录保存摘要、分析、短引语、公开链接和版本说明。
- 引用原始材料时，请根据 `references/sources/SOURCE-MANIFEST.md` 回到可靠版本复核。
- 第五卷使用 1977 年版和公开镜像辅助定位，不与现行官方 1—4 卷作无差别处理。

## 生成与归属

本 Skill 基于 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 的工作流、模板与工具脚本生成，并经过人工流程式校验。女娲项目创建者：[花叔（Huashu）](https://x.com/AlchainHust)。

女娲项目采用 MIT License，原版权声明为 `Copyright (c) 2026 Huashu (花叔)`。本仓库完整保留其版权声明与许可文本，详见 [第三方许可说明](THIRD_PARTY_NOTICES.md) 和 [女娲 MIT 原许可证](LICENSES/nuwa-skill-MIT.txt)。本仓库根目录的 `LICENSE` 适用于本仓库新增内容，不替代或取消女娲项目的原许可证。

## License

[MIT](LICENSE)
