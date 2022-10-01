# Pandas_learning
This is a file for testing Pandas

Wrote some examples for learning Pandas

Series类型可以创建的类型：
- Python列表，index与列表元素个数一致
- 标量值，index表达Series类型的尺寸
- Python字典，键值对中的“键”是索引，index从字典中进行选择操作
- ndarray，索引和数据都可以通过ndarray类型创建
- 其他函数，range()函数等

Series类型的操作类似ndarray类型：
- 索引方法相同，采用[]
- NumPy中运算和操作可用于Series类型
- 可以通过自定义索引的列表进行切片
- 可以通过自动索引进行切片，如果存在自定义索引，则一同被切片

Series类型的操作类似Python字典类型：
- 通过自定义索引访问
- 保留字in操作
- 使用.get()方法