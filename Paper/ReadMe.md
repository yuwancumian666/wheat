## 写作过程中需要注意的问题

### 1. 卷积层和池化层的层数及结构

   卷积神经网络的设计中，为什么采用3+3的卷积层和池化层，而不进一步采用更深层的网络结构用于病害识别？

### 2. 数据集的分配及预留样本测试

实验过程中，第一种实验方案设计采用三分之一数据集用于训练，三分之二用于测试。在该种实验设计方案中没有设定验证集，**直接采用预留样本作为测试集**有混淆概念嫌疑。另外**训练集和测试集划分比例**也存在一定问题，该种比例划分下如何降低分类器的泛化误差需要进一步说明。

### 3. 细化实验设计参数

实验过程中实验次数，交叉实验折数，已经实验过程中的分类器性能评价指标都过于单一，需要进一步细化实验设计参数，并增加分类器性能评价指标。
   *对不同实验次数作记录，寻找能够使正确率达到最高值且逐渐平稳的训练次数。*
4. 针对小麦不同类型病害的特征与卷积模型之间缺乏必要的关联分析。
5. 在数据训练上对1000次和5000次的训练次数未给出定量依据，还有待进一步研究。
6. **深度置信网络**
