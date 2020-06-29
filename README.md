# SVG Percentage Donut Chart
very very simple svg donut chart!

# ヒント
[参考先](https://link.medium.com/YbdWN3m3H7)を読んだら分かるが、  
`d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831"` というおまじないめいた記述がコア。

viewBoxのサイズを36x36にして、d属性を前述の値にすることで、_stroke-dasharray_の値を100分率と対応するようにしている。

# reference
- [How to code a responsive circular percentage chart with SVG and CSS.](https://link.medium.com/YbdWN3m3H7)
