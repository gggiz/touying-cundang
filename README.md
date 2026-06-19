# 投影存档

古龙建筑投影存档，包含 Minecraft 世界存档和 Litematica 投影文件。

## 文件结构

```
├── 叹息古龙_纯网格_OTS.litematic   # Litematica 投影文件
└── 古龙/                           # Minecraft 世界存档
    ├── datapacks/
    │   └── 突破限高/               # 自定义数据包（扩展建筑高度限制）
    ├── dimensions/                 # 维度数据（Overworld/Nether/End）
    └── data/                       # 世界数据（记分板、游戏规则等）
```

## 使用方式

### 加载投影文件

1. 安装 [Litematica](https://www.curseforge.com/minecraft/mc-mods/litematica) 模组
2. 将 `.litematic` 文件放入 `.minecraft/schematics/`
3. 游戏中打开 Litematica 菜单加载投影

### 加载世界存档

将 `古龙/` 文件夹放入 `.minecraft/saves/`，在单人游戏中加载。
