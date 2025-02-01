# YT to MP3

YT to MP3 是一個簡單易用的工具，能夠將 YouTube 影片轉換為 MP3 音訊檔案，適用於個人備份與離線收聽。

## 功能特色
- 下載 YouTube 影片並轉換為 MP3
- 支援高品質音訊輸出
- 簡單易用的指令列介面
- 依賴 `yt-dlp` 進行下載與轉換

## 安裝方式
### 先決條件
請確保您的環境已安裝以下軟體：
- Python 3.x
- `yt-dlp` 套件
- `ffmpeg` (用於音訊轉換)

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
### 指令列使用
執行以下指令來下載並轉換 YouTube 影片為 MP3：
```bash
python yt_to_mp3.py <YouTube 影片網址>
```
例如：
```bash
python yt_to_mp3.py https://www.youtube.com/watch?v=dQw4w9WgXcQ
```

### 下載後的檔案位置
轉換後的 MP3 檔案將儲存在 `output/` 資料夾內。

## 注意事項
- 本專案僅供個人備份與學習使用，請勿用於非法下載或侵害版權。
- 若遇到 `ffmpeg` 錯誤，請確認已正確安裝並設置於系統 PATH。

## 貢獻方式
如果您有任何改進建議或發現錯誤，歡迎提交 Pull Request 或回報 Issue。

## 授權條款
本專案遵循 MIT 授權條款，詳見 [LICENSE](LICENSE) 檔案。

