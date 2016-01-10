---
title: '2016-1-6 投资日记'

layout: nil
---

### 本日收获

* 投资是理性的，不能主观想着会反弹，会借壳，会大涨；
* 现在还是原资金，如果没有回撤，将会有30%的收益，为什么三次回撤后还会犯错误呢？
* 在底部时老半仓，觉得还要跌；而在震荡横盘时慢慢加成满仓，觉得随时都可能上攻，三次都这样承担大风险，是不是脑子有病？
* 如果及时止损，绝不会回撤，收益率绝不会停滞不前，并且不套牢，有资金来抄底。收益50%很简单。
* 每个股票都要有个止损点，严格执行，最起码不会亏，最起码有现金再战其他好票。
* 为自己的整体仓位写一个策略，当到亏损到什么的时候，强行平仓，观察清楚后再继续。

When [retrieving stuff](#get-stuff) for example:

```Status: 200 OK```
```{
    {
        id: thing_1,
        name: 'My first thing'
    },
    {
        id: thing_2,
        name: 'My second thing'
    }
}```

### Error

Error responses are simply returning [standard HTTP error codes](http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html) along with some additional information:

* The error code is sent back as a status header,
* The body includes an object describing both the code and message (for debugging and/or display purposes),

For a call with an invalid authentication token for example:

```Status: 401 Access denied```
```{
    code: 401,
    message: 'Access denied: invalid authentication token.'
}```
