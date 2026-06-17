# 这是个好事儿啊

一个基于公开材料与本地视频转写蒸馏出来的粗粝反鸡汤安慰 skill。

适用场景：
- 倒霉事、破防、被拒绝、丢脸、情感受挫、计划失败
- 不想听温柔陪伴，想听“拆穿式”“骂醒式”安慰

不适用场景：
- 自伤、自杀、暴力、急症
- 丧亲、重病、真实创伤现场
- 只想要冷分析，不想要角色风格化回应

## 目录结构

```text
zhe-shi-ge-hao-shi-er/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    ├── research/
    │   ├── 01-writings.md
    │   ├── 02-conversations.md
    │   ├── 03-expression-dna.md
    │   ├── 04-external-views.md
    │   ├── 05-decisions.md
    │   ├── 06-timeline.md
    │   ├── 07-peak-snippets.md
    │   ├── 08-style-notes.md
    │   └── 09-cross-video-patterns.md
    └── transcripts/
        ├── 01-zhe-shi-hao-shi.cleaned.txt
        ├── 02-fengge-yulu-30m.cleaned.txt
        └── 03-xiasanlu.cleaned.txt
```

## 怎么用

把整个文件夹放进你自己的 Codex skills 目录，例如：

```bash
~/.codex/skills/zhe-shi-ge-hao-shi-er/
```

最小可用文件是：
- `SKILL.md`

为了完整复现这个版本，建议一起保留：
- `agents/openai.yaml`
- `references/research/`
- `references/transcripts/`

## 这个仓库包含什么

公开内容：
- 可运行的 skill 本体
- 调研与蒸馏笔记
- 3 份经过清洗的本地视频转写文本

未公开内容：
- 原始视频
- 音频中间文件
- whisper 模型缓存

## 说明

这个项目追求的是：
- 学习表达动作、推进方式、常识拆法
- 做出可运行的风格化 skill

不是：
- 冒充真人
- 逐字逐句复刻
- 声称所有近似表达都来自原始逐字实录

仓库里的研究笔记已尽量区分：
- 清洗文本里能直接支撑的表达习惯
- 基于这些习惯推出来的高相似写法
