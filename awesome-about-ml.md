emoji|含义
-----|--
:clap:|我在实际项目中使用过
:computer:|支持的编程语言
:memo:|我的备注
:bug:|使用中踩过的坑

_注：你可以通过复制此 emoji 到页面内搜索窗口，以实现快速定位到指定 emoji_

# Datasets

* [Google Dataset Search](https://toolbox.google.com/datasetsearch)
* [candlewill/Dialog_Corpus](https://github.com/candlewill/Dialog_Corpus)  
用于训练中英文对话系统的语料库 Datasets for Training Chatbot System
* [chinese-poetry/chinese-poetry](https://github.com/chinese-poetry/chinese-poetry)  
最全中华古诗词数据库, 唐宋两朝近一万四千古诗人, 接近5.5万首唐诗加26万宋诗. 两宋时期1564位词人，21050首词。 http://shici.store

# 数据处理

* [pandas-dev/pandas](https://github.com/pandas-dev/pandas)  
Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.frame objects, statistical functions, and much more https://pandas.pydata.org

## nlp

* :clap:[fxsjy/jieba](https://github.com/fxsjy/jieba)  
:computer:Python  
结巴中文分词
* [thulac](http://thulac.thunlp.org/)  
:computer:C++/Java/Python  
:memo:清华的中文分词工具包，其最大的价值是对分词能力引入了量化衡量指标。如果用于商业用途，需要授权

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
* [cjlin1/libsvm](https://github.com/cjlin1/libsvm)  
libsvm 既是一个 svm 模型的实现，又是一种机器学习样本数据格式，非常适合描述高维稀疏样本
* [quora/qmf](https://github.com/quora/qmf)  
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

* [hankcs/HanLP](https://github.com/hankcs/HanLP)  
HanLP是一系列模型与算法组成的NLP工具包，功能包括：中文分词、磁性标注、命名实体识别、关键词提取、自动摘要、短语提取、拼音转换、简繁转换、文本推荐、依存句法分析、文本分类、文本聚类、word2vec、语料库工具等
* [isnowfy/snownlp](https://github.com/isnowfy/snownlp)  
Python library for processing Chinese text
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

### cv

* [opencv/opencv](https://github.com/opencv/opencv)  
Open Source Computer Vision Library https://opencv.org

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

* [https://github.com/facebookresearch/pytext](https://github.com/facebookresearch/pytext)  
A natural language modeling framework based on PyTorch https://fb.me/pytextdocs  
:memo:将 fastText 的框架抽象成独立的 pyText，为「离线训练+模型评估（常见评估指标）+在线预测」提供胶水层代码

# 学习资源

## nlp

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

## 其他

* [floodsung/Deep-Learning-Papers-Reading-Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap)  
The roadmap is constructed in accordance with the following four guidelines:  
  * From outline to detail
  * From old to state-of-the-art
  * from generic to specific areas
  * focus on state-of-the-art
* [scutan90/DeepLearning-500-questions](https://github.com/scutan90/DeepLearning-500-questions)  
深度学习500问，以问答形式对常用的概率知识、线性代数、机器学习、深度学习、计算机视觉等热点问题进行阐述，以帮助自己及有需要的读者。
* [fast.ai](https://www.fast.ai/)  
* [deeplearning.ai](https://www.fast.ai/)  
:memo:根据[深度学习哪家强？吴恩达、Udacity和Fast.ai的课程我们替你分析好了](https://www.jianshu.com/p/28f5473c66a3)，fast.ai 更偏向实用性，对底层的数学原理介绍较少，适合入门，不适合深入；而 deeplearning.ai 更偏向建立牢固的理论基础（特别是数学），对应用场景的介绍较少。
* [oxford-cs-deepnlp-2017/lectures](https://github.com/oxford-cs-deepnlp-2017/lectures)  
重点关注 deep-learning 在 nlp 中的应用，并非通用的 nlp 课程
* [tensorflow/nmt](https://github.com/tensorflow/nmt)  
TensorFlow Neural Machine Translation Tutorial
* [jindongwang/transferlearning-tutorial](https://github.com/jindongwang/transferlearning-tutorial)  
《迁移学习简明手册》LaTex源码 http://tutorial.transferlearning.xyz
* [aymericdamien/TensorFlow-Examples](https://github.com/aymericdamien/TensorFlow-Examples)  
TensorFlow Tutorial and Examples for Beginners with Latest APIs https://tensorflow.org
* [GokuMohandas/practicalAI](https://github.com/GokuMohandas/practicalAI)  
A practical approach to learning machine learning.  
:memo:以 jupyter_notebook 形式写的一些教程（文字+code），传统机器学习和深度学习均有
