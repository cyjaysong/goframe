# 相较于主分支变更内容
- 1、Model 默认不执行Safe函数，保证链式调用不重复构建新的Model指针对象

- 2、gdb 增加NewCounter函数

- 3、gdb 事务Rollback时判断事务是否已关闭

- 4、gtime.Format 废弃标注，gtime.Format与标准库`time.Time`的 Format 方法冲突容易造成生产事故

- 5、Redis 添加 GetConfig()