本仓库提供了本地运行和调试的方法

### 运行方法
#### 一、配置core模块
```
git submodule init
git submodule update
```
#### 二、运行main函数
```
python main.py ---dir_pacman=路径1 ---dir_ghosts=路径2
```
其中路径1是**包含了pacman的ai_func函数**的路径，路径2是**包含了ghosts的ai_func函数**的路径

运行过程默认0号玩家为卷王，1号玩家为幽灵

### 调试方法
可在./replay/replay.json中获取到回放文件

[Rollman游戏](https://www.saiblo.net/game/42)网页播放器一栏可读取本地回放文件并载入网页播放器