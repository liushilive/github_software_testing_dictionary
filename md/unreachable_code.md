# 无法访问的代码

无法访问的代码，源代码的一部分，由于不适当的退出点 / 控制流而永远不会被执行。另一种无法访问的代码称为死代码，尽管死代码可能会被执行但对系统的功能没有影响。

## 无法访问的代码副作用

* 不必要的内存开销。

* 不必要的缓存周期会导致性能瓶颈。

* 记录和维护管理费用。

## 无法访问的代码原因

* 在开发复杂条件分支时编程错误。

* 不完整的单元测试，因为未检测到无法访问的代码。

* 开发人员忘记删除的冗余代码

* 由于传递给函数的输入数据，可能在编程上正确但不会在任何时间执行的代码。
