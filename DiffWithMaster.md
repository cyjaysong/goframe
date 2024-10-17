# 相较于主分支变更内容
- 1、Model 默认不执行Safe函数，保证链式调用不重复构建新的Model指针对象

- 2、gredis Option 构建结构调整

- 3、grpool 添加 WithParams 特性支持

- 4、gdb 添加 Exist 查询支持

- 5、gdb 增加NewCounter函数

- 6、gdb 事务Rollback时判断事务是否已关闭