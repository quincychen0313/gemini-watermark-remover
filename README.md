# Gemini 圖片與影片浮水印處理工具（GitHub Pages 版）

這是為課堂分享整理的純靜態版本。圖片與影片都在使用者自己的瀏覽器中處理，不會上傳到網站伺服器。

## 更新現有 GitHub Repository

1. 在 GitHub Repository 按 **Add file → Upload files**。
2. 將本資料夾內的所有檔案與資料夾一起拖曳上傳。
3. 確認 `index.html`、`video-preview.html`、`models`、`onnxruntime`、`workers` 都有出現在上傳清單。
4. 按 **Commit changes**。同名檔案會更新，新增檔案會直接加入。
5. 等待 GitHub Pages 重新部署完成。

請上傳解壓縮後「資料夾裡面的內容」，不要只上傳 ZIP 或多包一層外部資料夾。

## 使用方式

- 圖片支援 JPG、PNG、WebP，可一次選擇多張。
- 影片支援 MP4、WebM、MOV，建議使用最新版 Chrome 或 Edge。
- 沒有設定固定的使用者檔案大小上限；實際處理能力取決於裝置記憶體、影片長度與解析度。
- 影片會在本機逐格處理，長片或高解析度影片需要較長時間。
- 此網頁上傳版固定使用相容性較高的 WebAssembly 路徑，已排除 GitHub 瀏覽器上傳容易失敗的選用 WebGPU 大型檔案。
- 請只處理自己產生或已取得授權的圖片與影片。

## 授權與原作者

本版本修改自 [GargantuaX/gemini-watermark-remover](https://github.com/GargantuaX/gemini-watermark-remover)，依 MIT License 授權。原始授權聲明保留於 `LICENSE`。
