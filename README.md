# checklists

一些工具、库使用时的注意事项

## gob

- 对于接口类型的变量，每个实现该接口的类型需要一次性的调用 gob.Register() 进行注册，否则 encode 时会出错

## upper.io/db.v3

- NULL 值的处理。struct 中的 field 需要声明为指针类型，如果是值类型，读取数据填充数据结构时，会报错

## sorted balanced binary tree
[google/btee](https://github.com/google/btree)

> Unlike gollrb, though, we currently don't support storing multiple equivalent values.

[petar/GoLLRB](https://github.com/petar/gollrb)
