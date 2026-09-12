# Changelog / 更新记录

All notable adaptation changes are recorded here. Repository release numbers are separate from Codex's `spriteVersionNumber`.

这里记录适配项目的重要变化。仓库 Release 版本号与 Codex 的 `spriteVersionNumber` 相互独立。

## [Unreleased] / 未发布

- No unpublished files are stored in this public repository. / 本公开仓库不预存尚未发布的文件。

## [v3.0.0] - 2026-09-11

### English

- First GitHub archival release of the existing v3 Codex Pet adaptation.
- Added all nine standard Codex animation rows.
- Added task-oriented `waiting`, desk-work `running`, and book-reading `review` states.
- Added English in-app attribution: `Loris from VPet Simulator.` plus the official source link.
- Added bilingual installation, use, update, removal, attribution, and redistribution instructions.
- Added a QA contact sheet and deterministic validation record.

Known limitation: during an active task, Codex may fall back to `idle`; v3's idle loop looks like standing/resting.

### 中文

- 首次在 GitHub 存档发布现有 v3 Codex Pet 适配。
- 补齐 Codex 九种标准动画行。
- 提供面向任务的 `waiting`、桌前工作的 `running` 和读书审阅的 `review` 状态。
- Codex 内说明改为英文 `Loris from VPet Simulator.`，并附上官方来源链接。
- 补充中英文安装、使用、更新、删除、归属与再分发说明。
- 附带 QA 联系表和确定性验证记录。

已知限制：任务执行期间 Codex 可能回退到 `idle`；v3 的 idle 看起来像站立或休息。

