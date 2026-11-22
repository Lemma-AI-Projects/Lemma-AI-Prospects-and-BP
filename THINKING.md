# THINKING.md · 开工前必读

> 每次回答前查看本文件。它是本工作区的常驻工作约定，不是文档。

## 当前任务上下文

- 本工作区是 **Lemma AI 上市公开书 + BP 的文书准备区**。当前阶段：素材准备与头脑风暴。
- 参考上市书在 `prospectuses/`（Anthropic 424B4、SpaceX 424B4，SEC EDGAR 原件）。
- 素材地图在 `brainstorm-material.md`（源文件清单 + 原句 + 待定口径）。
- **风格目标：巨人格局 + 野性 + 艺术家气质。** MVP 阶段，但书写出来的气场不能是创业公司打补丁的语气。

## 素材源仓库（只读参考，不改动）

- `D:\github projects\lemma-ai` —— 产品与愿景（LEMMA_VISION.md、docs/design/pitch-deck/）
- `D:\github projects\OITS Repo\The-Throes\相关笔记\Lemma AI` —— A16Z 大纲、表单、灵感笔记
- `D:\github projects\Lemma-AI-Projects.github.io` —— whylemma 公开宣言

## 工作原则

1. **结论先行，每条一句，不解释为什么。** AI 味来自解释从句和自我点评，不来自词汇。
2. **先写场景和界面原话，再写结论**；抽象术语写完 grep 自查。
3. 不编造数字；引用一律给出处文件。
4. 决策分歧时**点名哪份文件过期**，不说"可能不一致"。
5. 交付物要短不要全。宁可少写。

## 环境备忘

- 本机托管 Python：`C:/Users/chkev/.workbuddy/binaries/python/envs/default/Scripts/python.exe`
- 本 agent 无 GitHub 凭证，push 交给用户。
- 当日日志 append-only：写 `.workbuddy/tmp/` 再 cat 追加，绝不直接 Write 日志文件。
- SEC 抓取带 User-Agent；下载完必须回尾部验 `</DOCUMENT>`。
