# python-
要求解的优化问题：变量均为连续变量  object function：非线性函数（不是简单的二次项）  constraints：等式约束：非线性约束（二次项）+线性约束                        不等式约束：线性约束  之前查过cvxopt和apm两种求解器。  cvxopt要求等式约束均为线性，非线性约束只能是不等约束，所以cvxopt无法求解。  apm从网上下载的求解器，约束全部在.apm文件中编辑，不太会编辑，灵活度不高，感觉也不适用。  除此之外，还有其他合适的求解器吗？万分感谢！
