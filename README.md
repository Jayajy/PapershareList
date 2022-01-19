# PapershareList

## 相关论文查找网站（持续更新）
https://ieeexplore.ieee.org/xpl/conhome/1000002/all-proceedings <br>
https://ismir.net/ <br>

## Music Information Retrieval
- [IJCNN(International Joint Conference on Neural Networks) 2021]Large-scale singer recognition using deep metric learning: an experimental study <br>
  动机：歌手识别任务由于音乐伴奏对于人声造成的低信噪比，导致其任务较为困难。并且目前针对这一任务的数据集较少，并且数据集内歌手数量也很有限，则限制了识别的泛化性。本文构建了一个由5057个歌手构成的大规模数据集，使用这一数据集进行了一系列的研究。 <br>
  方法：1、网络模型使用类似于Thin ResNet-34的架构。 <br>
        2、引入了三种计算Loss的方法来对两种任务——识别和验证进行评估。三种Loss分别为： Triplet Loss(TPL)， Prototypical Network Loss(PNL)，Generalized End-to-End Loss(GE2E)。 <br>
        3、引入声源分离技术分别评估了带有音乐伴奏的歌声和没有音乐伴奏的歌声。 <br>
        4、尝试了多片段输入对系统性能的改变，事实证明有较大提升。 <br>
  未来工作：考虑到歌声的高度可变性，一个单一的或一个质心的embedding可能不足以代表一个歌手。这将作为本研究的未来工作进行讨论。 <br>
  https://github.com/Jayajy/PapershareList/Paper/Largescale_singer_recognition_using_deep_metric_learning_an_experimental_study.pdf <br>
- 
