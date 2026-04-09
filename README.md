# my-skill
本仓库包含多个 skill，每个 skill 独立放在对应子目录下，用于自媒体内容撰写及排版。

## 目录结构
.
├── media-content-writer/
│   ├── SKILL.md
│   └── references
│       └── case-library
├── media-formatter/
│   ├── SKILL.md
│   └── references
│       └── formatting-guide
└── README.md

## 各 skill 说明

### 1. media-content-writer

- **功能简介**：自媒体内容撰写 Skill，专注于 AI、设计、产品与营销交叉领域的公众号、小红书、LinkedIn 内容生产。当用户提供选题、关键词、参考内容或方向，需要输出可供审阅和多轮打磨的文章正文时，触发此 Skill。覆盖五大内容栏目：《设计思考》《增长视角》《AI设计实战》《出海洞察》《行业点评》《事务所日常》。只要用户提到"写文章"、"出稿"、"公众号"、"小红书"、"内容"、"选题"、"爆款"、"标题"等关键词，或提供了一个主题希望变成内容，都应立即调用此 Skill。注意：本 Skill 只负责内容撰写，不输出 HTML 排版，排版请调用 media-formatter Skill。
- **使用方法**：
  1. 进入目录：`cd skill1_name`
  2. 安装依赖：`pip install -r requirements.txt`（如果有）
  3. 运行：`python skill1_main_file.ext`（根据实际入口文件）
  4. 其它配置/说明...

### 2. media-formatter

- **功能简介**：易点设计事务所公众号排版规范
- **使用方式**：
  1. 进入目录：`cd skill2_name`
  2. 安装依赖：...
  3. 运行：...
  4. 其它...

（依此类推）

## 关于引用/依赖

- 如果 skill 依赖外部 reference 文件或数据，说明下载/使用方式。
- 公共依赖可在根目录提供 `requirements.txt` 列出，或分别放各 skill 子目录内。

## 常见问题

- 如何添加新的 skill
- skill 之间是否有依赖关系
- 如何贡献 PR
- 联系方式

## License

本仓库遵循 XX License（如 MIT），详见 LICENSE 文件。
