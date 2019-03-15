## 双向反射分布函数BRDF

描述光在不透明表面反射的分布函数

`$$f(l,v) = {{D(h) \cdot F(v, h) \cdot G(l, v, h)} \over {4 \cdot (n \cdot l) \cdot (n \cdot v)}}$$`

`$D(h)$`是法线分布函数
`$F(v, h)$`是菲涅耳函数
`$G(l, v, h)$`是双向阴影遮挡函数
