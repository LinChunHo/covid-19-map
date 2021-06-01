# COVID-19 地圖製作

## 設計思考
- 同理(Emphathize)
    - 地圖使用經驗
- 定義(Define)
    - 資訊需求
    - 互動
- 發想(Ideate)
    - GIS資料收集
    - 圖資來源
    - 視覺化呈現方式
    - 靜態或互動
- 原型(Prototype)
    - QGIS 靜態
    - 地圖網站
    - SVG互動
- 測試(Test)
    - QGIS/openstreetmap/SVG
        - coding
        - gitpage

### 「參考資料」

- [以「使用者」為中心的設計思考5步驟](https://medium.com/as-a-product-designer/%E4%BB%A5-%E4%BD%BF%E7%94%A8%E8%80%85-%E7%82%BA%E4%B8%AD%E5%BF%83%E7%9A%84%E8%A8%AD%E8%A8%88%E6%80%9D%E8%80%835%E6%AD%A5%E9%A9%9F-13660bb1108f)
## 先備知識
- 地理資訊系統GIS
    - [教科書](https://www.books.com.tw/products/0010682141)
    - 座標系統
    - 圖層
    - 資料格式
    - 資料呈現
    - [QGIS](https://www.qgis.org/en/site/)

- 資料處理技術
    - [geojson](https://geojson.org/)
    - [geopandas](https://geopandas.org/)
    - 資料轉檔
    - 網路爬蟲
    - [資料可視化](https://d3js.org/)

- Web-based Programming
    - HTML/CSS/JS
    - Python
    - [git](https://git-scm.com/)

### 「參考資料」
- [geojson.io]((https://geojson.io/#map=2/20.0/0.0))
- [30天精通GIS資料分析-使用Python 系列](https://ithelp.ithome.com.tw/users/20107816/ironman/1797)
- [Git入門指南](https://backlog.com/git-tutorial/tw/)
- [SVG 與 D3.js 系列](https://ithelp.ithome.com.tw/users/20083608/ironman/838)

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
    
    - 「參考資料」
        - [mapbox studio](https://www.youtube.com/watch?v=fpl4no2T1sQ&list=PLOlUoOtyTOXh8bwQ6MM7p7l6gfo4j8hch)
        - [OSM](https://www.openstreetmap.org/#map=9/22.7002/121.0281&layers=N)
        - [SVG 完整教學 31 天](https://www.oxxostudio.tw/articles/201410/svg-tutorial.html)
        - [D3、Vue 畫一個台灣地圖](https://www.letswrite.tw/d3-vue-taiwan-map/)
        - [老闆 來點寇汀吧 讓我們來操控地圖顯示對應天氣吧！！](https://www.facebook.com/bosscodingplease/videos/1842446952675383/)
- Step 2：準備資料集
    - 資料來源
        - [疾管署](https://nidss.cdc.gov.tw/)
    - 資料處理
        - [google excel](https://support.google.com/docs/answer/6000292?co=GENIE.Platform%3DDesktop&hl=zh-Hant)

    - 「參考資料」
        - [爬蟲](https://jupyter.org/)
        
    
- Step 3：資料可視化方式
    - 地圖網站
        - 互動
    - 圖表SVG
        - 互動
            - [D3js](https://d3js.org/)
            - [Vue](https://vuejs.org/)
            - [plotly](https://plotly.com/python/)

    - 「參考資料」

- Step 4：合併圖資資料集
    - 使用地圖網站

    - 使用SVG/PNG
        - [SVG editor](https://github.com/SVG-Edit/svgedit)(標籤設定)
        - Vue
        - D3js
    - 取得資料方式(外部)
        - [FASTAPI](https://fastapi.tiangolo.com/)   
        - 公用API

    - 「參考資料」

- Step 5：實作部署
    - [平台選擇 gitpage](https://pages.github.com/)
    - [heroku](https://www.heroku.com/)

    - 「參考資料」

