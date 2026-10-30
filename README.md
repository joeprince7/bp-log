# 血壓紀錄

手機用的血壓紀錄小工具：數字鍵盤輸入收縮壓、舒張壓、心跳與時間，列表顯示、可修改刪除、統計平均、自訂標準範圍，並可輸出 CSV（LibreOffice Calc 可讀）。

作者：Joeprince

## 用 GitHub Pages 在手機執行

1. 在 GitHub 建一個新的 repository（例如 `bp-log`），設為 Public。
2. 按 **Add file → Upload files**，把這個資料夾裡的所有檔案拖進去，按 **Commit changes**。
3. 到 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾 `/ (root)`，按 **Save**。
4. 等一兩分鐘，網址會是 `https://<你的帳號>.github.io/bp-log/`。
5. 用手機瀏覽器打開該網址：
   - iPhone（Safari）：分享 → 加入主畫面
   - Android（Chrome）：選單 → 加到主畫面 / 安裝應用程式

加到主畫面後會像 App 一樣全螢幕開啟，沒有網路也能使用。

## 注意

紀錄存在手機瀏覽器裡（localStorage），只有那支手機看得到；刪除 App 或清除瀏覽器資料會一併清掉，請定期用「輸出檔案」備份。
