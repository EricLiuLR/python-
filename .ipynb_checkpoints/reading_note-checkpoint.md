# Python 数据分析与挖掘实战

## 第一章：数据挖掘基础

数据挖掘：从大量数据中挖掘出隐含的、未知的、对决策有潜在价值的关系、模式和趋势，并利用这些知识和规则建立用于决策支持的模型，利用预测性决策支持的方法、工具和过程，就是数据挖掘。

数据挖掘的基本任务：提取数据中蕴含的商业价值，提高企业的竞争力。

### 数据挖掘建模过程：
- 定义挖掘目标
    - 分析应用领域，了解情况
    - 理解任务，确定目标
- 数据抽样
    - 定义了数据挖掘目标之后，从业务系统中抽取一个与挖掘目标相关的数据样本子集
    - 抽取数据的标准：相关性、可靠性、有效性
    - 抽样的方式：随机抽样、等距抽样、分层抽样、从起始顺序抽样、分类抽样
- 数据探索
    - 对抽取的样本数据进行探索、审核和必要的加工处理
    - 数据挖掘的质量不会超过抽取样本的质量，数据探索和预处理的目的就是保证样本数据的质量
    - 主要包括：异常值分析、缺失值分析、相关分析和周期性分析等
- 数据预处理
    - 目的：改善数据质量、完善数据挖掘的结果
    - 方式包括：数据筛选、数据变量转换、缺失值处理、坏数据处理、数据标准化、主成分分析、属性选择、数据规约等
- 挖掘建模
    - 本次建模属于数据挖掘中的哪类问题？
    - 分类、聚类、关联规则、时序模式、智能推荐？
    - 选用哪种算法进行模型构建？
- 模型评价