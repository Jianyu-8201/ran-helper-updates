# RAN 助手更新

[最新版本與更新說明](https://github.com/Jianyu-8201/ran-helper-updates/releases/latest)

## 下載

- [免 Root 版 APK](https://github.com/Jianyu-8201/ran-helper-updates/releases/latest/download/ran-noroot.apk)：一般 Android 手機、平板或未 Root 雲手機，需要無障礙服務。
- [Root 版 APK](https://github.com/Jianyu-8201/ran-helper-updates/releases/latest/download/ran-root.apk)：需要 Root 授權。

最低 Android 8。免 Root 版不依賴 x86 原生元件；Root 版包含 x86_64 與 ARM64 元件，尚未在 ARM64 雷電雲手機實測。

## 自動檢查更新

首次手動安裝對應 APK 後，每次從圖示開啟助手會檢查新版，自動下載並開啟 Android 安裝確認畫面。最後仍需使用者確認安裝。相同類型可直接覆蓋安裝，以保留設定。

App 已預設本儲存庫網址。如果使用先前可設定網址的版本，可在「更新設定」填入 `https://github.com/Jianyu-8201/ran-helper-updates`。

- 免 Root 版本資訊：`https://github.com/Jianyu-8201/ran-helper-updates/releases/latest/download/noroot.json`
- Root 版本資訊：`https://github.com/Jianyu-8201/ran-helper-updates/releases/latest/download/root.json`

沒有網路或取消更新時仍可使用原本版本。下載後會核對大小、SHA-256、套件名稱、版本和已安裝助手的簽章。

## 功能範圍

免 Root 版提供定時按鍵與固定路線，不能判斷怪物、血量或精準 400 M 距離。需要手動校準按鍵並讓遊戲保持前景。

Root 版的功能依裝置、Root 權限與遊戲版本而定。各次發布的驗證範圍列在 Release 說明中。

此儲存庫提供 APK、版本資訊和使用說明。GitHub 自動提供的 Source code 壓縮檔僅包含此儲存庫的說明檔，並非助手原始碼。
