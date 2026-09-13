# Loris Codex Pet v4 / 萝莉斯 Codex 桌宠 v4

> Free, non-commercial distribution only. / 仅限免费、非商业分发。

## English

v4 is the work-state refinement release. Its main goal is to keep Loris visually compatible with active work when Codex returns to the slow `idle` loop while the underlying task state remains unchanged.

### What changed

- Replaced the standing/resting `idle` row with a calm desk-ready loop.
- Matched the `idle` and `running` base desk pose, while preserving a more visible writing cadence in `running`.
- Rebuilt `waiting` as a complete symmetric thinking/needs-input loop without a hard reset.
- Refined `review` with one natural blink and removed faint low-alpha pink residue inherited from the source effect.
- Resampled the forward and return phases of `failed` for a smoother loop seam.
- Shifted desk actions upward by 4 pixels to keep a safer transparent bottom margin.
- Preserved the v3 directional movement, waving, and jumping rows.
- Synchronized the in-app identity and attribution as `Loris` and `Loris from VPet Simulator. Source: https://github.com/LorisYounger/VPet`.

No AI redraw was used. The release uses deterministic selection, resizing, alignment, residue cleanup, and atlas assembly from the original VPet animation frames.

### Validation and downloads

- Codex sprite schema: v1 (`spriteVersionNumber: 1`)
- Atlas: transparent lossless WebP, `1536 × 1872`, 8 columns × 9 rows
- Atlas size: 364,036 bytes
- Atlas SHA-256: `FA8CB52C10674697D3AC7552B184686D7DD3B6B9514B56E119659222AB1F631D`
- Deterministic atlas validation: passed with 0 errors and 0 warnings
- Release assets include the installable ZIP, standalone spritesheet, contact sheet, focused work-state preview GIF, validation JSON, and SHA-256 checksums.

### Install

Download `loris-vpet-v4.zip`, extract it, and copy the `loris-vpet` folder to `%USERPROFILE%\.codex\pets\loris-vpet`. Replace `pet.json` and `spritesheet.webp` together, then restart Codex or refresh Pets in Settings and select **Loris**.

For web upload, use the standalone `loris-vpet-v4-spritesheet.webp` asset in **Settings > Personalization > Pet > Upload pet**.

### Attribution and authorization

Loris and the original default animation artwork come from [VPet Simulator](https://github.com/LorisYounger/VPet); the upstream notice identifies the VUP-Simulator team as the animation copyright owner. This release is an unofficial technical adaptation and claims no ownership or official endorsement.

The release follows the upstream [animation authorization terms](https://github.com/LorisYounger/VPet/blob/main/README_en.md#animation-copyright-notice-and-authorization-terms): non-commercial use must identify and link the source; commercial use additionally requires prior contact, a first-use source pop-up, an accessible source notice, and no profit from selling the animation files; distribution must disclose all of those conditions, link the official repository, and charge no fee or profit from the files. Built-in images use the same terms, and the upstream ZIP Photo Gallery is non-commercial only. The complete bilingual notice is included in the download as `NOTICE.md`.

The original VPet archive, `.lps` metadata, and extracted source frames are not included.

## 中文

v4 是工作状态优化版。主要目标是：当任务底层状态保持不变、Codex 回到较慢的 `idle` 循环时，萝莉斯在视觉上依然与工作状态相符。

### 更新内容

- 把站立/休息式 `idle` 改为安静的桌前循环。
- 让 `idle` 与 `running` 共用一致的基础桌面姿势，同时保留 `running` 中更明显的书写节奏。
- 将 `waiting` 重建为完整、对称的思考/等待输入循环，避免硬切回起点。
- 优化 `review`：加入一次自然眨眼，并清除源特效遗留的低透明度淡粉色残点。
- 重新覆盖 `failed` 的前进与返回阶段，降低循环接缝突跳。
- 桌前动作整体上移 4 像素，保留更安全的透明底边。
- 保留 v3 的左右移动、挥手和跳跃动作。
- 同步 Codex 内名称与归属说明：`Loris`，以及 `Loris from VPet Simulator. Source: https://github.com/LorisYounger/VPet`。

本版未使用 AI 重画；所有处理均基于原始 VPet 动画帧，采用确定性的选帧、缩放、对齐、残点清理和图集重组。

### 验证与下载内容

- Codex 图集规范：v1（`spriteVersionNumber: 1`）
- 图集：带透明通道的无损 WebP，`1536 × 1872`，8 列 × 9 行
- 图集大小：364,036 字节
- 图集 SHA-256：`FA8CB52C10674697D3AC7552B184686D7DD3B6B9514B56E119659222AB1F631D`
- 确定性图集验证：通过，0 错误、0 警告
- Release 附件包括可安装 ZIP、独立 spritesheet、动作总览图、工作状态 GIF、验证 JSON 和 SHA-256 校验值。

### 安装

下载并解压 `loris-vpet-v4.zip`，把其中的 `loris-vpet` 文件夹复制到 `%USERPROFILE%\.codex\pets\loris-vpet`。请同时替换 `pet.json` 与 `spritesheet.webp`，随后重启 Codex；也可以在设置中刷新 Pets 并选择 **Loris**。

如需网页端上传，请在 **设置 > 个性化 > Pet > 上传宠物** 中选择独立附件 `loris-vpet-v4-spritesheet.webp`。

### 归属与授权

萝莉斯及原始默认动画美术来自[《虚拟桌宠模拟器》](https://github.com/LorisYounger/VPet)；上游声明动画版权归虚拟主播模拟器制作组所有。本 Release 是非官方技术适配，不主张拥有相关美术，也不表示得到官方背书。

本 Release 遵守上游[动画版权声明与授权](https://github.com/LorisYounger/VPet/blob/main/README.md#动画版权声明与授权)：非商业使用必须说明并链接来源；商业使用还必须事先联系作者、首次使用时通过醒目弹窗说明来源、在易于访问的页面中保留来源说明，并且不得靠出售动画文件获利；分发时必须披露所有这些条件、链接官方仓库，且不得收费或通过这些文件获利。程序内置图片适用相同条件，上游 ZIP 照片图库仅限非商业用途。下载包内的 `NOTICE.md` 包含完整中英文声明。

本 Release 不包含 VPet 原始压缩包、`.lps` 元数据或解包后的源动画帧。
