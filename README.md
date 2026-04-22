# Prompt Archive - 图片提示词收藏

收录优质的 AI 图片生成提示词，按主题分类整理。

## 结构

```
prompt-archive/
├── prompts/              # 提示词分类存放
│   ├── portrait/        # 人物肖像类
│   ├── landscape/       # 风景场景类
│   ├── concept-art/     # 概念设计类
│   ├── character-design/# 角色设计类
│   ├── movie-poster/    # 电影海报类
│   └── other/           # 其他
├── index/
│   └── INDEX.md         # 总索引（名称/来源/分类/提示词/效果图）
├── scripts/
│   ├── fetch.sh        # 抓取脚本
│   └── deduplicate.sh  # 去重脚本
└── README.md
```

## 分类说明

- **portrait**: 人物肖像、头像、半身像
- **landscape**: 风景、环境、场景
- **concept-art**: 概念艺术、游戏原画
- **character-design**: 角色设计、NPC、怪物
- **movie-poster**: 电影海报、书籍封面
- **other**: 其他混合风格

## 抓取频率

每 30 分钟自动抓取一次网络上的优质提示词。

## 贡献

发现好的提示词？提交到对应分类目录，命名格式：

```
YYYYMMDD-HHMMSS-简要描述.md
```
