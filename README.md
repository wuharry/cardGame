# 卡牌遊戲專案

這是一個使用 Godot 引擎開發的卡牌遊戲專案。本專案旨在創建一個互動式卡牌遊戲，提供流暢的遊戲體驗和精美的視覺效果。

## 目錄結構

專案的目錄結構經過精心設計，以保持程式碼和資源的組織性：

```
cardGame/
├── assets/             # 資源文件目錄
│   ├── fonts/          # 字體資源
│   ├── sounds/         # 音效和音樂文件
│   ├── textures/       # 紋理和圖像文件
│   ├── icon.svg        # 專案圖標
│   └── reference_image_20250408.png  # 參考圖像
├── scenes/             # 場景文件目錄
│   ├── levels/         # 遊戲關卡場景
│   ├── ui/             # 使用者介面場景
│   └── MainScene.tscn  # 主場景文件
├── scripts/            # 腳本文件目錄
│   ├── game_logic/     # 遊戲邏輯相關腳本
│   └── ui/             # UI 相關腳本
├── .editorconfig       # 編輯器配置
├── .gitattributes      # Git 屬性配置
├── .gitignore          # Git 忽略規則
├── project.godot       # Godot 專案配置文件
└── README.md           # 專案說明文檔
```

## 環境設置

要開始使用本專案，請按照以下步驟進行設置：

1. 安裝 Godot 引擎（建議使用 Godot 4.x 版本）
2. 克隆此儲存庫：
   ```
   git clone https://github.com/wuharry/cardGame.git
   ```
3. 使用 Godot 引擎開啟專案目錄中的 `project.godot` 文件
4. 等待 Godot 引擎匯入所有資源文件

## 使用說明

### 開發者

1. 主場景位於 `scenes/MainScene.tscn`，這是遊戲的入口點
2. 在 Godot 編輯器中點擊「播放」按鈕以測試遊戲
3. 使用 F5 鍵可以快速啟動遊戲

### 玩家

將在發布第一個正式版本後提供遊戲操作指南。

## 開發規範

為了保持專案的一致性和可維護性，請遵循以下開發規範：

### 命名規範

- **檔案命名**：使用 PascalCase（例如：`CardTemplate.tscn`、`PlayerController.gd`）
- **變數命名**：使用 snake_case（例如：`player_health`、`card_damage`）
- **函數命名**：使用 snake_case（例如：`update_health()`、`draw_card()`）

### 資源管理

- 所有資源文件應放置在適當的子目錄中（textures、sounds、fonts 等）
- 遵循統一的命名模式，避免使用特殊字符或中文字符作為文件名

### 版本控制

- 提交時使用清晰的提交訊息，描述變更的內容和目的
- 遵循 Git 工作流程，使用分支進行功能開發
- 定期拉取和推送更新，避免大型合併衝突

### 程式碼風格

- 使用適當的縮排（建議使用 4 個空格）
- 添加註釋說明複雜的邏輯和算法
- 遵循 Godot 的最佳實踐和設計模式

## 版權信息

© 2025 卡牌遊戲開發團隊。保留所有權利。

