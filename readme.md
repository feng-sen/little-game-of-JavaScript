## 项目说明

---


### 游戏说明
    >本游戏是经典的贪吃蛇游戏，通过点击开始游戏按钮可以开始游戏
    >操作：通过 ↑ ↓ ← → 键来控制贪吃蛇的行走路线
    >游戏规则: 1、撞到墙体或者自己身体则游戏结算，回到初始界面
            > 2、撞到苹果则会变长一个单位，苹果重新刷新
            > 3、游戏过程中点击游戏界面会出现三角启动按钮同时暂停游戏
            > 4、再次点击三角启动键可以继续开始游戏
            > 5、游戏过程会不断累积分数，吃到一个苹果加一分

---
### 对象

    1.Square: 这是食物和蛇的组成部件，可以看作是蛇的父一级构造函数
                <属性>：
                    x：横坐标
                    y：纵坐标
                    class： 方块的CSS类
                    viewContent: 方块对应的Dom元素节点
                    parent:方块的父级Dom节点

                <方法>
    2.Snake : 这个是蛇的整体，由多个Square对象组成