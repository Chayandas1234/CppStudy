练习16.43：使用上一题定义的函数，如果我们调用g(i == ci)，g的模板参数将是什么？

---

i = ci返回的是一个int&，它是一个左值，模板参数将推断为引用类型，即int& 。