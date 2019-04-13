# GIS-FULLSTACK
gis全栈资料整理

## 开源GIS图形引擎或小型GIS可视化库
- [harp.gl](https://github.com/heremaps/harp.gl)：一个基于webgl的实验性的和正在开发的开源三维地图渲染引擎，由HERE地图开发
- [3d-earth](https://github.com/cheeaun/3d-earth)：用MapboxGL,d3.js和three.js结合起来做的三维球可视化
- [wrld.js](https://github.com/wrld3d/wrld.js)：同样也是基于webgl的3D地图库，基于leaflet.js，但是需要注册账户，可能类似于mapbox那种吧
- [realtime-webgl-globe](https://github.com/askmike/realtime-webgl-globe)：基于three.js，一个很小型的地球库，不过时间久，16年时候开发的了


## GIS数据解析
- [osg-serializer-js：纯JavaScript模块，用于读取.osgb和.osgt文件](https://github.com/eran-pinhas/osg-serializer-js)
- [geotiff.js：一个小型库，用于解析TIFF文件以进行可视化或分析。](https://github.com/geotiffjs/geotiff.js)


## 三维地形服务
- Cesium地形服务：https://3d.geo.admin.ch/1.0.0/ch.swisstopo.terrain.3d/default/20160115/4326


## GIS数据展示工具
- [一个用来展示geojson数据的在线地址，可配置样式与高度](https://maptime-ams.github.io/geojson-3d/)
- [在地图上绘制图形，并可以对其以geojson的方式进行下载](https://labs.mapbox.com/svg-to-geojson/)


## GIS数据处理
- [用python编写的可以生成cesium的高度图和地形瓦片](https://github.com/giohappy/gdal2cesium)
- [gdal2tiles：将栅格数据转换成TMS或者XYZ瓦片](https://github.com/Luqqk/gdal2tiles)
- [geojson数据处理相关库](https://github.com/tmcw/awesome-geojson)


## 矢量瓦片生成处理相关
- [从postgis数据库轻松生成mapbox矢量切片（没有mapnik依赖）](https://github.com/philippeauriach/vector-tiles-generator)
- [tilemaker：从.osm.pbf文件中创建mapbox类型的矢量瓦片 ](https://github.com/systemed/tilemaker)
- [gdal2mbtiles：把影像转成mbtiles文件](https://github.com/ecometrica/gdal2mbtiles)
- [tilegrinder：一个node库，用于在MBTiles容器中轻松更改Vector Tiles的某些逻辑](https://github.com/rastapasta/tilegrinder)
- [用于从矢量地图数据和Mapbox GL样式来生成栅格地图图块](https://github.com/CMU-CREATE-Lab/tile-generation)
- [tileshrink：用于减少和简化MBTiles容器中的Vector Tile功能的CLI工具](https://github.com/rastapasta/tileshrink)
- [fresco：矢量瓦片样式编辑器，包括mapbox矢量瓦片样式、geojson样式等](https://github.com/go-spatial/fresco)
- [tegola：用Go编写的Mapbox矢量瓦片服务器](https://github.com/go-spatial/tegola)