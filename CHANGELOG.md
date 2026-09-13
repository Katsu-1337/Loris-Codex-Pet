# Changelog / 更新记录

All notable adaptation changes are recorded here. Repository release numbers are separate from Codex's `spriteVersionNumber`.

这里记录适配项目的重要变化。仓库 Release 版本号与 Codex 的 `spriteVersionNumber` 相互独立。

## [Unreleased] / 未发布

- No unpublished files are stored in this public repository. / 本公开仓库不预存尚未发布的文件。

## [v4.0.0] - 2026-09-12

### English

- Replaced the standing/resting `idle` row with a calm desk-ready loop so active-task runtime fallback still looks work-compatible.
- Aligned the `idle` and `running` base desk pose while keeping the active writing cadence in `running` more visible.
- Rebuilt `waiting` as a complete symmetric thinking/needs-input loop without a hard reset.
- Refined `review` to include one natural blink and removed faint low-alpha pink residue inherited from the source effect.
- Resampled the forward and return phases of `failed` for a smoother loop seam.
- Shifted desk actions upward by 4 pixels to preserve a safer transparent bottom margin.
- Preserved the v3 directional movement, waving, and jumping rows.
- Kept the in-app English attribution and official VPet source link synchronized across the current package and release package.
- Added a v4 contact sheet, focused work-state GIF, and deterministic validation record.

No AI redraw was used. v4 uses deterministic frame selection, resizing, alignment, residue cleanup, and atlas assembly from the original VPet animation frames.

### 中文

- 把站立/休息式 `idle` 改为安静的桌前循环，使任务期间的运行时回退仍保持工作感。
- 对齐 `idle` 与 `running` 的基础桌面姿势，同时让 `running` 的主动书写节奏更明显。
- 将 `waiting` 重建为完整、对称的思考/等待输入循环，避免硬切回起点。
- 优化 `review`：加入一次自然眨眼，并清除源特效遗留的低透明度淡粉色残点。
- 重新覆盖 `failed` 的前进与返回阶段，降低循环接缝突跳。
- 桌前动作整体上移 4 像素，保留更安全的透明底边。
- 保留 v3 的左右移动、挥手和跳跃动作。
- 在当前包与 Release 包之间同步 Codex 内英文归属说明及 VPet 官方来源链接。
- 新增 v4 动作总览图、工作状态 GIF 和确定性验证记录。

本版未使用 AI 重画；v4 仅对原始 VPet 动画帧进行确定性的选帧、缩放、对齐、残点清理和图集重组。

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
