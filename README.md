[![PythonVersion](https://img.shields.io/badge/python-3.8-blue)](https://img.shields.io/badge/python-3.8-blue)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

🔈 尝试复现一个机器学习算法时，自己的算例结果有时与使用开源库（如[`scikit-learn`](https://github.com/scikit-learn/scikit-learn)）的结果不一致？

🔈 想学习算法原理，完成由公式推导到代码实现？了解开源库的实现细节有哪些不同？

👇 如果你有类似问题或者需要，欢迎了解本项目。目前已实现部分机器学习算法，对每个算法都给出了原理解释、

必要的公式推导及一些自己的思考，同时配有案例，与使用开源库的结果进行对比并给出相关说明。

算法目录
-------
- [线性回归](https://github.com/viga111/machine-learning/blob/master/algorithms/LinearRegression.ipynb)
- [逻辑回归](https://github.com/viga111/machine-learning/blob/master/algorithms/LogisticRegression.ipynbb)
- [K近邻](https://github.com/viga111/machine-learning/blob/master/algorithms/KNearestNeighbor.ipynb)
- [朴素贝叶斯](https://github.com/viga111/machine-learning/blob/master/algorithms/NaiveBayes.ipynb)
- [决策树](https://github.com/viga111/machine-learning/blob/master/algorithms/DecisionTree.ipynb)
- [提升算法](https://github.com/viga111/machine-learning/blob/master/algorithms/AdaBoost.ipynb)
- [梯度提升树](https://github.com/viga111/machine-learning/blob/master/algorithms/GradientBoost.ipynb)

持续更新中...

使用说明
-------
本项目`.ipynb`文件中的图片地址为相对路径，例如`DecisionTree.ipynb`文件中

    <img src="..src\DecisionTree.png">

❗ 为避免图片显示出错，请注意文件的路径问题。如下为一种正确的路径示例

    E:\machine-learning\algorithms\DecisionTree.ipynb
    E:\machine-learning\src\DecisionTree.png

⭐推荐使用[`jupyterthemes`](https://github.com/dunovank/jupyter-themes)设置自己的`jupyter notebook`风格，以获得更好的阅读体验。

环境需求
-------
本项目代码在以下配置下全部测试通过
- Python (=3.8.4)
- jupyter (=1.0.0)
- scikit-learn (=0.24.2)
- numpy (=1.19.0)
- matplotlib (=3.4.1)
- graphviz (=0.17)

正常情况下，只需要已安装必要的库即可运行项目代码，并非强制需求上述配置。

待办
----
- [ ] 监督学习算法部分的补充完善
- [ ] 无监督学习算法

参考
----
- 李航. 统计学习方法
- [scikit-learn文档](https://scikit-learn.org/stable/)
- [scikit-learn源码](https://github.com/scikit-learn/scikit-learn)

联系
----
欢迎大家提`issue`，一起学习交流！
