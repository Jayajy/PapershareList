# PapershareList

## 相关论文查找网站（持续更新）
https://ieeexplore.ieee.org/xpl/conhome/1000002/all-proceedings <br>
https://ismir.net/ <br>
https://web.cse.ohio-state.edu/~wang.77/pnl/ <br>

## Speech
- [arXiv 1 Dec 2021]TOWARDS LEARNING UNIVERSAL AUDIO REPRESENTATIONS <br>
  动机：评估和检测以往的通用音频表示模型和学习框架，特别是关注监督分类和自我监督对比学习两种主要范式，并在一组大的模型架构中对它们进行比较。本文还提出了一种新的通用模型——Slowfast NFNet-F0，可以提高系统的性能。 <br>
  方法：1、引入了HARES，包含跨越了语言，音乐，和环境声三个领域的12个任务。![image](https://user-images.githubusercontent.com/41570758/150502134-a9de06dd-e203-4886-b2c8-07f94b84a66e.png) <br>
        2、评测了多种预训练模型框架，比较了两个训练目标——有监督分类任务和自监督对比学习任务。![image](https://user-images.githubusercontent.com/41570758/150502473-8faa4b5f-4f95-40a2-83a2-53450fa29f8c.png) <br>
        3、本文提出的Slowfast NFNets。![image](https://user-images.githubusercontent.com/41570758/150502934-eec9d6f7-8ecd-4c5b-9429-109c5fb3997c.png) <br>
        Slowfast网络最先提出于视频分类，低帧率捕获空间语义信息，高帧率捕获动作信息。结合这两种信息可以更全面的表达视频的特征。![image](https://user-images.githubusercontent.com/41570758/150503071-d3b6aebf-848c-4449-9a7d-266cf18e6811.png) <br>
        4、研究了正则化对SlowFast网络的影响以及做了与其他先进模型的比较。![image](https://user-images.githubusercontent.com/41570758/150503286-0516403d-68e7-45e0-9494-2269bb1f4de6.png)
        ![image](https://user-images.githubusercontent.com/41570758/150503310-96cbce6d-9f83-47f1-9bf6-d1f552aaeb14.png) <br>
  https://github.com/Jayajy/PapershareList/blob/main/Paper/TOWARDS_LEARNING_UNIVERSAL_AUDIO_REPRESENTATIONS.pdf <br>
 - [IEEE/ACM TASLP 2020]Learning Complex Spectral Mapping With Gated Convolutional Recurrent Networks for Monaural Speech Enhancemental <br>
   动机：相位信息对语音质量的影响很大。本文使用复谱映射提取出纯净语音的实部谱和虚部谱，来增强语音的幅度谱和相位谱的准确性。根据前人的工作，本文提出一种新型CRN，提出了一种用于复数谱映射的门控卷积循环网络(GCRN)。 <br>
   方法：每个卷积层或解卷积层被相应的门控线性单元（GLU）块所取代；LSTM采用了分组策略；在最后一个去卷积层的基础上增加了一个线性层来预测实谱和虚谱。<br>
## Music Information RetrievLearning 
- [IJCNN(International Joint Conference on Neural Networks) 2021]Large-scale singer recognition using deep metric learning: an experimental study <br>
  动机：歌手识别任务由于音乐伴奏对于人声造成的低信噪比，导致其任务较为困难。并且目前针对这一任务的数据集较少，并且数据集内歌手数量也很有限，则限制了识别的泛化性。本文构建了一个由5057个歌手构成的大规模数据集，使用这一数据集进行了一系列的研究。 <br>
  方法：1、网络模型使用类似于Thin ResNet-34的架构。 <br>
        2、引入了三种计算Loss的方法来对两种任务——识别和验证进行评估。三种Loss分别为： Triplet Loss(TPL)， Prototypical Network Loss(PNL)，Generalized End-to-End Loss(GE2E)。 <br>
        3、引入声源分离技术分别评估了带有音乐伴奏的歌声和没有音乐伴奏的歌声。 <br>
        4、尝试了多片段输入对系统性能的改变，事实证明有较大提升。 <br>
  未来工作：考虑到歌声的高度可变性，一个单一的或一个质心的embedding可能不足以代表一个歌手。这将作为本研究的未来工作进行讨论。 <br>
  https://github.com/Jayajy/PapershareList/blob/main/Paper/Large-scale_singer_recognition_using_deep_metric_learning_an_experimental_study.pdf <br>
- [ICASSP 2021]COMPLEX RATIO MASKING FOR SINGING VOICE SEPARATION <br>
   动机方法概述：https://github.com/Jayajy/PapershareList/blob/main/Paper/%E6%8A%A5%E5%91%8ACOMPLEX%20RATIO%20MASKING%20FOR%20SINGING%20VOICE%20SEPARATION.docx<br>
   mir_eval:https://github.com/craffel/mir_eval <br>
   https://github.com/Jayajy/PapershareList/blob/main/Paper/COMPLEX%20RATIO%20MASKING%20FOR%20SINGING%20VOICE%20SEPARATION.pdf<br>
- [arXiv 2020]VOICE AND ACCOMPANIMENT SEPARATION IN MUSIC USING SELF-ATTENTION CONVOLUTIONAL NEURAL NETWORKS <br>   
  动机：音乐源分离一直是信号处理中的一个流行话题，不仅因为它在技术上的困难，而且还因为它在许多商业应用中的重要性。本文受到UNet-CNN的启发，推出一种新的自我注意网络来分离音乐中的声音和伴奏。<br>
  方法：网络结构与上一篇相似，输入和输出是时域上的短时傅里叶变换的频谱图。<br>
  ![image](https://user-images.githubusercontent.com/41570758/151650078-c5d6a63e-cb42-4419-8afe-bed1319aedb5.png)
- [INTERSPEECH 2019]On the Importance of Audio-source Separation for Singer Identification in Polyphonic Music <br>
  动机：虽然识别歌手与说话人识别相似，但由于背景伴奏对歌手特定信息的干扰，这是具有挑战性的。将背景伴奏与歌唱声乐分离将有助于我们克服干扰。<br>
  方法：1、使用基于Wave-U-Net的音频源分离方法从多调歌曲中提取歌声。提取的歌声用于基于i向量的歌手识别系统。<br>
        2、探索了不同的最先进的音频源分离方法，以建立所考虑的方法在歌手识别中的作用。<br>
        3、所提出的歌手识别框架比基线的绝对精度提高了5.66%。<br>
        ![image](https://user-images.githubusercontent.com/41570758/151651077-8f557a65-bb3c-415a-a42c-261b813df374.png)

  
  

  
