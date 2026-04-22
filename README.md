# Prompt Archive - 图片提示词收藏

收录优质的 AI 图片生成提示词，按主题分类整理。

## 结构

```
prompt-archive/
├── prompts/              # 正式收录提示词
│   ├── portrait/        # 人物肖像类
│   ├── landscape/       # 风景场景类
│   ├── concept-art/     # 概念设计类
│   ├── character-design/# 角色设计类
│   ├── movie-poster/    # 电影海报类
│   └── other/           # 其他
├── review/              # 待评审提示词
├── index/
│   ├── INDEX.md         # 总索引（按分类排列）
│   └── REVIEW_INDEX.md  # 评审区索引
└── README.md
```

## 分类说明

- **portrait**: 人物肖像、头像、半身像
- **landscape**: 风景、环境、场景
- **concept-art**: 概念艺术、游戏原画
- **character-design**: 角色设计、NPC、怪物
- **movie-poster**: 电影海报、书籍封面
- **other**: 其他混合风格

## 收录流程

```
定时任务抓取 → review/ 待评审 → 你确认 → 移到 prompts/ 正式收录
```

## 命名格式

```
prompts/分类/名称-YYYYMMDD.md
review/名称-YYYYMMDD.md
```

**格式说明**：名称在前，日期在后，精确到年月日。

## 收录标准

1. ✅ 有**完整逐字**的提示词原文
2. ✅ 有明确的**作者**信息
3. ✅ 有**原始发布链接**
4. ✅ 有**效果图**
5. ✅ 提示词质量高，风格独特

---

*索引由定时任务自动维护*
