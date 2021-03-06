# 2048-online

## 简介
2048游戏，在网上可以两个人同时玩，实时显示对方的动作和得分。

## 游戏规则

* 使用键盘上下左右键控制方块的整体移动过方向
* 如果相同方向上相邻的数字相同就相加合并为一个方块
* 移动完成后，随机在空格中填入2或者4
* ...

## 对战胜负规则

### 无可移动空格
判定为失败，另一方获胜

### 完成目标，获得2048
判定为胜利

### 投降
判定为失败，另一方获胜

### 网络断线
判定为失败，另一方获胜

### 超时不操作
判定为失败，另一方获胜


## 技术实现

* 同步实时数据 `Firebase`或`Wilddog`.
* 控制脚本 `React`
* 样式 `CSS`
* 页面 `HTML`


## 第三方库文件 
libs
├── JSXTransformer.js
├── jquery.js
├── react.js
└── wilddog.js

## License

MIT
