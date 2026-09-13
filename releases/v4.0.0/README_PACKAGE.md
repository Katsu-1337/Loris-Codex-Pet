# Loris Codex Pet v4 / 萝莉斯 Codex 桌宠 v4

> Free, non-commercial distribution only. / 仅限免费、非商业分发。

This is an unofficial Codex Pet adaptation of Loris from VPet Simulator. It is not affiliated with or endorsed by OpenAI, LB Game, VPet Simulator, or the VUP-Simulator team. Read `NOTICE.md` before using or redistributing the animation-derived files.

这是《虚拟桌宠模拟器》（VPet Simulator）萝莉斯的非官方 Codex Pet 适配，与 OpenAI、LB Game、《虚拟桌宠模拟器》或虚拟主播模拟器制作组不存在隶属、合作或背书关系。使用或再分发由动画衍生的文件前，请阅读 `NOTICE.md`。

## What changed / 更新内容

- `idle` is now a calm desk-ready loop, so active-task fallback remains visually compatible with work. / `idle` 改为安静的桌前循环，使任务期间的回退仍保持工作感。
- `waiting`, `running`, and `review` remain distinct task-oriented states. / `waiting`、`running` 与 `review` 保持清晰、互有区别的任务语义。
- Waiting, review, and failure loops were refined; desk actions received a safer transparent bottom margin. / 优化等待、审阅和失败循环，并为桌前动作保留更安全的透明底边。

## Install / 安装

1. Close Codex before replacing the installed files.  
   替换已安装文件前请先关闭 Codex。
2. Copy this entire `loris-vpet` folder to `%USERPROFILE%\.codex\pets\loris-vpet`.  
   将整个 `loris-vpet` 文件夹复制到 `%USERPROFILE%\.codex\pets\loris-vpet`。
3. Replace `pet.json` and `spritesheet.webp` together; do not mix files from different releases.  
   请同时替换 `pet.json` 和 `spritesheet.webp`，不要混用不同 Release 的文件。
4. Restart Codex, or refresh and select **Loris** in **Settings > Pets**.  
   重启 Codex，或者在**设置 > Pets**中刷新并选择 **Loris**。

To remove the pet, close Codex, delete `%USERPROFILE%\.codex\pets\loris-vpet`, and reopen Codex.

如需删除，请关闭 Codex，移除 `%USERPROFILE%\.codex\pets\loris-vpet`，再重新打开 Codex。

## Compatibility / 兼容性

- Codex sprite schema: v1 (`spriteVersionNumber: 1`)
- Atlas: transparent lossless WebP, `1536 × 1872`, `8 × 9` cells
- Atlas SHA-256: `FA8CB52C10674697D3AC7552B184686D7DD3B6B9514B56E119659222AB1F631D`
- Validation: passed with 0 errors and 0 warnings / 验证通过：0 错误、0 警告

Source / 来源：https://github.com/LorisYounger/VPet
