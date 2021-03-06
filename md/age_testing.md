# 年龄测试

它是一种测试技术，用于评估系统未来的执行能力，通常由测试团队执行。随着系统变老，性能可能下降的程度是在 Age Testing 中测量的。

让我们也理解缺陷年龄的概念。它是根据两个参数来衡量的：

1. Phases
1. Time

## 缺陷年龄 - Phases

阶段缺陷年龄定义为缺陷注入阶段和缺陷检测阶段之间的差异。

### 参数

1.“缺陷注入阶段”是引入缺陷时软件开发生命周期的阶段。
1.“缺陷检测阶段”是指定缺陷时软件开发生命周期的阶段。

### 计算公式

阶段的缺陷年龄 = 缺陷检测阶段 - 缺陷注入阶段

### 例

思考一下，我们采用的 SDLC 方法有以下几个阶段：

1. 需求开发
1. 设计
1. 编码
1. 单元测试
1. 集成测试
1. 系统测试
1. 验收测试

如果在单元测试（4）中发现缺陷并且缺陷在开发的设计阶段（2）中引入，则缺陷年龄为（4） - （2）= 2。

## 缺陷年龄 - Time

缺陷年龄定义为缺陷检测日期与当前日期之间的时间差，前提是缺陷仍被认为是开放的。

### 参数

1. 缺陷处于“打开”和“已分配”状态，而不仅仅处于“新”状态。
1. 不考虑因“不可复制”或“重复”而处于“封闭”状态的缺陷。
1. 从缺陷开放日期和当前日期计算天数或小时数的差异。

### 计算公式

缺陷年龄 = 缺陷修复日期（OR）当前日期 - 缺陷检测日期

### 例

如果在 05/05/2013 11:30:00 AM 检测到缺陷并在 2013 年 5 月 23 日下午 12:00:00 关闭，则缺陷年龄将按如下方式计算。

缺陷年龄（天） = 05/05/2013 11:30:00 AM - 23/05/2013 12:00:00 PM

缺陷年龄（天） = 19 days

## 结果

为了评估每个阶段和任何审查 / 测试活动的有效性，缺陷年龄越小，效果越好。
