# Homework1
#### 知识点：
回顾了渲染流水线中顶点的空间变换过程：模型变换-观察变化-投影变换-屏幕映射

其中关于投影部分UnityShader精要中公式推导和101所用的常量不同，裁剪矩阵M-frustum（平截头体）会改变空间的旋转性，从右手坐标系转化为了左手坐标系。注：101课程中n和f变量的值是小于0的，而书上的near和far是绝对值。

关于透视投影和不同推到方式转换：https://zhuanlan.zhihu.com/p/122411512

#### 主要任务
实现三角形绕Z轴的旋转 `./Rasterizer −r 30`，旋转30度结果如下：

![](../Recordings/output.png)

刚开始旋转的角度并不对，是因为没有转化为弧度制。同时为了验证结果的正确性找到一款3D绘图软件：https://www.geogebra.org/

https://github.com/kaya-dong/Game101_work/assets/130848123/86c593ad-68d9-427a-bfa1-6e87730746c1

`./Rasterizer` A（+10°）D（-10°）键进行旋转：

https://github.com/kaya-dong/Game101_work/assets/130848123/c6e02292-5a72-4591-a1b3-63e0900c5ff7

