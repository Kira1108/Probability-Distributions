# Probability-Distributions
Using probability distributions in various packages


你知道PYMC为什么没有工业使用么。
你知道贝叶斯为什么工业使用不如ML么。
因为门槛高啊。
因为不能`fit_predict`啊


所以你需要看各种Distribution.
Distribution就是一个函数，跟初三高一数学的函数一样。
你就一直搞这些狗屁函数，不同的库定义的方法也不一样。
可参考的材料也比较少。


所以就开这个库，记录一下mc天坑。

用任意的一个过程，这个过程是很多函数，分布的组合，来描述一组数据。
当这个过程能够描述你的数据的时候，你假设的模型就成立了。

但是这个过程有时候太复杂了，和理论的分布有很大的差距，中间需要好多的奇淫技巧。
用tensor和pm的组合、构造新的分布，选取合适的参数，都能帮你弄的更好。


