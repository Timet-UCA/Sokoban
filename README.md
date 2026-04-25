# 3D Sokoban
UE 5.5.4 制作的 3D 推箱子原型，项目包含完整游戏流程，一个自制的关卡编辑工具，用于快速创建、保存、预览和测试关卡。

## 使用引擎版本

- Unreal Engine 5.5.4

## 项目主要功能

完整游戏流程：Lv_Sokoban

主流程为：

主菜单 → 关卡选择 → 进入游戏 → 通关 → 返回关卡选择界面

Menu:本项目用键盘控制UI

- `W / S / A / D`：切换选项或关卡
- `Space`：确认
- `Esc`：返回上一层界面

Gameplay:

- 玩家按网格单位移动
- 箱子可以被推动
- 墙体阻挡玩家和箱子
- 箱子不能被推到墙外或其他箱子上
- 只要所有 Goal 上都有 Box，即判定关卡成功

关卡编辑器：Lv_LevelEditor

打开该关卡，并在Content/Sokoban/Blueprint/UtilityWidget下找到EUW_LevelEditor
右键Run Editor Utility Widget
使用左侧工具，在右侧关卡2D映射PANEL中编辑当前关卡
点击运行开始测试

- ---
  项目使用购买美术资源
  Advanced_Water_Material
  UltraDynamicSky
- ---
  运行请选择 —— 新建编辑器窗口(PIE)
