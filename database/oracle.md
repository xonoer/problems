- copy specified records from a table to another table already exists|复制一个表中的数据到另一个已创建的表中:
-insert into table 1 (column1,column2,column3,..) select col1,col2,col3,.. from table2 
- 视图中包含集合操作,distinct等语句时不能进行数据更新操作
可以在视图上加个字段,表明数据是从那个基础表里取出来的,然后根据这个去直接操作基础表达到想要的功能.
- 