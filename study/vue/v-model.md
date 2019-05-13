#### v-model :

修饰符：

` .lazy `

```javascript

<!-- 在 "change" 而不是在 "input" 事件中更新 -->
<input v-model.lazy="msg" >
    
```



`.number `

```javascript
//因为input标签中， 即使 type="number" 时，HTML中输入的值也总是返回 字符串类型

//因此可以给v-model添加修饰符 .number来处理：

<input v-model.number="age" type="number">
```



` trim `

```javascript
//自动过滤用户输入的收尾空格：	
<input v-model.trim="msg" >
```

