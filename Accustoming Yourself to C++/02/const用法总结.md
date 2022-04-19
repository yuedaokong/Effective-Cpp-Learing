
# const 用法总结
const 是一个变量，其值不能改变，换言之，将变量限定为一个常量。
const 对象一旦创建就不能改变，所以必须进行初始化

`const int i = 42;//编译时初始化`

`const int j = get.size();//运行时初始化`

```cpp
int i = 42;
const int ci = i;//拷贝初始化
```
