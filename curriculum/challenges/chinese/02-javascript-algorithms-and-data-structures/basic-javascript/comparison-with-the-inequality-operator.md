---
id: 56533eb9ac21ba0edf2244d2
title: 不等运算符
challengeType: 1
videoUrl: 'https://scrimba.com/c/cdBm9Sr'
forumTopicId: 16787
---

# --description--

不相等运算符（`!=`）与相等运算符是相反的。这意味着不相等运算符中，如果“不为真”并且返回`false`的地方，在相等运算符中会返回`true`，*反之亦然*。与相等运算符类似，不相等运算符在比较的时候也会转换值的数据类型。

**例如**

```js
1 !=  2     // true
1 != "1"    // false
1 != '1'    // false
1 != true   // false
0 != false  // false
```

# --instructions--

在`if`语句中，添加不相等运算符`!=`，这样函数在当`val`不等于 `99`的时候，会返回 "Not Equal"。

# --hints--

`testNotEqual(99)`应该返回 "Equal"。

```js
assert(testNotEqual(99) === 'Equal');
```

`testNotEqual("99")`应该返回 "Equal"。

```js
assert(testNotEqual('99') === 'Equal');
```

`testNotEqual(12)`应该返回 "Not Equal"。

```js
assert(testNotEqual(12) === 'Not Equal');
```

`testNotEqual("12")`应该返回 "Not Equal"。

```js
assert(testNotEqual('12') === 'Not Equal');
```

`testNotEqual("bob")`应该返回 "Not Equal"。

```js
assert(testNotEqual('bob') === 'Not Equal');
```

你应该使用`!=`运算符。

```js
assert(code.match(/(?!!==)!=/));
```

# --solutions--

