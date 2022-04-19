## 02 尽量以 const , enum, inline 替换 #define]
补充 [const 用法总结](https://github.com/yuedaokong/Effective-Cpp-Learing/blob/main/Accustoming%20Yourself%20to%20C%2B%2B/02/const%E7%94%A8%E6%B3%95%E6%80%BB%E7%BB%93.md) [enum 用法总结](https://github.com/yuedaokong/Effective-Cpp-Learing/blob/main/Accustoming%20Yourself%20to%20C%2B%2B/02/enum%E7%94%A8%E6%B3%95%E6%80%BB%E7%BB%93.md)

`#define ASPECT_RATIO 1.653` 
- 如果调用的库函数非你所写，则会不清楚 1.653 所指，追溯所指含义浪费时间
- 你所使用名称可能并未进入记号表

解决方法用常量替换 #define
