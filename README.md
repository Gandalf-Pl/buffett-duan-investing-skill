# buffett-duan-investing

一个 Claude Code Skill：用巴菲特与段永平的价值投资框架分析公司 / 股票 / 投资决策。

## 框架概要

核心公理：**买股票就是买公司**（格雷厄姆 → 巴菲特 → 段永平）。

三个过滤器，重要性依次递减：

1. **right business**（商业模式：差异化、定价权、资本需求、毛利结构）
2. **right people**（企业文化与管理层：诚信、热爱生意还是钱、纠错能力）
3. **right price**（未来现金流折现；安全边际 = 你有多懂，不是有多便宜）

外加一张一票否决清单（Stop Doing List）：不懂不做、不杠杆不做空、不诚信不碰、无差异化不碰、需持续大额资本开支维持地位的不碰……

输出为固定九段式：生意本质 → 能力圈判定 → 商业模式 → 企业文化 → 护城河变化方向 → 估值（先估值再看价）→ 机会成本 → 否决清单检查 → 结论与仓位建议。

## 安装

```bash
# 个人级（所有项目可用）
mkdir -p ~/.claude/skills/buffett-duan-investing
cp SKILL.md ~/.claude/skills/buffett-duan-investing/

# 或项目级
mkdir -p your-project/.claude/skills/buffett-duan-investing
cp SKILL.md your-project/.claude/skills/buffett-duan-investing/
```

## 使用

在 Claude Code 中直接说：「用巴菲特和段永平的框架分析一下 XX 公司」，或 `/buffett-duan-investing`。

## 语料来源

框架提炼自 [gengjiawen/buffett-chinese](https://github.com/gengjiawen/buffett-chinese)（34 篇巴菲特演讲/访谈 + 段永平讲话的中文实录）。
