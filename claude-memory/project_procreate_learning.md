# Procreate 自學專案 — 背景速記

> Claude Code 記憶系統的可攜式備份（沿用使用者在 `NewEraR` 專案建立的慣例）。
> 換機器接續時，說「先讀 claude-memory/project_procreate_learning.md」即可還原背景。
> 最後更新：2026-09-25（從 NewEraR 獨立成 `tienhku/learn-drawing`）

## 這是什麼

使用者想從零開始學畫畫（Procreate）。這個 repo 就是那套為他量身寫的 12 週自學教材。

**歷史**：內容原本放在 `tienhku/NewEraR`（C01 機器人維修專案）的 `procreate/` 資料夾，
分支 `claude/procreate-drawing-learning-xvkhz8`。2026-09-25 獨立成這個 repo，
因為兩件事完全無關。**NewEraR 那份是歷史副本，之後只更新這裡。**

## 使用者狀況（2026-09-13）

- **完全沒有受過美術訓練**，成年自學
- iPad 與 iPhone 都已安裝 Procreate（iPhone 上是 Procreate Pocket，**兩者檔案不互通**）
- **Apple Pencil（USB-C）—— 沒有壓力感應**（2026-09-17 本人確認）。有傾斜感應。教材已全面改成「不透明度 20% 疊塗 ＋ 傾斜側鋒」的替代做法（`00-setup.md` 有專節、`D03`/`D09` 有無壓感版）。**建議他先不要換筆，也不要買第三方壓感筆。**
- **想畫的三個方向**（2026-09-17 本人確認）：人物角色、風景場景、日常靜物寫生。處理方式：靜物＝W2–W4 主題材、場景＝W5–W7、**人物另開支線**（W7 起每天暖身加 D18 姿態速寫 5 張、W10 起 10 張）。12 週後建議順序：人物 → 場景 → 靜物（靜物轉為維持）。
- 每日可投入時間假設為 **20–30 分鐘**，尚未與本人確認

## 教材結構（repo 根目錄）

| 檔案 | 內容 |
|---|---|
| `README.md` | 總覽、12 週地圖、每日流程、三條鐵律 |
| `00-setup.md` | 裝置與 App 設定、畫布規格、4 支起手式筆刷、備份規則 |
| `01-cheatsheet.md` | 手勢與介面速查 |
| `02-curriculum-12weeks.md` | 12 週逐日課表 + 每週通過標準 |
| `03-drills.md` | D01–D20 練習庫 |
| `04-fundamentals.md` | 美術原理（形/比例/明暗/邊緣/透視/構圖/色彩/學習法） |
| `05-troubleshooting.md` | 症狀診斷表（技術面 + 心態面） |
| `06-resources.md` | 書、頻道、素材、筆刷 |
| `progress-log.md` | 日誌模板 + 12 週追蹤表 |
| `practice/` | 使用者匯出的練習圖（JPEG）。`.procreate` 原始檔已在 `.gitignore` 排除 |
| `tracker.artifact.html` | 線上練習台的原始檔（發布成 Artifact，進度存在 db capability，iPad／iPhone 同步）<br>https://claude.ai/artifact/6qxMpartCqZ9ZJomKGAUL6 |

## 教學設計上的關鍵決定（之後調整時要知道原因）

1. **W1–W8 幾乎全黑白**，刻意把上色押後到 W9。理由：顏色會掩蓋形與明度的問題。
2. **限制只用 4 支內建筆刷**，禁止 12 週內購買筆刷包。理由：換筆刷是最舒服的逃避練習方式。
3. **核心觀念是「符號畫」問題**（見 `04-fundamentals.md` §0），所以 W2–W3 的盲輪廓/負空間/倒置臨摹不能跳。
4. **每天 25 分鐘上限、一週 4 天即算成功**。理由：連續性 > 單日時數。
5. **W12 會重畫 W1 的題目做對照**，所以 W1 的檔案一定要留著。

## 進度

- 2026-09-13：教材初版寫完，推到分支 `claude/procreate-drawing-learning-xvkhz8`。
- 2026-09-25：從 NewEraR 拆出來成為獨立 repo `tienhku/learn-drawing`，檔案移到根目錄，加上 `practice/` 與 `.gitignore`。
- 2026-09-17：確認筆與題材方向後，全面改寫壓感相關練習、加入人物支線、重排 12 週後路線圖；線上練習台同步更新。使用者**尚未開始 W1**（課表起算日原訂 2026-09-14，需要重新確認起算日）。
