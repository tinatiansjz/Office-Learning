# 15  文本函数

1. 分列缺点：① 无法一劳永逸自动做；② 可能会覆盖老数据

2. **LEFT / RIGHT / LEN / LENB**

   `RIGHT(text, [num_chars])`  文本拆分

   `LEFT(text, [num_chars])`  文本拆分

   `LEN(text)`    一个中文汉字记为1个字符数

   `LENB(text)`  一个中文汉字记为2个字符数

3. **FIND**  文本定位

   `FIND(find_text, within_text, [start_num])`

   **start_num**   within_text 中的首字符是编号为 1 的字符,假定其值为 1。

4. **MID**  文本拆分

   `MID(text, start_num, num_chars)`

5. **TRIM** 除了单词之间的单个空格之外，移除文本中的所有空格

   `TRIM(text)`

6. **&**  连接符

7. **TEXT**

   `TEXT(value, format_text)`

8. `CHAR(10)`  强制换行

9. **Ctrl E**  快速填充使用条件

   - Excel 2013/2016
   - 必须在第一行给出填充规律

