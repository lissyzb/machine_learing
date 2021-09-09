## 机器学习代码及课件

### 1. 目录说明

- [code]目录为课程作业代码，详情可阅读code/代码链接.md
- [课件]()为上课PPT课件

### 2. 代码说明

- 环境建议：使用vscode、pychram等IDE，也可以使用jupyer notebook
- github：https://gitee.com/towerysable/machine_learning_code_stu
- colab：https://drive.google.com/drive/folders/1XKvrieFkK46CNqwTE78i4DzFLpM-1cjg?usp=sharing

### 3. 作业说明

- 第一章 绪论                      无代码

- 第二章 模型估计与选择    无代码

- **作业1 第三章 线性模型              房价预测（基于sklearn）**

  - 题目：使用sklearn机器学习库进行房价预测。
    - 从给定的房屋基本信息以及房屋销售信息等，建立一个回归模型预测房屋的销售价格；
    - 使用matplotlib展示最终的预测结果与实际结果的对比。

  > [可视化参考链接：房价预测](https://www.kaggle.com/marsggbo/kaggle)[kaggle](https://www.kaggle.com/marsggbo/kaggle)[入门项目](https://www.kaggle.com/marsggbo/kaggle)

- **作业2 第四章 决策树                  收入分类问题（基于sklearn）**

  - 题目：用决策树模型完成收入分类问题。
    - 对数据进行分类；
    - 使用pydotplus和IPython.display可视化这颗决策树，并分析决策树是什么进行决策的？
    - 如果调整收入这个参数，决策树会怎么变化，为什么？

- **作业3 第五章 神经网络              铁锈图像分类（CNN，基于keras和sklearn）**

  - 题目：用CNN模型在铁锈数据集完成图像分类。（比赛）
    - 已经提供Keras源码，尝试修改卷积层的参数，写一份不同参数的报告；
    - 已提供训练的代码，尝试书写预测的代码（预测的数据可以来自训练集）；
    - 已经提供Keras的模型参考代码，改写成Tensorflow代码（附加）。 

- **作业4 第六章 支持向量机          新闻分类（基于libsvm）**

  - 题目：用SVM模型完成新闻分类。
    - 已经提供libsvm的源码，尝试使用sklearn中的SVM实现新闻分类问题；
    
      > **数据集：** 链接: https://pan.baidu.com/s/1Xvq39rwi8qJfb-Wu1bE9iw    提取码: 35rp

- **作业5 第七章 贝叶斯网络          新闻分类（基于sklearn）**

  - 题目：用朴素贝叶斯模型完成新闻分类。
    - 使用sklearn.model_selection 中的train_test_split完成交叉验证；
    - 将文本特征向量化，并使用朴素贝叶斯进行训练； 
    - 使用sklearn.metrics分析得到的分类结果。

- **作业6 第八章 集成学习             鸢尾花分类（基于sklearn，LightGBM）  房价预测（基于sklearn，随机森林）**

  - 题目1：构造随机森林模型完成新闻分类。

    - 已提供基础构造随机森林的代码，尝试比较随机森林和决策树的不同。

  - 题目2：用LightGBM算法实现鸢尾花种类的分类任务。（选学）
  - 比较LightGBM和随机森林的异同。
  
- **作业7 第九章 聚类                    模拟正态分布（GMM与EM算法，）  K-Means聚类（基于sklearn）**

  - 题目1：使用K-Means完成文本聚类。

    - 了解自然语言处理中的TF-IDF算法的原理；
    - 比较选择不同的聚类中心对最终结果带来的影响；
    - 每个聚类选取N个词，带来的影响是什么？

  - 题目2：模拟两个正态分布的参数。（选学）
  - 根据代码熟悉EM算法与GMM模型
  
- **作业8 第十章 降维与度量学习  手写数字识别（KNN）**

  - 题目：基于KNN完成构造随机森林模型完成新闻分类。
    - 构造一个能识别数字 0 到 9 的基于 KNN 分类器的手写数字识别系统
    - 将模型开发流程进行熟悉
    - 尝试使用其他的模型完成手写数字识别（例如PCA、SVM）