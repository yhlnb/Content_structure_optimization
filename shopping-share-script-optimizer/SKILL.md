---
name: shopping-share-script-optimizer
description: Diagnose and rewrite Chinese shopping-share spoken scripts for Xiaohongshu-style good-item, outfit, gift, travel packing, home fragrance, and creator-gear videos. Use when optimizing 购物分享、好物分享、礼物推荐、穿搭购物、翻包开箱、拍摄设备分享口播稿, especially when preserving the user's natural male lifestyle creator voice while improving structure, concrete usage scenes, performance-informed details, and recordable final wording.
---

# Shopping Share Script Optimizer

## Core Workflow

Use this skill to diagnose and rewrite shopping-share spoken scripts in the user's natural style. Keep the tone like a real friend sharing recent purchases, not a sales pitch.

1. Classify the script type: outfit shopping, good-item/gift list, travel packing, creator gear, home/fragrance, or mixed shopping haul.
2. Extract the one-line theme and viewer gain.
3. Diagnose the script against the performance-informed checks below.
4. Preserve the user's stable voice: relaxed, practical, low-key aesthetic, specific daily scenes, and light personal judgment.
5. Strengthen every item with: why bought, when used, what problem it solves, and real sensory or usage feedback.
6. Remove or rewrite generic praise when it does not create a visible, usable, or memorable detail.
7. Add a clear ending payoff: most recommended, most surprising, best self-use, best gift, or highest-frequency item.
8. Output a diagnosis plus a recordable revised version unless the user asks for diagnosis only.

## Reference Routing

Read only the files needed for the current task:

- For the user's stable口播人格、语气、常用句式、审美词库, read `references/voice-profile.md`.
- For data-informed differences between `赞藏1000+`, `赞藏500-1000`, and `<500` samples, read `references/performance-patterns.md`.
- For diagnosis dimensions, rewrite steps, item templates, and ending templates, read `references/rewrite-framework.md`.

## Performance-Informed Checks

Always check whether the script includes:

- Real scenes: 通勤、旅行、健身、咖啡店、送礼、家里、季节变化、工作日、周末.
- Perceptible results: 能放什么、穿多久、喷多久、走多久、是否磨脚、是否黏腻、是否抗皱、是否显比例.
- Personal judgment: 为什么买、怎么用、为什么适合自己、是否会高频使用.
- Light life texture: small defects, small jokes, real hesitation, already-used feedback, friend/family context.
- Ending ranking: 最推荐、最惊喜、最适合自用、最适合送人、最高频.

## Default Output

Prefer Chinese output.

Use this compact shape when fitting:

```markdown
## 一句话判断

## 文案诊断
| 维度 | 当前表现 | 修改方向 |
|---|---|---|

## 需要保留的口播优势

## 需要加强的细节

## 可直接录制的改稿版本

## 自检
```

For a batch of scripts, compare tiers first, then list reusable patterns and priority fixes. For a single script, prioritize concrete line-level revisions over broad theory.
