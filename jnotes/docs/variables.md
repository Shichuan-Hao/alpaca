# 变量

大多数情况下，JavaScript 应用需要处理信息。

如果将变量想象成一个“数据”的盒子，盒子上有一个唯一的标注盒子名字的贴纸。
例如：变量 message 可以被想象成一个标有 “message” 的盒子，盒子里面的值为“Hello!”。

我们可以在盒子内放入任何值。并且，这个盒子的值，我们想改多少次，就可以改变多少次。
```JavaScript
let message;
message = 'Hello!';
message = 'World!'; // 值改变了
alert(message)
```
当值改变的时候，之前的数据就被从变量中删除了。
```JavaScript
let hello = 'Hello world';
let message;
// 将字符串 'Hello world' 从变量 hello 拷贝到 message
message = hello;

// 现在两个变量保存着相同的数据
alert(hello); // Hello world!
alert(message); // Hello world!
```

> 声明两次会触发 error \
> 一个变量应该只被声明一次。 \
> 对同一个变量进行重复声明会触发 error \
> ```JavaScript
> let message = "This"
> // 重复 'let' 会导致 error
> let message = "That";
> ```