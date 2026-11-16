# Type4Me 衍生工程 — Agent 規則

先讀本檔、`RULES.md` 與精簡的 `MEMORY.md`（存在時）；歷史只按問題查找，不預設全文載入。

- 倉庫：`dylanchiang-forks/FORK-type4me`；本機 `/002/dylanchiang-forks/FORK-type4me/`。
- Swift Package Manager 的 macOS 語音輸入工程；保留雲端與本地 ASR 版本邊界，Linux 文件檢查不能冒充 macOS 實機驗收。
- 建置變體、ASR provider、下載與 Keychain 讀開發參考；GUI 憑證經應用設定與 Keychain，不假定能從 shell 環境載入。
- 修改前核對分支、origin、upstream 與工作樹；保留既有修改，只處理本次相關檔案，不強推或自行重設歷史。
- 現況改寫 MEMORY 原條目；詳細經過放 docs/memory，已結束的歷史退出根入口，不每輪追加。
- 不把憑證、環境值或私人狀態寫入文件、日誌或 Git；不新增追蹤及未要求的網路呼叫。
- 驗證依實際 scripts 與變更範圍；純協作文件檢查差異與連結，不啟動服務或資料庫。提交、推送與部署遵守當次授權。

[依模組查開發參考](docs/agent-development.md)。

[整理前規則](docs/archive/AGENTS-before-20261116.md) 僅供歷史追溯；舊路徑、部署日誌與過時命令不作為目前環境依據。
