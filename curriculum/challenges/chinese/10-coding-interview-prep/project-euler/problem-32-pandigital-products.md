---
id: 5900f38c1000cf542c50fe9f
title: 问题32：Pandigital产品
challengeType: 5
videoUrl: ''
---

# --description--

我们可以说，如果n位数字恰好一次使用了1到n的所有数字，那么它就是pandigital。 例如，5位数字15234是1到5泛数字。

乘积7254是不寻常的，因为其标识为39×186 = 7254，包含被乘数，乘数，乘积是1到9泛数。

找出所有被乘数/乘数/产品标识可以写成1到9泛数字的所有产品的总和。

提示：某些产品可以通过多种方式获得，因此请确保只在其总和中包括一次。

# --hints--

`pandigitalProducts()`是一个函数。

```js
assert(typeof pandigitalProducts === 'function');
```

`pandigitalProducts()`应该返回45228。

```js
assert.strictEqual(pandigitalProducts(), 45228);
```

# --solutions--

