# 少林呱呱 Codex V2 桌宠 | Shaolin Guagua Codex V2 Pet

《洛克王国》棍术修行形态 #426的非官方桌宠设计。动作包括持棍待机、基本棍术、失手后的尴尬与克制的收势。

An unofficial pet based on the staff-practice form #426 of *Rock Kingdom*. It features staff practice, an embarrassed recovery, and a modest finishing pose.

外观：橙色单肩武僧服，左肩露出，红色腰封结在角色自身右侧；棍为独立道具。

Appearance: An orange one-shoulder monk outfit with the left shoulder bare, a red sash tied on the character own right, and a separate staff.

| 待机 Idle | 悬停 Hover | 工作 Working | 成功 Success |
|---|---|---|---|
| ![Idle](assets/idle.gif) | ![Hover](assets/hover.gif) | ![Working](assets/working.gif) | ![Success](assets/success.gif) |

## 安装 / Installation

将 `guagua-426` 文件夹复制到 Codex 的 `pets` 目录，然后在 Codex Desktop 的 **Settings → Pets** 中选择“少林呱呱”。本项目机器上的安装路径是 `E:\AI Agents\Codex\pets\guagua-426`。若刚替换图集，完全退出并重新打开 Codex 或切换到另一只宠物再切回。

Copy `guagua-426` into your Codex `pets` directory, then select **Shaolin Guagua** in **Settings → Pets**. Restart Codex or switch pets and back if the old atlas remains cached.

~~~text
pets/guagua-426/
├── pet.json
└── spritesheet.webp
~~~

## 动画 / Animations

| 行 Row | 状态 State | 有效帧 Frames |
|---:|---|---:|
| 0 | Idle | 7 |
| 1–2 | Running Right / Left | 8 each |
| 3 | Waving | 4 |
| 4 | Hover / Jump | 5 |
| 5 | Failed | 8 |
| 6 | Waiting | 6 |
| 7 | Working | 6 |
| 8 | Review / Success | 6 |
| 9–10 | Look / Tracking | 8 each |

图集为 1536×2288 px，8 列×11 行，单格 192×208 px，无损 RGBA WebP，`spriteVersionNumber: 2`。左右跑独立绘制，服装和道具保持角色自身左右属性。本仓库只含最终安装文件与从最终图集导出的四个预览，不含原始参考图、废稿或制作过程素材。

The atlas is a lossless RGBA WebP at 1536×2288 px, arranged as 8 columns × 11 rows of 192×208 px cells, with `spriteVersionNumber: 2`. Left and right running poses were created separately to preserve costume and prop topology. This repository contains only the install files and four previews rendered from the final atlas; it does not contain reference images, rejected drafts, or production intermediates.

## 同人声明 / Fan-work notice

本项目为非官方、非商业同人作品。角色名称、形象与相关知识产权归其权利方所有。本仓库不代表获得权利方、OpenAI 或 Codex 授权；不对第三方角色形象授予开源再许可。

This is an unofficial, non-commercial fan work. The character and related intellectual property belong to their respective rights holders. No endorsement or authorization by the rights holders, OpenAI, or Codex is implied. This repository does not grant an open-source license to the underlying character IP.
