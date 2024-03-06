# CoreXY_Plotter_GRBL


 [简体中文](README.md)				[English](README_en.md)



CoreXY结构写字机(绘图机)，支持换笔功能，自适应Z不需要对桌面进行调平。

写字机框架与传动部分设计来自Bilibili @大鱼DIY

本项目基于上述项目进行了部分优化





项目开发中



# 关于项目

主控板：Arduino Uno + CNC Shield + DRV8825 + 限位开关

固件：GRBL  https://github.com/grbl/grbl

上位机：GRBL-Plotter  https://github.com/svenhb/GRBL-Plotter



外型尺寸: 500\*320\*150mm

行程： X316mm Y206mm Z18mm



特性功能:

1. 换笔(你可以用一个G-code文件画出拥有多种颜色的图案)
2. 自动回零(绘图仪带有XY轴的限位开关，允许使用者使用上位机中的回零功能进行回零)
3. 自适应Z轴(自适应Z不需要对桌面进行调平，只需要将笔夹到大概合适的位置)



敬请期待......
