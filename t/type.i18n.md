## CN

获取 JavaScript 对象的内部类型。

|参数名|类型|说明|
|-----|----|---|
|val|*|目标对象|
|返回值|string|对象类型，小写|

```javascript
type(5); // -> 'number'
type({}); // -> 'object'
type(function () {}); // -> 'function'
type([]); // -> 'array'
```