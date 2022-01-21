# PapershareList

## 相关论文查找网站（持续更新）
https://ieeexplore.ieee.org/xpl/conhome/1000002/all-proceedings <br>
https://ismir.net/ <br>

## Music Information Retrieval
- [arXiv 1 Dec 2021]TOWARDS LEARNING UNIVERSAL AUDIO REPRESENTATIONS <br>
  动机：评估和检测以往的通用音频表示模型和学习框架，特别是关注监督分类和自我监督对比学习两种主要范式，并在一组大的模型架构中对它们进行比较。本文还提出了一种新的通用模型——Slowfast NFNet-F0，可以提高系统的性能。 <br>
  方法：1、引入了HARES，包含跨越了语言，音乐，和环境声三个领域的12个任务。![image](https://user-images.githubusercontent.com/41570758/150502134-a9de06dd-e203-4886-b2c8-07f94b84a66e.png) <br>


- [IJCNN(International Joint Conference on Neural Networks) 2021]Large-scale singer recognition using deep metric learning: an experimental study <br>
  动机：歌手识别任务由于音乐伴奏对于人声造成的低信噪比，导致其任务较为困难。并且目前针对这一任务的数据集较少，并且数据集内歌手数量也很有限，则限制了识别的泛化性。本文构建了一个由5057个歌手构成的大规模数据集，使用这一数据集进行了一系列的研究。 <br>
  方法：1、网络模型使用类似于Thin ResNet-34的架构。 <br>
        2、引入了三种计算Loss的方法来对两种任务——识别和验证进行评估。三种Loss分别为： Triplet Loss(TPL)， Prototypical Network Loss(PNL)，Generalized End-to-End Loss(GE2E)。 <br>
        3、引入声源分离技术分别评估了带有音乐伴奏的歌声和没有音乐伴奏的歌声。 <br>
        4、尝试了多片段输入对系统性能的改变，事实证明有较大提升。 <br>
  未来工作：考虑到歌声的高度可变性，一个单一的或一个质心的embedding可能不足以代表一个歌手。这将作为本研究的未来工作进行讨论。 <br>
  https://github.com/Jayajy/PapershareList/blob/main/Paper/Large-scale_singer_recognition_using_deep_metric_learning_an_experimental_study.pdf <br>
  
  
- [ICASSP 2021]MULTI-TASK SELF-SUPERVISED PRE-TRAINING FOR MUSIC CLASSIFICATION <br>
  动机：
  方法：
  
