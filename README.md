# 附近旅館搜尋

用 GPS 或輸入的地點，搜尋附近的飯店、民宿、青年旅館、汽車旅館。

- 資料：OpenStreetMap（Overpass API），地址搜尋：Nominatim，地圖：Leaflet
- 完全免費，不需要任何 API 金鑰
- 評分、照片、房價：點每筆結果的「Google 地圖看評價」

單一檔案 `index.html`，直接放到任何 HTTPS 靜態空間（例如 GitHub Pages）即可使用。
GPS 定位只能在 HTTPS 或 localhost 下使用。

本機測試：

```bash
npx http-server -p 8765
```
