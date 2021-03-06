### 毕业论文答辩Draft
Author : 单铭铭  
Date : 2017-06-01

#### 开场白
大家好, 我是来自13级数学系统计专业的单铭铭, 负责指导我的是师维学老师.
也先感谢一下师老师花的宝贵时间来读我的论文. 接下来的几分钟我来介绍一下
我写的毕业论文的主要内容, 因为是学习总结, 所以也可以同时锻炼一下各位的
耐心. 

#### 介绍仿紧性
这篇小论文是对拓扑空间的仿紧性质做的一个入门介绍, 虽然各位可能早就对仿紧
长什么样一清二楚, 但还是容许我再一次掀开它的神秘面纱.

一个拓扑空间是仿紧的, 如果它的任意开覆盖都有局部有限开加细.
这个定义和紧空间的定义由相似之处, 都是任意开覆盖具有某种性质.
这不是巧合, 因为仿紧就是紧致稍微放松一下条件. 并且这个定义也
可以说明紧空间都是仿紧的. 既然紧空间的任意开覆盖都有有限子覆盖,
当然也是局部有限的.

既然紧性与仿紧性由如此紧密的关系, 那么仿紧空间的性质, 也在一定程度上和
紧空间的性质有个对应关系. 比如, 紧空间的闭子空间是紧的, 对比这个, 我们
还有, 仿紧空间的闭子空间是仿紧的. 同样的, 紧致Hausdorff空间是T3, T4,
仿紧Hausdorff空间也是T3, T4的. 这么看, 它们相似的地方确实多.
当然它们也有不同的地方, 后面我们会举例子.

#### 核心定理
下面我来介绍一下仿紧空间的刻画, 因为我从定义也看不出太多的东西了.
定理3.0.1, 是Michael在1953年得到的结论. 它主要说明的是, 对于满足
T_3公理的拓扑空间, 仿紧的定义可以更宽松一下, (只要任意开覆盖有
sigma局部有限开加细就行了, 和定义相比, )不再要求局部有限, 而是
可数个局部有限集族的并是开加细就行了. 这样的话, 判断一个空间是不是
仿紧的, 严格地判断存在局部有限开加细, 可能比判断存在sigma局部有限
开加细要困难得多, 但它们在T3下是等价的, 所以一般情况下, 这个定理把
判断仿紧性的难度调低了. 这个定理的直接应用就是定理4.0.1, ...

接下来, 还是Michael在1956年得到的定理, 是对仿紧性质的进一步刻画.
这次, 是用闭包保持的性质来的. 定理3.0.2, 说在T3公理下, 仿紧与
任意开覆盖有闭包保持开加细等价. 原定义局部有限, 需要考虑局部,
而这里, 变成了只要考虑开加细是不是闭包保持的就行了. 形式上,
将验证局部性质改为验证是否闭包保持了. 我感觉, 应该是让判断是否是
仿紧空间更加容易了. 这个定理的证明, 也用了上个定理, 这也反映了
上一个定理很有用.

紧性与仿紧性不同的地方, 我们来看一看. 
对于紧空间, 它的F-sigma子空间不一定是紧的. 但对于仿紧空间,
我们有它的F-sigma子空间是仿紧的. 这个是紧空间不具有的性质,
但是仿紧具有. 也有仿紧具有, 但是紧空间不具有的性质.
比如, 两个紧空间的乘积空间也是紧的, 但是, 两个仿紧空间的
乘积空间却不一定是仿紧的. 反例是这样的, 记S为Sorgenfrey line,
S是仿紧的, 但是S x S(Sorgenfrey plane)就不是仿紧的.
虽然仿紧空间的乘积空间不一定是仿紧的, 但是我们也有一个对应的
结论, 就是命题4.0.6. 紧空间与仿紧空间的乘积空间, 是仿紧的.

#### Ending
以上就是我所总结的主要定理及命题. 谢谢大家的收听.
