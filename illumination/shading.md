## 高洛德着色（Gouraud shading）

也被称为逐顶点光照（per-vertex lighting），只计算每个顶点的光照信息，然后在渲染图元内部进行线性插值的着色方法

光照计算在顶点着色器中进行

---

## Phong着色（Phong shading）

也被称为逐像素光照（per-pixel lighting），通过对渲染图元的顶点法线进行插值获得像素的法线，并对每个像素进行光照计算的着色方法

光照计算在像素着色器中进行
