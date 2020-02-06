# 18  日期函数

1. `TODAY()` `NOW()`

2. `YEAR(serial_number)` `MONTH(serial_number)` `DAY(serial_number)`

   **serial_number**  日期 

3. `DATE(year, month, day)`

4. 本月最后一天  `DATE(year, month+1, 0)`

   下个月的第0天 = 本月最后一天

5. **DATEDIF**  计算两个日期之间相隔的天数

   DATEDIF(start_date, end_date, unit)`

6. **NETWORKDAYS**  净工作日数量

   `NETWORKDAYS(start_day, end_day, [holidays])`

   **holidays**  自定义假日列表

7. **IF**

   `IF(logical_test,[value_if_true],[value_if_false])`

8. `TEXT(value, format_text)`

   星期  `TEXT(TODAT(),"aaaa")`  ”星期五“

   ​		  `TEXT(TODAY(), "aaa")`  "五"

9. **开始 > 条件格式 > 新建规则 > 使用公式确定要设置格式的单元格**

   **开始 > 条件格式 > 管理格式 > 上移/下移**

10. **Ctrl ;** 快速录入系统当前日期

    **Ctrl ；[space] Ctrl Shift ;** 快速录入系统当前时间

    （不会随着刷新而更新）

11. **F9**  刷新

