emoji|含义
-----|--
:clap:|我在实际项目中使用过
:computer:|支持的编程语言
:memo:|我的备注
:bug:|使用中踩过的坑
:x:|过渡性或过时的技术，不推荐掌握

_注：你可以通过复制此 emoji 到页面内搜索窗口，以实现快速定位到指定 emoji_

# Datasets

* [Google Dataset Search](https://toolbox.google.com/datasetsearch)
* [candlewill/Dialog_Corpus](https://github.com/candlewill/Dialog_Corpus)  
用于训练中英文对话系统的语料库 Datasets for Training Chatbot System
* [awesomedata/awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets)  
* [Common Voice By mozilla](https://voice.mozilla.org/zh-CN/datasets)  
Common Voice 数据集里面有什么？  
数据集中的每一条都包含了一组独立 MP3 录音及相应的文字文件。数据集所记录的 1,368 小时的录音中，有许多条数据同时包含了年龄、性别、口音等人口统计元数据，能够训练语音识别引擎提升其准确性。  
  
该数据集当前有 1,087 小时，18 种语言的语音数据，但我们在持续添加更多的语音数据和更多的语言。前往我们的语言页请求加入更多的语言或开始做出贡献。
* [AISHELL-2](http://www.aishelltech.com/aishell_2)  
希尔贝壳中文普通话语音数据库AISHELL-2的语音时长为1000小时，其中718小时来自AISHELL-ASR0009-[ZH-CN]，282小时来自AISHELL-ASR0010-[ZH-CN]。录音文本涉及唤醒词、语音控制词、智能家居、无人驾驶、工业生产等12个领域。录制过程在安静室内环境中， 同时使用3种不同设备： 高保真麦克风（44.1kHz，16bit）；Android系统手机（16kHz，16bit）；iOS系统手机（16kHz，16bit）。AISHELL-2采用iOS系统手机录制的语音数据。1991名来自中国不同口音区域的发言人参与录制。经过专业语音校对人员转写标注，并通过严格质量检验，此数据库文本正确率在96%以上。（支持学术研究，未经允许禁止商用。）
* [OpenSLR](http://www.openslr.org/index.html)  
OpenSLR is a site devoted to hosting speech and language resources, such as training corpora for speech recognition, and software related to speech recognition. We intend to be a convenient place for anyone to put resources that they have created, so that they can be downloaded publicly.
* [brightmart/nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus)  
大规模中文自然语言处理语料 Large Scale Chinese Corpus for NLP
* [doc-analysis/TableBank](https://github.com/doc-analysis/TableBank)  
TableBank is a new image-based table detection and recognition dataset built with novel weak supervision from Word and Latex documents on the internet, contains 417K high-quality labeled tables.

# 数据处理

* [pandas-dev/pandas](https://github.com/pandas-dev/pandas)  
Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.frame objects, statistical functions, and much more https://pandas.pydata.org
* [tensorflow/tensor2tensor](https://github.com/tensorflow/tensor2tensor)  
Library of deep learning models and datasets designed to make deep learning more accessible and accelerate ML research.  
:memo:生产力工具
* [iterative/dvc](https://github.com/iterative/dvc)  
Data & models versioning for ML projects, make them shareable and reproducible https://dvc.org
:memo:生产力工具，git for data and model
* [ricklamers/gridstudio](https://github.com/ricklamers/gridstudio)  
Grid studio is a web-based spreadsheet application with full integration of the Python programming language.

It intends to provide an integrated workflow for loading, cleaning, manipulating, and visualizing data. This is achieved through a spreadsheet backend written in Go with integration of the Python runtime to manipulate its contents.

## 标注工具

* [INK-USC/AlpacaTag](https://github.com/INK-USC/AlpacaTag)  
AlpacaTag: An Active Learning-based Crowd Annotation Framework for Sequence Tagging http://inklab.usc.edu/AlpacaTag/
* [heartexlabs/label-studio](https://github.com/heartexlabs/label-studio)  
Label Studio is a multi-type data labeling and annotation tool with standardized output format https://labelstud.io/


## nlp

* [BYVoid/OpenCC](https://github.com/BYVoid/OpenCC)  
A project for conversion between Traditional and Simplified Chinese http://opencc.byvoid.com/

## 数据可视化

* [plotly/dash](https://github.com/plotly/dash)  
Dash is a Python framework for building analytical web applications. No JavaScript required.
* [cytoscape/cytoscape.js](https://github.com/cytoscape/cytoscape.js)  
:computer:Javascript  
Graph theory (network) library for visualisation and analysis http://js.cytoscape.org  

# 训练模型

## 算法模型

* [StateOfTheArt.ai ](https://www.stateoftheart.ai/)  
:memo:网站以应用为导向，收集了当前在各种机器学习任务、各种数据集下表现最好的算法和模型
* [PapersWithCode](https://paperswithcode.com/sota)  
:memo:类似 StateOfTheArt.ai，以应用/任务为导向，信息更加丰富，论文、数据集，以及该任务当前及其历史的机器所能达到的水平
* [The Neural Network Zoo](http://www.asimovinstitute.org/neural-network-zoo/)  
:memo:收集了各种 NN Architecture
* :x:[cjlin1/libsvm](https://github.com/cjlin1/libsvm)  
libsvm 既是一个 svm 模型的实现，又是一种机器学习样本数据格式，非常适合描述高维稀疏样本
* :x:[quora/qmf](https://github.com/quora/qmf)  
A fast and scalable C++ library for implicit-feedback matrix factorization models
* [facebookresearch/Detectron](https://github.com/facebookresearch/Detectron)  
FAIR's research platform for object detection research, implementing popular algorithms like Mask R-CNN and RetinaNet.
* [emilwallner/Screenshot-to-code](https://github.com/emilwallner/Screenshot-to-code)  
A neural network that transforms a design mock-up into a static website
* [dmlc/xgboost](https://github.com/dmlc/xgboost)
* [Microsoft/LightGBM](https://github.com/Microsoft/LightGBM)  
:memo:[**GBDT**](http://mlexplained.com/2018/01/05/lightgbm-and-xgboost-explained/) 是在 Kaggle 竞赛中表现最好的模型，2015 年 Kaggle 比赛公开的 29 个获奖解法中，有 17 个使用了 [dmlc/xgboost](https://github.com/dmlc/xgboost)，[Microsoft/LightGBM](https://github.com/Microsoft/LightGBM) 是微软开源的 xgboost 挑战者。
* [aksnzhy/xlearn](https://github.com/aksnzhy/xlearn)  
High performance, easy-to-use, and scalable machine learning (ML) package, including linear model (LR), factorization machines (FM), and field-aware factorization machines (FFM) for Python and CLI interface. https://xlearn-doc.readthedocs.io/en/…


### nlp

* [google-research/bert](https://github.com/google-research/bert)  
BERT, or Bidirectional Encoder Representations from Transformers, is a new method of pre-training language representations which obtains state-of-the-art results on a wide array of Natural Language Processing (NLP) tasks.
* [hanxiao/bert-as-service](https://github.com/hanxiao/bert-as-service)  
Mapping a variable-length sentence to a fixed-length vector using BERT model
* [PrincetonML/SIF](https://github.com/PrincetonML/SIF)  
sentence embedding by Smooth Inverse Frequency weighting scheme  
:memo:[sentence embedding 方法综述](http://mlexplained.com/2017/12/28/an-overview-of-sentence-embedding-methods/)
* [facebookresearch/fastText](https://github.com/facebookresearch/fastText)  
Library for fast text representation and classification.  
:memo:用途：计算 word embedding、文本分类  
:bug:解决 fastText 官方 python-binding 在 macOS 上安装不成功的问题 [Issue#669](https://github.com/facebookresearch/fastText/issues/669)
* [lancopku/pkuseg-python](https://github.com/lancopku/pkuseg-python)  
声称是目前最好的中文分词工具
* [Embedding/Chinese-Word-Vectors](https://github.com/Embedding/Chinese-Word-Vectors)  
100+ Chinese Word Vectors 上百种预训练中文词向量
* [facebookresearch/LASER](https://github.com/facebookresearch/LASER)  
Language-Agnostic SEntence Representations
* [huggingface/transformers](https://github.com/huggingface/transformers)  
Transformers (formerly known as pytorch-transformers and pytorch-pretrained-bert) provides state-of-the-art general-purpose architectures (BERT, GPT-2, RoBERTa, XLM, DistilBert, XLNet, CTRL...) for Natural Language Understanding (NLU) and Natural Language Generation (NLG) with over 32+ pretrained models in 100+ languages and deep interoperability between TensorFlow 2.0 and PyTorch.
* [epfml/sent2vec](https://github.com/epfml/sent2vec)  
General purpose unsupervised sentence representations


### cv

* [opencv/opencv](https://github.com/opencv/opencv)  
Open Source Computer Vision Library https://opencv.org
* [Cadene/pretrained-models.pytorch](https://github.com/Cadene/pretrained-models.pytorch)  
Pretrained ConvNets for pytorch: NASNet, ResNeXt, ResNet, InceptionV4, InceptionResnetV2, Xception, DPN, etc.

### audio

* [kaldi-asr/kaldi](https://github.com/kaldi-asr/kaldi)  
Kaldi is a toolkit for speech recognition written in C++ and licensed under the Apache License v2.0. Kaldi is intended for use by speech recognition researchers. 

## 模型库

* [TensorFlowHub](https://tfhub.dev/)  
TensorFlow Hub is a library for the publication, discovery, and consumption of reusable parts of machine learning models.

## 模型可视化 & 可解释性

* [CSAILVision/GANDissect](https://github.com/CSAILVision/GANDissect)  
Pytorch-based tools for visualizing and understanding the neurons of a GAN. https://gandissect.csail.mit.edu/
* [tensorspace-team/tensorspace](https://github.com/tensorspace-team/tensorspace)  
神经网络 3D 可视化框架，有助于理解神经网络的内部结构
* [marcotcr/lime](https://github.com/marcotcr/lime)  
据说可以为任何机器学习分类器提供解释，有空研究下原理
* [slundberg/shap](https://github.com/slundberg/shap)  
SHAP (SHapley Additive exPlanations) is a game theoretic approach to explain the output of any machine learning model. It connects optimal credit allocation with local explanations using the classic Shapley values from game theory and their related extensions (see papers for details and citations).
* [christophM/interpretable-ml-book](https://github.com/christophM/interpretable-ml-book)  
Explaining the decisions and behaviour of machine learning models.


# 在线预测

* [Model interoperability](https://www.andrey-melentyev.com/model-interoperability.html)  
:memo:一个已经训练好的模型，要想提供在线预测服务，涉及到模型从离线训练环境到在线预测环境的数据交换，而不同的库/框架之间的互交换性不同。  
本文综述了
  1. 离线训练部分：各种库/框架之间的模型互交换性
  2. 在线预测部分：有哪些可用的框架？看起来 TensorFlow Serving 一枝独秀
  3. 专门的数据交换格式
     1. [onnx/onnx](https://github.com/onnx/onnx)  
     facebook、microsoft 联合出品，感觉上是老大（tensorflow）一枝独秀，老二老三只好联手
     2. PMML，在传统机器学习领域无竞争对手，但在深度学习领域，前景堪忧

## 传统机器学习

* [openscoring/openscoring](https://github.com/openscoring/openscoring)  
:computer:Java  
以 PMML 作为格式的模型文件部署在线预测服务，RESTful 客户端/服务器端实现，predict/evaluate 基于 [jpmml/jpmml-evaluator](https://github.com/jpmml/jpmml-evaluator)。
* [jpmml/jpmml-evaluator](https://github.com/jpmml/jpmml-evaluator)  
:computer:Java  
PMML 标准实现，形式：Library

## 其他

* [aaalgo/kgraph](https://github.com/aaalgo/kgraph)
* [nmslib/nmslib](https://github.com/nmslib/nmslib)
* [facebookresearch/faiss](https://github.com/facebookresearch/faiss)  
:memo:上述三者都是相似性搜索库，各有侧重。
  * kgraph 求解 k-NN(k-近邻) 问题，用户可自定义相似性计算函数
  * nmslib 和 kgraph 都是通用解决 k-NN 问题的框架
  * faiss 专注稠密向量的相似性搜索和聚合，特别适合 word2vec 后产生的隐因子
  

# 框架

## nlp
* [facebookresearch/pytext](https://github.com/facebookresearch/pytext)  
A natural language modeling framework based on PyTorch https://fb.me/pytextdocs  
:memo:将 fastText 的框架抽象成独立的 pyText，其价值在于：
  * 将 facebook 对 NLP 任务的 BestPractice 框架化，将变化的部分抽象成接口，为不变的部分提供胶水层代码
  * 已抽象的接口包括：
    * DataHandler，将用户数据转化成 Trainer 需要的数据
    * Trainer，模型训练器，在训练集上训练模型，并挑选表现最好的模型
    * 常见 NLP 任务的输入，如：文本分类
    * Model
    * Loss
    * Optimizer
    * MetricReporter
  * 内置大量模型实现，又给定制化留出可能性
  * 在线预测方面支持以 ONNX 格式导出到 Caffe2，提供了高效的多线程 C++ 后端
* [zalandoresearch/flair](https://github.com/zalandoresearch/flair)  
A very simple framework for state-of-the-art Natural Language Processing (NLP)
* [allenai/allennlp](https://github.com/allenai/allennlp)  
An open-source NLP research library, built on PyTorch. http://www.allennlp.org/

# 学习资源

## nlp

* [crownpku/Awesome-Chinese-NLP](https://github.com/crownpku/Awesome-Chinese-NLP)  
:memo:汇总了中文自然语言处理领域的各种优质资源
* github 搜索关键词  
[nlp](https://github.com/search?q=nlp)、[chinese](https://github.com/search?q=chinese)、[Natural Language Processing](https://github.com/search?q=Natural+Language+Processing)
* [Kyubyong/nlp_tasks](https://github.com/Kyubyong/nlp_tasks)  
Natural Language Processing Tasks and References  
:memo:自然语言处理领域要解决的问题列表
* [brightmart/text_classification](https://github.com/brightmart/text_classification)  
各种各样的文本分类模型
* [chenyuntc/PyTorchText](https://github.com/chenyuntc/PyTorchText)  
2017 知乎看山杯第一名的解决方案，问题：为知乎问题标注标签，每个标签对应知乎上的一个「话题」。
* [moneyDboat/data_grand](https://github.com/moneyDboat/data_grand)  
2018“达观杯”文本智能处理挑战赛-第10名“万里阳光号”解决方案，问题：长文本分类（文本平均长度>700字符)
* [graykode/nlp-tutorial](https://github.com/graykode/nlp-tutorial)  
Natural Language Processing Tutorial for Deep Learning Researchers https://www.reddit.com/r/MachineLearn…
* [文本分类指南 From Google](https://developers.google.com/machine-learning/guides/text-classification/)  

## PapersWeLove

* [floodsung/Deep-Learning-Papers-Reading-Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap)  
The roadmap is constructed in accordance with the following four guidelines:  
  * From outline to detail
  * From old to state-of-the-art
  * From generic to specific areas
  * Focus on state-of-the-art
* [wzhe06/Reco-papers](https://github.com/wzhe06/Reco-papers)  
[王喆](https://github.com/wzhe06)的推荐系统领域经典论文
* [wzhe06/Ad-papers](https://github.com/wzhe06/Ad-papers)  
[王喆](https://github.com/wzhe06)的广告系统领域经典论文

## MOOC

* [fast.ai](https://www.fast.ai/)  
* [deeplearning.ai](https://www.fast.ai/)  
:memo:根据[深度学习哪家强？吴恩达、Udacity和Fast.ai的课程我们替你分析好了](https://www.jianshu.com/p/28f5473c66a3)，fast.ai 更偏向实用性，对底层的数学原理介绍较少，适合入门，不适合深入；而 deeplearning.ai 更偏向建立牢固的理论基础（特别是数学），对应用场景的介绍较少。

## deep learning frameowrk

* [aymericdamien/TensorFlow-Examples](https://github.com/aymericdamien/TensorFlow-Examples)  
TensorFlow Tutorial and Examples for Beginners with Latest APIs https://tensorflow.org
* [yunjey/pytorch-tutorial](https://github.com/yunjey/pytorch-tutorial)  
PyTorch Tutorial for Deep Learning Researchers
* [Tencent/ncnn](https://github.com/Tencent/ncnn)  
ncnn is a high-performance neural network inference framework optimized for the mobile platform
* [pjreddie/darknet](https://github.com/pjreddie/darknet)  
:memo:[YOLO](https://pjreddie.com/darknet/yolo/)的神经网络库，C语言写成，支持CPU/GPU

## 其他

* [scutan90/DeepLearning-500-questions](https://github.com/scutan90/DeepLearning-500-questions)  
深度学习500问，以问答形式对常用的概率知识、线性代数、机器学习、深度学习、计算机视觉等热点问题进行阐述，以帮助自己及有需要的读者。
* [oxford-cs-deepnlp-2017/lectures](https://github.com/oxford-cs-deepnlp-2017/lectures)  
重点关注 deep-learning 在 nlp 中的应用，并非通用的 nlp 课程
* [tensorflow/nmt](https://github.com/tensorflow/nmt)  
TensorFlow Neural Machine Translation Tutorial
* [jindongwang/transferlearning-tutorial](https://github.com/jindongwang/transferlearning-tutorial)  
《迁移学习简明手册》LaTex源码 http://tutorial.transferlearning.xyz
* [GokuMohandas/practicalAI](https://github.com/GokuMohandas/practicalAI)  
A practical approach to learning machine learning.  
:memo:以 jupyter_notebook 形式写的一些教程（文字+code），传统机器学习和深度学习均有
* [Microsoft/Recommenders](https://github.com/Microsoft/Recommenders)  
This repository provides examples and best practices for building recommendation systems
* [yenchenlin/awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning)  
A curated list of awesome adversarial machine learning resources
* [karpathy/arxiv-sanity-preserver](https://github.com/karpathy/arxiv-sanity-preserver)  
Web interface for browsing, search and filtering recent arxiv submissions http://www.arxiv-sanity.com/

