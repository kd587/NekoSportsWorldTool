# 可选补充地图

## 大连东软信息学院软件园校区田径场

`dalian-neusoft-stadium.osm` 包含田径场周边的公开 OSM 道路、建筑，以及从可见跑步场地补绘的 28 节点跑道闭环。原 OSM 下载只包含外围道路，导致田径场部分点位距离道路超过 40 米；重新下载同一数据不能补全未绘制的跑道。

在“路网”页核对校区后，点击“加载大连东软田径场补充地图”。地图内嵌在 EXE 中，不需要另外下载或选择 OSM 文件；加载后使用现有手动地图流程，保留真实道路模式。再回到“跑步”页刷新点位并核对预览。其他学校不会自动使用此地图，自动获取功能也不受影响。

这是按公开影像描绘的近似可跑步路线，未经实地 GPS 测量。约 427 米是补绘几何的计算长度，不代表田径场认证圈长。影像拍摄日期未确认，场地现状需使用者核对。地图不包含学校围栏，不确认校园边界；软件仍保留原有点位距离、连通性及服务端检查。

## 数据来源、许可与署名

此目录的地图数据与程序代码分开许可：地图按 [Open Database License 1.0（ODbL）](https://opendatacommons.org/licenses/odbl/1-0/) 提供。

- 周边道路和建筑：© [OpenStreetMap contributors](https://www.openstreetmap.org/copyright)。2026-10-26 读取的公开 OSM 数据；可通过 [OSM API](https://api.openstreetmap.org/api/0.6/map?bbox=121.527,38.893,121.532,38.897) 核对田径场附近现有数据。
- 跑道补绘来源：© [Esri World Imagery 及其影像贡献者](https://server.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer)，2026-10-26 读取，Web Mercator，zoom 19。像素到地理位置的转换采用服务的标准瓦片坐标；根据影像中可见红色跑步场地描绘，不是打卡点间插值。
- [Esri 的矢量描绘使用授权说明](https://wiki.openstreetmap.org/wiki/Esri)。本仓库分发的是矢量数据，不包含影像瓦片；补绘尚未上传到 OpenStreetMap。

地图不包含账号、密码、设备身份、会话或用户运动记录。当前版本的测试点位仅表示该公共田径场周边的地理位置。
