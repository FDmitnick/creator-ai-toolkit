# Creator AI Toolkit｜自媒体 AI 工具箱

面向普通内容创作者的 AI 提示词、工作流与实用模板合集。

不要求安装 Agent，也不要求编程。每个模块都尽量做到：复制提示词、填写需求卡、在豆包、DeepSeek、ChatGPT 等普通对话 AI 中直接使用。

## 已有模块

### 01. 小红书封面助手

帮助用户完成封面标题、模板选择、视觉锚点、配色排版、生图提示词和成品复盘。

- [模块使用说明](modules/xiaohongshu-cover/docs/小白使用说明.md)
- [封面助手总提示词](modules/xiaohongshu-cover/prompts/01-封面助手总提示词.md)
- [极简需求卡](modules/xiaohongshu-cover/prompts/02-极简需求卡.md)
- [修改返工口令](modules/xiaohongshu-cover/prompts/03-修改返工口令.md)
- [封面质检提示词](modules/xiaohongshu-cover/prompts/04-封面质检提示词.md)
- [10 个需求卡示例](modules/xiaohongshu-cover/examples/10个需求卡示例.md)

## 未来可扩展模块

- 自媒体账号定位
- 选题库与热点拆解
- 爆款标题改写
- 短视频脚本
- 口播稿与分镜
- 小红书正文
- 公众号文章
- 内容复盘与数据分析
- 评论区互动与私域承接

## 目录结构

```text
creator-ai-toolkit/
├─ modules/
│  └─ xiaohongshu-cover/
│     ├─ prompts/
│     ├─ examples/
│     └─ docs/
├─ CONTRIBUTING.md
├─ PUBLISHING.md
└─ README.md
```

以后新增能力时，在 `modules/` 下建立独立目录即可，例如：

```text
modules/topic-generator/
modules/title-rewriter/
modules/short-video-script/
```

每个模块建议至少包含一个总提示词、一张极简需求卡、使用说明和实际示例。

## 封面模块 30 秒开始

1. 新开对话，完整复制[封面助手总提示词](modules/xiaohongshu-cover/prompts/01-封面助手总提示词.md)。
2. 复制[极简需求卡](modules/xiaohongshu-cover/prompts/02-极简需求卡.md)，填空后发送。
3. 将 AI 输出的“完整生图提示词”交给你使用的图片生成工具。
4. 不满意时使用[修改返工口令](modules/xiaohongshu-cover/prompts/03-修改返工口令.md)；支持看图的 AI 可用[质检提示词](modules/xiaohongshu-cover/prompts/04-封面质检提示词.md)复盘。

## 能力边界

本项目提供普通聊天可执行的提示词和人工工作流，不包含自动读取文件、自动调用生图、自动多轮检查等 Agent 自动化能力。纯文字模型可负责策划与生成提示词，图片仍需交给具备生图功能的平台。

## 来源说明

首个封面模块的方法灵感参考了 [ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system) 中的信息密度、视觉锚点与模板化封面策划思路。本仓库内容是面向普通对话 AI 的重新组织版本。发布和再分发时，请同时遵守上游项目适用的署名与许可要求。

## 参与贡献

新增模块和改进建议请先阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。上传 GitHub 前的事项见 [PUBLISHING.md](PUBLISHING.md)。
