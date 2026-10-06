# MCJS-Archive

本仓库用于存档 MC.JS 网页版 Minecraft 启动器的历史版本。

原始站点：https://mc.js.cool/ 或 https://mcjs.cc/

## 说明

MC.JS 是一个基于网页的 Minecraft 启动器，收录了 GitHub 上的开源网页 MC 项目，提供无需下载、即开即玩的网页版 Minecraft 体验。

本站点已于原始域名停止维护，本仓库通过 Internet Archive（网页时光机）抓取的快照，对页面进行修复与还原，以便长期保存和查阅。

## 目录结构

```
MCJS-Archive/
├── .gitattributes
├── LICENSE
├── README.md
├── index.html                        # 仓库入口页
│
├── 2023/                             # 2023 年版本存档
│   ├── breakpoints.min.js
│   ├── browser.min.js
│   ├── font.woff2
│   ├── index.html
│   ├── jquery.min.js
│   ├── main.js
│   ├── mcfront.jpg
│   ├── util.js
│   │
│   ├── play/                         # 网页版 Minecraft 1.8.8 u23
│   │   ├── assets.epk
│   │   ├── classes.js
│   │   ├── classes.js.map
│   │   ├── favicon.png
│   │   ├── index.html
│   │   └── lang/
│   │       └── zh_CN.lang
│   │
│   └── web/                          # WebMC（nodejs 重写版）
│       ├── index.html
│       ├── mc.css
│       ├── server.js
│       ├── src/
│       │   ├── globalVeriable.js
│       │   ├── main.js
│       │   ├── processingPictures.js
│       │   ├── settings.js
│       │   │
│       │   ├── Entity/
│       │   │   ├── Entity.js
│       │   │   ├── EntityController.js
│       │   │   ├── Item.js
│       │   │   ├── Player.js
│       │   │   └── PlayerLocalController.js
│       │   │
│       │   ├── Renderer/
│       │   │   ├── BlockModuleBuilder.js
│       │   │   ├── Camera.js
│       │   │   ├── EntitiesPainter.js
│       │   │   ├── EntityItemModel.js
│       │   │   ├── glsl.js
│       │   │   ├── HighlightSelectedBlock.js
│       │   │   ├── Program.js
│       │   │   ├── Render.js
│       │   │   ├── WelcomePageRenderer.js
│       │   │   ├── WorldChunkModule.js
│       │   │   └── WorldRenderer.js
│       │   │
│       │   ├── UI/
│       │   │   ├── doc.txt
│       │   │   ├── index.js
│       │   │   ├── components/
│       │   │   │   ├── Component.js
│       │   │   │   ├── MCButton.html
│       │   │   │   ├── MCButton.js
│       │   │   │   ├── MCCrosshairs.js
│       │   │   │   ├── MCFullScreenBtn.js
│       │   │   │   ├── MCHotbar.html
│       │   │   │   ├── MCHotbar.js
│       │   │   │   ├── MCInput.html
│       │   │   │   ├── MCInput.js
│       │   │   │   ├── MCInventory.html
│       │   │   │   ├── MCInventory.js
│       │   │   │   ├── MCMoveBtns.html
│       │   │   │   ├── MCMoveBtns.js
│       │   │   │   ├── MCSlider.html
│       │   │   │   ├── MCSlider.js
│       │   │   │   ├── MCSwitch.html
│       │   │   │   └── MCSwitch.js
│       │   │   └── pages/
│       │   │       ├── CreateNewWorldPage.html
│       │   │       ├── CreateNewWorldPage.js
│       │   │       ├── HowToPlayPage.html
│       │   │       ├── HowToPlayPage.js
│       │   │       ├── LoadTerrainPage.html
│       │   │       ├── LoadTerrainPage.js
│       │   │       ├── Page.js
│       │   │       ├── PausePage.html
│       │   │       ├── PausePage.js
│       │   │       ├── PlayPage.html
│       │   │       ├── PlayPage.js
│       │   │       ├── PreloadPage.js
│       │   │       ├── SelectWorldPage.html
│       │   │       ├── SelectWorldPage.js
│       │   │       ├── SettingPage.html
│       │   │       ├── SettingPage.js
│       │   │       ├── WelcomePage.html
│       │   │       └── WelcomePage.js
│       │   │
│       │   ├── utils/
│       │   │   ├── EventDispatcher.js
│       │   │   ├── FiniteStateMachine.js
│       │   │   ├── isWebGL2Context.js
│       │   │   ├── loadResources.js
│       │   │   └── math/
│       │   │       ├── common.js
│       │   │       ├── index.js
│       │   │       ├── mat4.js
│       │   │       ├── solver.js
│       │   │       ├── vec2.js
│       │   │       └── vec3.js
│       │   │
│       │   └── World/
│       │       ├── Block.js
│       │       ├── Block.txt
│       │       ├── blocks.json
│       │       ├── Chunk.js
│       │       ├── noise.js
│       │       ├── World.js
│       │       ├── WorldFluidCal.js
│       │       └── WorldLight.js
│       │
│       └── texture/
│           ├── background.png
│           ├── gui.png
│           ├── icons.png
│           ├── jumpingBlock.gif
│           ├── mc-font.ttf
│           ├── panorama.png
│           ├── spritesheet.png
│           ├── terrain-atlas.png
│           └── title.png
│
└── 2025/                             # 2025 年版本存档
    └── index.html
```

## 历史版本

2023 - 完全修复，游戏已还原
- Made by Github@Enchantment-Niko

2025 - 工作中
- 仅恢复基本 2025 index页面，后续可能不再更新

## 修复内容

- 移除 Wayback Machine 注入的归档注释与统计代码
- 将外链资源改为相对路径
- 清理无效的 CDN 引用
- 修正编码与字符集问题

## 版权与免责

本仓库仅作技术存档与学习研究用途。

- 页面原始内容版权归 MC.JS 原作者所有
- Minecraft 相关版权归 Mojang Studios 与 Microsoft 所有
- 本仓库与 "Minecraft" 及 "我的世界" 无任何隶属关系
- 若原作者或权利方要求下架，将立即移除相关内容

## 参考

- Internet Archive: https://web.archive.org/
- 原始站点快照: https://web.archive.org/web/*/https://mc.js.cool
