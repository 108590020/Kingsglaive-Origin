# Kingsglaive-Origin

Kingsglaive-Origin 是一個使用 Unreal Engine 4.27 製作的第三人稱RPG遊戲，整合日夜系統、角色動畫、特效、美術資源、自訂插件與完整設定，適合學習、展示或擴充 Unreal Engine 遊戲開發。

---

## 專案結構

- `Config/`：Unreal Engine 專案設定檔（引擎、遊戲、輸入、編輯器等）
- `Content/`：美術資源、特效、角色、動畫、UI、Blueprints 等
  - `_main/Blueprint/`：遊戲邏輯、角色行為、互動機制等藍圖資源
  - `_HelloWorld/`、`_MeleeCreeps/`、`AnimStarterPack/` 等：AI、角色、動畫、特效等
- `Plugins/`：自訂 Unreal Engine 插件（如 teat）
- `Source/`：角色骨架、動畫 FBX、技術說明文件、骨架模板
- `Intermediate/`：編譯過程產生的中間檔案與快取
- `Saved/`：暫存檔、日誌、Crash 報告、遊戲存檔、螢幕截圖等
- `DayNightSystem.uproject`：Unreal Engine 專案設定檔

---

## 主要功能

- 日夜系統展示
- 多種角色動畫與骨架
- 特效、材質、UI 整合
- Blueprint 視覺化遊戲邏輯設計
- 多場景與地圖設計

---

## 技術說明

- **Unreal Engine 4.27**：遊戲引擎，負責場景渲染、物理運算、動畫、特效、藍圖邏輯等
- **Blueprints**：視覺化程式設計工具，用於設計遊戲邏輯、角色行為、互動機制
- **FBX 動畫匯入**：角色動畫、骨架動作透過 FBX 格式匯入
- **美術資源整合**：材質、特效、UI、角色模型等
- **技術文件與骨架模板**：方便動畫師、技術美術進行二次編輯與匯入

---

## 如何開始

1. 使用 Unreal Engine 4.27 開啟 `DayNightSystem.uproject`
2. 進入 `Content/` 編輯美術資源或 Blueprint
3. 遊戲邏輯可在 `Content/_main/Blueprint/` 內編輯
4. 角色動畫與骨架可在 `Source/` 內匯入或調整

---

## 開發環境

- Unreal Engine 4.27
- 主要依賴 UE4 Blueprint、FBX 動畫、插件系統等模組

---

## 版本控制

- 建議設定 `.gitignore` 排除 Intermediate、Saved 等暫存與編譯檔案

---

如需詳細說明或貢獻，請參考各資料夾內的 README 或 Unreal Engine 官方文件。
