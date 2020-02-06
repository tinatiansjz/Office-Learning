# 17  查找函数

1. 阶梯查询 **LOOKUP**

   `LOOKUP(lookup_value, lookup_vector, [result_vector])`

2. **F4**  快速切换$所在位置 (挂锁头)

   **双击**，列自动填充

3. 查找函数 **VLOOKUP**  [vertical]

   `VLOOKUP(lookup_value, table_array, [range_lookup])`

   `VLOOKUP(查找对象, 查找区域, 返回数据值列表, 匹配程度)`

   `VLOOKUP(找谁，哪里找，返回第几列，0)`

   `table_array` 必须把“找谁”放在第一列，然后从左到右，拖拽选择区域。

   `col_index_num`  在被查找的数据区域中，从左到右数，返回第几列，就写几

   `range_lookup`  True-近似匹配，False-精确匹配

   - 查找信息
   - 核对信息

4. 数据清洗（前后空格）**TRIM**

   `TRIM(test)`

5. **IFERROR**

   `IFERROR(value, value_if_error)`

6. 利用条件格式，让结果更直观

7. 合并的单元格的信息只保留在左上角的子单元格中，其他的子单元格中没有内容。

   - 取消合并单元格
   - **Ctrl** + **G**  快速定位，定位到 **空值**
   - **= ↑** 等于上方单元格
   - **Ctrl Enter** 批量运用

8. 一对多查找

   新建辅助列

9. **HLOOKUP**   [horizontal]  横向查找