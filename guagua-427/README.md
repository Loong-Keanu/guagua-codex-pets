# 富贵呱呱 Codex V2 桌宠 | Fugui Guagua Codex V2 Pet

《洛克王国》九龙长廊修行形态 #427的非官方桌宠设计。动作包括帽两侧钱币饰件、算盘核算、失败时偷看与成功时短暂金币演出。

An unofficial pet based on the Jiulong Corridor form #427 of *Rock Kingdom*. It features two fixed hat coins, abacus work, shy failure, and a brief success coin effect.

外观：红色上衣、蓝色腰部带状装束、深色短下装；深色帽左右各固定一枚黄色钱币饰件。算盘只在工作动作出现。

Appearance: A red outfit, blue waist sash, dark shorts, and one fixed gold coin ornament on each side of the dark cap. The abacus appears only during work.

| 待机 Idle | 悬停 Hover | 工作 Working | 成功 Success |
|---|---|---|---|
| ![Idle](assets/idle.gif) | ![Hover](assets/hover.gif) | ![Working](assets/working.gif) | ![Success](assets/success.gif) |

## 安装 / Installation

将 `guagua-427` 文件夹复制到 Codex 的 `pets` 目录，然后在 Codex Desktop 的 **Settings → Pets** 中选择“富贵呱呱”。本项目机器上的安装路径是 `E:\AI Agents\Codex\pets\guagua-427`。若刚替换图集，完全退出并重新打开 Codex 或切换到另一只宠物再切回。

Copy `guagua-427` into your Codex `pets` directory, then select **Fugui Guagua** in **Settings → Pets**. Restart Codex or switch pets and back if the old atlas remains cached.

~~~text
pets/guagua-427/
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
