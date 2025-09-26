# 贡献指南

感谢你的贡献！在提交前请遵循以下规则：

## 基本流程
- Fork 仓库并创建主题分支（例：`feat/update-hsbc-guide`）。
- 提交信息使用 Conventional Commits（如：`docs: add ZA Bank guide`）。
- 发起 PR，描述修改动机与要点，附关键截图（如有）。

## 文档规范（风格）
- 标题：使用 Title Case，文件内仅一个一级标题 `#`。
- 列表：使用 `-` 作为项目符号，二级缩进 2 个空格。
- 行宽：建议 ≤ 100 字符，便于审阅。
- 文件名：小写，使用中划线或下划线；可加地域/语言后缀（如 `appsail_hk.md`）。
- 链接：优先相对路径（如 `[Intro](intro.md)`）。

## 资源与结构
- 文档放入 `docs/` 对应章节目录；图片放入同级 `assets/` 或 `docs/assets/`。
- 新增银行/支付渠道：在相应章节 README 中补链，并创建对应指南文件。

## 格式化与校验（可选）
- 格式化：`npx prettier --prose-wrap always --write "**/*.md"`
- Lint：`npx markdownlint-cli2 "**/*.md"`
- 链接检查：`npx markdown-link-check -q <file>.md`

注：无需提交本地配置或脚本；本仓库不强制 npm/Makefile。
