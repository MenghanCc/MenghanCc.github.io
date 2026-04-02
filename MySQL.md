### MySQL学习记录

#### 基础篇



![image-20260318163750973](C:%5CUsers%5Clenovo%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20260318163750973.png)



DQL语句的执行顺序：

1.表名列表FROM

2.条件列表WHERE

3.分组字段列表GROUP BY

4.字段列表SELECT

5.排序字段列表ORDER BY

6.分页参数LIMIT



##### 约束

约束是作用于表中字段上的规则，用于限制存储在表中的数据。

目的：保证数据库中数据的正确、有效性和完整性。



笛卡尔积: 笛卡尔乘积是指在数学中，两个集合A集合和B集合的所有组合情况。

在多表查询中，我们是需要消除无效的笛卡尔积的，只保留两张表关联部分的数据。



联合（union）查询中，两次查询选择的字段数量应一致。

union去重，union all不去重

