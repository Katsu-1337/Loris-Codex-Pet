# Loris Codex Pet v3 / 萝莉斯 Codex 桌宠 v3

> Free, non-commercial distribution only. / 仅限免费、非商业分发。

## English

This is the first GitHub archival release of the existing v3 Codex Pet adaptation.

### Included

- Loris packaged for the Codex v1 sprite-atlas format
- All nine standard animation states
- Task-oriented `waiting`, desk-work `running`, and book-reading `review`
- Preserved directional movement, waving, jumping, and failure animations
- English in-app description with a direct link to the official VPet source
- Bilingual installation and attribution documentation inside the ZIP
- QA contact sheet and deterministic validation record

### Known limitation

Codex may fall back to the slow `idle` loop while a task is still active. In v3, that loop can look like standing or resting. The later v4 release is designed to address this behavior.

### Install

Download `loris-vpet-v3.zip`, extract it, and copy the `loris-vpet` folder to `%USERPROFILE%\.codex\pets\loris-vpet`. Replace `pet.json` and `spritesheet.webp` together, then restart or refresh Codex Pets.

### Attribution and authorization

Loris and the original default animation artwork come from [VPet Simulator](https://github.com/LorisYounger/VPet); the upstream notice identifies the VUP-Simulator team as the animation copyright owner. This release is an unofficial technical adaptation and claims no ownership or official endorsement.

The release follows the upstream [animation authorization terms](https://github.com/LorisYounger/VPet/blob/main/README_en.md#animation-copyright-notice-and-authorization-terms): non-commercial use must identify and link the source; commercial use additionally requires prior contact, a first-use source pop-up, an accessible source notice, and no profit from selling the animation files; distribution must disclose all of those conditions, link the official repository, and charge no fee or profit from the files. Built-in images use the same terms, and the upstream ZIP Photo Gallery is non-commercial only. The complete bilingual notice is included in the download as `NOTICE.md`.

## 中文

这是现有 v3 Codex 桌宠适配的首次 GitHub 存档发布。

### 包含内容

- 按 Codex v1 图集格式打包萝莉斯
- Codex 九种标准动画状态
- 面向任务的 `waiting`、桌前工作的 `running` 和读书审阅的 `review`
- 保留左右移动、挥手、跳跃和失败动作
- Codex 内英文描述附 VPet 官方来源直链
- ZIP 内附中英文安装和归属说明
- 附带 QA 联系表和确定性验证记录

### 已知限制

任务仍在进行时，Codex 可能回退到较慢的 `idle` 循环。v3 的这个循环有时看起来像站立或休息；之后发布的 v4 会针对该行为进行优化。

### 安装

下载并解压 `loris-vpet-v3.zip`，把 `loris-vpet` 文件夹复制到 `%USERPROFILE%\.codex\pets\loris-vpet`。请同时替换 `pet.json` 与 `spritesheet.webp`，然后重启或刷新 Codex Pets。

### 归属与授权

萝莉斯及原始默认动画美术来自[《虚拟桌宠模拟器》](https://github.com/LorisYounger/VPet)；上游声明动画版权归虚拟主播模拟器制作组所有。本 Release 是非官方技术适配，不主张拥有相关美术，也不表示得到官方背书。

本 Release 遵守上游[动画版权声明与授权](https://github.com/LorisYounger/VPet/blob/main/README.md#动画版权声明与授权)：非商业使用必须说明并链接来源；商业使用还必须事先联系作者、首次使用时通过醒目弹窗说明来源、在易于访问的页面中保留来源说明，并且不得靠出售动画文件获利；分发时必须披露所有这些条件、链接官方仓库，且不得收费或通过这些文件获利。程序内置图片适用相同条件，上游 ZIP 照片图库仅限非商业用途。下载包内的 `NOTICE.md` 包含完整中英文声明。

