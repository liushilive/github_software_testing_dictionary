# 条件覆盖测试

条件覆盖率也称为谓词覆盖率，其中每个布尔表达式都已被评估为 TRUE 和 FALSE。

## 例

```c
if ((A || B) && C)
{
  << Few Statements >>
}
else
{
   << Few Statements >>
}
```

## 结果

为了确保上述示例的完整条件覆盖标准，A，B 和 C 应至少对“真”和“假”评估一次。

因此，在我们的示例中，以下 3 个测试足以进行 100%条件覆盖测试。

* `A = true  | B = not eval | C = false`

* `A = false | B = true     | C = true`

* `A = false | B = false    | C = not eval`
