# GPT Sites 訪視網站備份

- Sites 版本：80
- 備份日期：2026-10-19
- 已部署網址：https://tnmr-115-disaster-visit.c-h-hsiang0422.chatgpt.site
- Sites source commit：`3ae52e59e91bbc6474bbb49bf8dfaee9440ef035`
- GitHub 3D 地圖基準 commit：`da7c4c0f4c3406050faa1598974a5cad58919bf2`
- 3D 地圖 Git blob：`6ea6c3b98d511ce2928fc188259ad4610eb03e25`
- 備份封存檔：27,142,723 bytes；SHA-256 `eaa6a304304df228e7e9bd41dc2194ca2f8cf1468bcbd4a3363eabdc30d05c61`

本目錄將完整的 Sites 靜態發布檔（首頁、互動式 3D 地圖、PDF、簡報圖片及 SVG）與 `.openai/hosting.json` 封存在 `gpt-sites-v80.zip.part-001` 到 `part-013`。下載全部 13 個分塊後，依檔名順序合併還原：

```sh
cat gpt-sites-v80.zip.part-* > gpt-sites-v80.zip
shasum -a 256 gpt-sites-v80.zip
unzip -t gpt-sites-v80.zip
```

合併後 SHA-256 應為上述值。GitHub Pages 原始版本與更早的地圖修改仍保留在此儲存庫的提交歷史中.
