# YT to MP3

YT to MP3 是一款基於 Tkinter 的桌面應用程式，能夠將 YouTube 影片轉換為 MP3 音訊檔案，適用於個人備份與離線收聽。

## 功能特色
- 使用 Tkinter 圖形化界面，簡單易用
- 下載 YouTube 影片並轉換為 MP3
- 支援高品質音訊輸出
- 進度條顯示下載進度
- 依賴 `yt-dlp` 進行下載與轉換

## 安裝方式
### 先決條件
請確保您的環境已安裝以下軟體：
- Python 3.x
- `yt-dlp` 套件
- `ffmpeg` (用於音訊轉換)
- `tkinter` (Python 內建 GUI 框架)
- `PyQt5` (用於圖示顯示)

### 安裝步驟
1. 克隆此專案
   ```bash
   git clone https://github.com/qrere-Ya/YT-to-MP3.git
   cd YT-to-MP3
   ```
2. 安裝必要的 Python 套件
   ```bash
   pip install -r requirements.txt
   ```

## 使用方式
### 執行應用程式
執行以下指令來啟動 GUI 介面：
```bash
python main.py
```

### 下載 MP3
1. 開啟應用程式後，在輸入框內輸入 YouTube 影片網址。
2. 點擊 `Download MP3` 按鈕。
3. 選擇下載目標資料夾。
4. 下載完成後，MP3 檔案將儲存在指定資料夾內。

## 注意事項
- 本專案是我紀錄學習成果所製作出來的發布地方。
- 若遇到 `ffmpeg` 錯誤，請確認已正確安裝並設置於系統 PATH。

## 貢獻方式
如果您有任何改進建議或發現錯誤，歡迎提交 Pull Request 或回報 Issue。

## 授權條款
本專案遵循 MIT 授權條款，詳見 [LICENSE](LICENSE) 檔案。

