# py3_postgresql
Python3 postgresql 增删改查简单封装

## 使用说明

```sql
-- 初始化实例
db = PostgreSQLDB()

-- 插入数据
cs = db.insert(table="asin", asin=asin, title="标题", stars=4.3)
print(cs)

-- 删除数据
cs = db.delete(table="T1", where="Id = 2")
print(cs)

-- 更新数据
cs = db.update(table="T1", Name="Python测试3", Sex="man", where="Id in(1,2)")
print(cs)

-- 查询数据
cs = db.getAll(table="asin", where="1")
print(cs)

```
