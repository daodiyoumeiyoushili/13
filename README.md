项目简介
这是一个简单的命令行扫雷游戏，玩家的目标是在一个棋盘上找出所有非雷格子而不触发任何雷。

功能
棋盘初始化: 提供了初始化棋盘的功能，可以设置棋盘上所有格子的初始值。
显示棋盘: 在命令行上显示当前的棋盘状态。
布置雷: 在棋盘上随机布置雷。
计算雷数: 为每个非雷的格子计算周围的雷数。
查找雷: 允许玩家输入坐标，查看该坐标是否为雷。如果是，游戏结束；否则，显示该格子周围的雷数。
菜单界面: 提供一个简单的菜单，允许玩家选择开始游戏或退出。
如何编译和运行
确保您的系统上已安装了C语言的编译器。

将上述代码保存为 minesweeper.c。
在同一目录下创建一个 game.h 文件，包含所需的函数原型。
使用编译器编译 minesweeper.c，例如使用gcc： gcc minesweeper.c -o minesweeper。
运行程序： ./minesweeper。
根据菜单提示开始游戏或退出。
使用说明
启动程序后，您会看到一个菜单。选择 "1. play" 开始游戏或 "0. exit" 退出。
在游戏中，根据提示输入您想要查找的坐标。
如果您选择的坐标是雷，游戏结束。否则，您会看到该坐标周围的雷数。
游戏的目标是找出所有非雷格子。
开发和贡献
如果您有任何建议或想要添加新的功能，欢迎创建PR。
