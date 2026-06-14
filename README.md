# 麻將連連樂

純前端 HTML/CSS/JavaScript 遊戲，可直接部署到 GitHub Pages。

## 內容

- 麻將連連樂主遊戲
- 30 關關卡設計
- 3 的倍數關卡為獎勵關卡
- 獎勵關卡完成後進入麻將賓果 Bonus
- 英雄榜紀錄使用瀏覽器 localStorage
- 手機版介面已調整

## 本地開啟

在此資料夾執行：

```bash
python -m http.server 5180
```

或使用任何靜態網站伺服器開啟：

```text
http://127.0.0.1:5180/index.html
```

## GitHub Pages

1. 將本資料夾內容上傳到 GitHub repository。
2. 到 repository 的 Settings。
3. 打開 Pages。
4. Source 選擇 main branch / root。
5. 發佈後開啟 GitHub Pages 網址即可遊玩。

## 注意

- `index.html` 是入口檔。
- `bingo-bonus/` 是獎勵關卡使用的麻將賓果。
- `tiles_fast/` 是遊戲中使用的輕量牌圖。
- `tiles_generated_aligned/` 是高清牌圖，Bonus 瞇牌會使用。
