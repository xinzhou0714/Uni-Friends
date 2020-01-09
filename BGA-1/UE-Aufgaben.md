# Übung-题型整理

Übung总共六次，由于A、B组分组不同，题目会不同但题型是相同的。

**以下整理均基于B组**

[TOC]





## Übung01_Optik und Beleuchtung 

光学和照明

---

题型一：成像定律(Abbildungsgesetz)

题型二：光圈(Blende)

题型三：光照条件(Beleuchtung )

## Übung02_Ni Vision Assisstant

图像预处理

---



题型一：Look-up-table操作

题型二：灰度直方图

## Übung03_Objektsegmentierung  

对象分割

---

01 Welche Filter ohne Faltungsoperator

- [ ] A. Sobel

- [x] B. Hoch Pass

- [ ] C. Canny

- [ ] D. Laplace

  

02  Welche Filter ist 2.Ordnung

- [x] Lapace-Filter

其他选项忘记

03  你在一个亮灰色的背景(Hellgraue Hintergrund)上面一个一个暗灰色的物体(Dunkelgraue Objekt),通过Sobel算子你成功的

下面那个操作会使你的边缘检测结果不再稳定(Robust)

- [ ] A,将图像旋转九十度
- [x] B.Kontrast erhöhen durch Histogrammspreizung 直方图均衡化
- [ ] C将所有灰度值提高10
- [ ] D.上面三种方法对结果都没有影响

解析



04关于Canny-algorithmus下面哪个说法是错误的

- [x] Filter in `2.Ordnung` ermöglich  xxxxx

解析:Canny算法没有用到二阶算子





## Übung04_Hough Transformation 

霍夫变换

---

题型1：霍夫变换，给原图，选参数空间的图

可能的坑点坐标系原点(Ursprung)的选择吗角度Theta的正方向选择(可以是顺时针Uhrzeitsinn)

题型2：Matlab编程相关

下面哪个关于MATLAB中霍夫变换的说法是**错误**

- [x] wenn du numpeaks einstellen wird immer so viele Kanten
- [ ] [-90:45:89] 那么只会检测水平(horizontal)竖直(vertikal)和对角线方向的直线
- [ ] 

解析:`numpeaks` 仅调节期待返回的直线条数的最大值，且直线条数还与阈值(Thredhold)相关



## Übung05_Rauschen 

噪声

---



## Übung06_Textureigenschaften  

纹理

---

