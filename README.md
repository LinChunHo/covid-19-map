# covid-19-map
---

- step 1 準備底圖 （ex : tanwan 鄉鎮區）
    - 資料來源 [高大 土木](https://sheethub.com/ronnywang/%E9%84%89%E9%8E%AE%E5%B8%82%E5%8D%80%E8%A1%8C%E6%94%BF%E5%8D%80%E5%9F%9F%E7%95%8C%E7%B7%9A?page=5)

    - mapbox studio [客製化所需地圖](https://www.mapbox.com/mapbox-studio)
    - OSM [OSM](https://www.openstreetmap.org/#map=9/22.7002/121.0281&layers=N)

    - leaflet js 互動
    - openlayer js
    - mapbox GL js

- step 2 準備資料集 （ex : 鄉鎮區 統計資料）
    - geojson
    - geopandas
    - DataFrame
        - 讀取 寫入
        - 選取 行 列
        - 新增 行 列
        - 刪除 行 列
        - 修改 行 列
    
- step 3 資料可視化方式
    - 網頁 js
    - 圖表
    - 文數字
- step 4 合併圖資資料集
    - SVG PNG
    - sever/client
- step 5 實作發布資料
    - 平台選擇 github