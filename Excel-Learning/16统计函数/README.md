# 16  统计函数

1. 透视表自动统计，规范的数据源是前提。

   老表留坑，函数来帮。

2. 连续区域表示：**(首格) : (末格)**   [eg: **F2:F7**]

   只选所选单元格：**F2, F7**

3. **公式 > 自动求和**

4. 五类基础的统计函数 条件统计函数

   - `SUMIFS(sum_range, criteria_range1, criteria1[, criteria_range2, criteria2])`

     `SUMIFS(求和区域, 条件区域1, 条件1...)`

     多条件求和；模糊条件求和（用 ***** 通配符标识任意内容，**&** 为连接符）

   - `AVERAGEIFS(average_range, criteria_range1, criteria1[, criteria_range2, criteria2])`

   - `COUNTIFS(criteria_range1, criteria1[, criteria_range2, criteria2])`

5. **F4**  快速切换$的所在位置，锁住特定行列

6. 自动求和 **Alt** + **=**

7. 套用超级表 **开始 > 套用表格格式**

   **设计 > 汇总行**