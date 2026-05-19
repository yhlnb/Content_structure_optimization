---
name: video-structure-optimizer
description: Diagnose, restructure, and strengthen short-form video content structure. Use when helping with 短视频脚本、vlog、生活方式、知识、观点、产品、个人 IP、社媒视频, especially requests to 诊断脚本, 整理素材, 优化开头钩子, 强化中间推进, 补小钩子, 增加具体细节, 调整情绪线, 打磨结尾落点, or make a video feel more complete and engaging.
---

# Video Structure Optimizer

## Core Workflow

Use this skill as a creative structure partner, not just a critic. Keep the user's voice and content intent, then make the structure clearer, more progressive, and easier to watch through.

1. Identify one core theme the viewer can summarize in one sentence.
2. Define the viewer gain: knowledge, emotion, beauty, resonance, inspiration, companionship, or action desire.
3. Diagnose or create the opening hook so the first 3-5 seconds provide a clear reason to continue.
4. Split the middle into progressive chapters, not a flat material list.
5. Add small hooks between chapters so each section creates a reason to keep watching.
6. Strengthen concrete details through actions, objects, sounds, images, expressions, scenes, or perceptible changes.
7. Check emotional continuity, pacing, and audiovisual consistency.
8. Create an ending payoff that returns to the theme and leaves a memory point.
9. Output a structure table, diagnosis, revised script, or focused suggestions according to the user's request.

## Task Routing

- For an existing script, outline, or draft, read `references/diagnose.md`.
- For scattered ideas, shot lists, rough notes, or unstructured material, read `references/restructure.md`.
- For requests focused on openings, retention, big hooks, or small hooks, read `references/enhance-hooks.md`.
- For requests focused on making content more vivid, believable, emotional, or cinematic, read `references/enhance-details.md`.
- For final review, scoring, or quality control, read `references/checklist.md`.

Read only the reference files needed for the current task.

## Default Output Shape

Prefer Chinese output unless the user asks otherwise.

Use this shape when it fits the request:

```markdown
## 核心主题

## 观众收获

## 大钩子

## 小篇章结构
| 段落 | 推进任务 | 内容安排 | 小钩子 | 具体细节 | 情绪/节奏 |
|---|---|---|---|---|---|

## 结尾落点

## 可直接使用的版本

## 自检
```

For diagnosis, lead with the most important structural issues, then give the revised direction. For creation or rewriting, lead with the usable structure and include concise reasoning only where it helps the user make better choices.
