# Gemini 圖片浮水印處理工具（GitHub Pages 版）

這是為課堂分享整理的純靜態版本。圖片會在使用者自己的瀏覽器中處理，不會上傳到網站伺服器。

## 上傳到 GitHub

1. 在 GitHub 建立一個新的 Public repository，名稱建議使用 `gemini-watermark-remover`。
2. 按 **Add file → Upload files**。
3. 將本資料夾內的所有檔案與 `workers` 資料夾一起拖曳上傳；不要只上傳外層資料夾。
4. 按 **Commit changes**。
5. 開啟 **Settings → Pages**。
6. 在 **Build and deployment** 下將 Source 設為 **Deploy from a branch**。
7. Branch 選 **main**，資料夾選 **/(root)**，再按 **Save**。

完成後的網址通常會是：

`https://你的帳號.github.io/gemini-watermark-remover/`

## 使用方式

- 支援 JPG、PNG、WebP；可一次選擇多張圖片。
- 單張圖片上限為 20 MB。
- 處理後可比較原圖與結果，並下載或複製圖片。
- 請只處理自己產生或已取得授權的圖片。

## 授權與原作者

本版本修改自 [GargantuaX/gemini-watermark-remover](https://github.com/GargantuaX/gemini-watermark-remover)，依 MIT License 授權。原始授權聲明保留於 `LICENSE`。
