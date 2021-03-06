# 突变测试

突变测试是一种结构测试技术，它使用代码结构来指导测试过程。在很高的层次上，它是以小的方式重写源代码以删除源代码中的冗余的过程

如果不修复，这些模糊可能会导致软件出现故障，并且很容易通过未检测到的测试阶段。

## 突变测试的好处

如果采用突变测试，则会有以下好处：

* 它给开发人员的注意带来了一种全新的错误。

* 它是检测隐藏缺陷的最有效方法，使用传统测试技术可能无法识别隐藏缺陷。

* Insure ++ 等工具帮助我们使用最先进的技术在代码中找到缺陷。

* 提高客户满意度指数，因为产品将减少错误。

* 调试和维护产品将比以往更容易。

## 突变测试类型

* 值突变：

  尝试更改值以检测程序中的错误。我们通常将一个值更改为更大的值，或将一个值更改为更小的值。最常见的策略是更改常量。

* 决策突变：

  更改决策 / 条件以检查设计错误。通常，一个人改变算术运算符来定位缺陷，我们也可以考虑改变所有关系运算符和逻辑运算符（AND，OR，NOT）

* 语句突变：

  通过删除或复制开发人员从其他位置复制粘贴代码时可能出现的行来对语句所做的更改。
