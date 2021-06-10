# Day 3

## Tips

关于Mapping注解的使用, 滥用 `@RequestMapper` 在生成文档时会产生多余的用法条目

### 今日内容

1. 数据库的创建
2. 数据表的设计与创建

> 使用`int`作为主键可以提高查询效率, 其与MySQL底层的Btree实现有关

3. 测试数据的生成 (可以使用 Python 的 faker 模块)
4. ★ 由于 DAO 中的方法与 Mapper 使用id一一对应, 所以DAO中的方法不能重载
5. 课堂问题的思考:
   - **int主键自增到极限的情况如何解决**
     - 引入新的主键 ? 在数据访问量少的时期使用新的列进行替换
  
   - **如何保证连续的id**
     - 据我所知, MySQL在处理连续的多次分配新id时, 其提供的预留id位是递增的, 这样造成了较多的空缺, 可以在每次进行insert更新之后刷新当前的id位置.
  
6. DAO的扫描, 在启动类中添加`@MapperScan`的注解. 在Springboot中可以在每个DAO类上面添加`@Mapper`的注解.
7. 事务控制
  - 原子性 (Atomicity)
  - 一致性 (Consistency)
  - 隔离性 (Isolation)
  - 持久性 (Durability)
  > Tips
  > 查询不添加事务的效率更高. 但是 `GET` 方法添加事务的原因是能够更好地发挥事务的传播特性


### 今日收获
