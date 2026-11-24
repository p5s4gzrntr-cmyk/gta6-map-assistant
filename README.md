# GTA6 地图助手

助手直接读取 Windows 屏幕上的游戏大地图。识别到已探索的区域后，它会把收藏卡、冥想点等收集品标在对应位置。点击标点或清单里的名称，可以查看地点说明和已有的参考图。

## 下载与使用

1. 从[最新发行版](https://github.com/p5s4gzrntr-cmyk/gta6-map-assistant/releases/latest)下载 `GTA6-Map-Assistant.exe`，在 Windows x64 上双击打开。
2. 在游戏里打开大地图，切到 **2D 俯视视角**，让地图界面在 Windows 屏幕上可见。只探索了一部分地图也可以，把已探索区域移入画面，方便助手对照道路或海岸线定位。采集卡是可选的。串流窗口或本机播放器呈现相同的地图界面时，助手也会尝试识别。当前版本以中文游戏地图页为识别参照，已在 Veyra 采集卡预览中实测。
3. 在地图助手中选择收集品类别。先根据地图标点到达附近，再点开名称，看清物品所在的建筑、楼层或地标。
4. 拿到物品后，勾选名称左侧的方框。打开「隐藏已收集点」，即可继续找下一处。收集进度保存在本机。

## 实机演示

[收藏卡 181 实机演示](https://github.com/p5s4gzrntr-cmyk/gta6-map-assistant/releases/download/v0.1.0/GTA6-Map-Assistant-Demo.mp4)是一段约 46 秒的 1080p 实录。玩家用助手定位到加油站，点开「收藏卡 181」，对照巨型杯子的参考图爬上屋顶，拾取「右翼侠（铜）」后回到清单打勾。地图标点、详情和勾选过程均由 NVIDIA 桌面录制捕获。

## 点位与语言

v0.3.8 收录 2,908 个点位，支持全图、附近和类别筛选。收藏、抢劫与犯罪、活动和服装可按类别浏览。随机事件和彩蛋可在分类顶部直接点选，现实景点位于「其他」。界面支持简体中文、繁體中文和 English。

在「服装」下选择休闲街头、运动装、正装、纪念品与泳装或旧货，再点店名，可查看 67 家门店的经营范围、已有的专属商品说明或找店地标。参考图按点位资料提供。

点位数据来自 fbritoferreira 的 Open GTA 6 Map，街区底图来自 GTADB.ORG 及其贡献者。两处上游数据采用 CC BY 4.0。助手对分类和地点说明做了本地化，转换了点位坐标，并从地图中提取了用于识别的特征。[Open GTA 6 Map](https://github.com/fbritoferreira/gta6) · [GTADB.ORG](https://github.com/rolux/gtadb.org) · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

部分点位、名称、地点说明及参考图来自[游民星空 GTA6 互动地图](https://www.gamersky.com/tools/map/?mapId=261)。

本工具由玩家制作。Grand Theft Auto 系列名称、游戏原画及游戏画面归各自权利人所有。
