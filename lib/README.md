# 从零写一个轮播组件

学会分析需求，从一个 mvp 的最小版本起去迭代。

## 需求分析

1. 能轮播（P0）
    1. 展示一组图片
    2. 没个？秒通过动画播放下一张图片
        1. 选择合适的时间和动画形式（P2）
    3. 循环播放（P1）
    4. 展示指示器（P1）
    5. 展示文字标题（P1）

2. 能点击（P0）
    1. 点击图片，跳转链接
    2. 点击图片，跳转链接

3. 手势/鼠标操作轮播（P1）
    1. 拖拽图片，跟随手指/鼠标移动
    2. 停止拖拽，播放动画弹到最近的一张图片

4. 鼠标悬停展示左右操作按钮（P1）
    1. 鼠标悬停, 展示翻页按钮
        1. 首张、末张图片不显示操作按钮（P2）
    2. 点击左按钮前进，点击右按钮后退
