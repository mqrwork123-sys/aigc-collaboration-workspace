# AIGC备课内容

本仓库按内容用途分区管理，存放 AIGC 课程、Codex 技能、创作项目和归档文件。

## 目录结构

```text
.
├── aigc-course/                  # AIGC 影像课程
│   ├── aigc-course-2.0.html     # 12 节影像创作课方案
│   ├── index-课程定位增强版-v2.html
│   ├── minutes/                  # 课程会议逐字稿
│   ├── draft_9684b8e8_folder/   # 课程路线图与可编辑源文件
│   ├── docs/                    # 课程会议与说明文档
│   └── media/
│       ├── logos/               # AI 平台、工具和品牌标识
│       └── pics/                # 课程照片、案例图和插图
├── skills/
│   └── performance-scoring/     # 内容运营绩效评分 Skill
│       ├── SKILL.md
│       ├── USAGE.md
│       └── agents/openai.yaml
└── archives/                     # 历史打包文件，不作为日常编辑入口
```

## 维护约定

- 课程网页保留在 `aigc-course/` 根目录，便于直接预览。
- 课程路线图、会议逐字稿等源资料随课程目录集中维护。
- 新增图片按类型放入 `media/logos/` 或 `media/pics/`，不再平铺在课程目录。
- 每个 Skill 使用独立目录，并将入口文件命名为 `SKILL.md`。
- 可编辑源文件与历史压缩包分开管理，避免把归档包当成最新版本。
