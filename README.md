# COVID-19 地圖製作

## 設計思考


- 「參考資料」
## 先備知識
- 地理資訊系統GIS
    - 教科書
    - 座標系統
    - 圖層
    - 資料格式
    - 資料呈現
    - QGIS

- 資料處理技術
    - geojson
    - geopandas
    - 資料轉檔
    - 網路爬蟲
    - 資料可視化

- Web-based Programming
    - HTML/CSS/JS
    - Python
    - git

## 實作流程
- Step 1：準備底圖
    - 使用地圖網站
        - 圖資來源
            - [內政部](https://data.gov.tw/dataset/7441)
            - [網路資源](https://sheethub.com/ronnywang/%E9%84%89%E9%8E%AE%E5%B8%82%E5%8D%80%E8%A1%8C%E6%94%BF%E5%8D%80%E5%9F%9F%E7%95%8C%E7%B7%9A?page=5)   
        - [Google Map](https://www.google.com/maps/about/mymaps/)
        - [OpenStreetMap](https://www.openstreetmap.org/#map=9/22.7002/121.0281&layers=N)
            - [josm](https://josm.openstreetmap.de/)
        - [mapbox](https://www.mapbox.com/)
        - 圖資轉檔
            - [mapbox studio](https://www.mapbox.com/mapbox-studio)

    - 使用SVG
        - 圖資來源
            - [內政部](https://data.gov.tw/dataset/7441)
        - 圖資轉檔
            - [mapshaper](https://mapshaper.org/)
            - [jupyter notebook]()
                - geojson
                - geopandas
                - pandas    
                - DataFrame
                    - 讀取 寫入
                    - 選取 行 列
                    - 新增 行 列
                    - 刪除 行 列
                    - 修改 行 列
    
    - 「參考資料」
        - mapbox studio [客製化所需地圖](https://www.mapbox.com/mapbox-studio)
        - OSM [OSM](https://www.openstreetmap.org/#map=9/22.7002/121.0281&layers=N)
        - [svg](https://www.oxxostudio.tw/articles/201410/svg-tutorial.html)
        
        - [互動](https://www.letswrite.tw/d3-vue-taiwan-map/)

        - leaflet js 互動
        - openlayer js
        - mapbox GL js
        - D3 js
        - Vue js

- Step 2：準備資料集
    - 資料來源
        - [疾管署](https://nidss.cdc.gov.tw/)
    - 資料處理
        - [google excel]()

    - 「參考資料」
        - 爬蟲
        
    
- Step 3：資料可視化方式
    - 地圖網站
        - 互動
    - 圖表SVG
        - 互動
            - [D3js]()
            - [Vue]()
            - [plotly]()

    - 「參考資料」

- Step 4：合併圖資資料集
    - 使用地圖網站

    - 使用SVG/PNG
        - [SVG editor](https://github.com/SVG-Edit/svgedit)(標籤設定)
        - [Vue]()
        - [D3js]()
    - 取得資料方式(外部)
        - [FASTAPI]()    
        - [公用API]()

    - 「參考資料」

- Step 5：實作部署
    - [平台選擇 gitpage]()
    - [heroku]()

    - 「參考資料」
    test
