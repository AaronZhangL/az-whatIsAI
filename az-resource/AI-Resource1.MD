Node-REDとはIBMが開発したオープンソース・ツールで、APIなどの各種サービスやファンクションを連係できるツールのこと。コーディングをせずに、視覚で直感的にアプリケーションの実行および開発ができる。

https://github.com/AaronZhangL/ChatterBot


形態素解析・係り受け解析

品詞タイプの判定などを行う「形態素解析」と、語句のつながりを解析する「係り受け解析」があることがわかりました。コマンドを作成するには「何をどうする」というつながりが重要なので、係り受け解析まで行う必要があります。

日本語の形態素解析・係り受け解析にはいくつかの有名なライブラリがあり、それぞれ出力の形式や内容によって系列があるようです。
形態素解析 	係り受け解析 	雑感
ChaSen, MeCab 	CaboCha 	パッケージに一日の長。関連パッケージが開発しやすく、優秀な辞書が多い
juman, juman++ 	knp 	機能的に尖っているイメージ？
kuromoji 	? 	純jsの実装があるのは便利そうだが、係り受け解析の実績が見つからなかった

他には形態素解析だとKAKASI, KyTeaなどが有名なようですが、係り受け解析を見つけることができませんでした。（見つけられなかっただけかもしれません）

--------------------------------------------------------------
Bot開発フレームワーク

複数のメッセージングアプリでチャットボットを作りたい場合、Bot開発フレームワークを利用する方法があります。フレームワークによっては対応していないプラットフォームもありますが、適切なフレームワークを選択すればプログラミングをする時間が短縮できます。

    botkit（Slack、Facebookメッセンジャーに対応）
    Microsoft Bot Framework（Skype、Slack、Facebookメッセンジャー等に対応）
    Amazon Lex（Facebookメッセンジャー、LINE等に対応）

---------------------------------------------------------------
日本語を理解するチャットボットに挑戦した話【デモあり】
http://tech.plaid.co.jp/chatbot-understanding-japanese/

https://github.com/otolab/halumi-core

---------------------------------------------------------------
QnA Mekerとは？https://qnamaker.ai/

Microsoftが提供するCognitive Serviceに仲間入りしたサービスで、質問と答えのリストかFAQ形式のWebページから、ノンコーディングでQ＆A BOTを自動で生成してくれるサービス。併せてAzure Bot Serviceを利用すれば、SkypeやSlack、Web Chatなどのサービスに対応するBOTが簡単に作れます。手軽なのにできることがすごいｗ
---------------------------------------------------------------
お問い合わせチャットBOTをノンコーディングで作ってみた話（QnA Maker + Bot Service）
http://zuvuyalink.net/nrjlog/archives/3798

---------------------------------------------------------------
https://ask.julyedu.com/article/349
认知架构

ACT-R
ACT-R由卡内基·梅隆大学开发，它既是人类认知理论的名称，又是基于该理论的软件的名称。该软件基于Lisp，提供详细的说明文档。
支持的操作系统：Windows、Linux和macOS
链接：http://act-r.psy.cmu.edu/software/

深度学习

Caffe
Caffe最初由加州大学伯克利分校的一名博士生创建，已成为一种大受欢迎的深度学习框架。它赖以成名的方面包括富有表现力的架构、可扩展代码和速度。
支持的操作系统：Windows、Linux和macOS
链接：http://caffe.berkeleyvision.org/

CaffeOnSpark
该项目最初在雅虎开发而成，将Caffe深度学习框架引入到Hadoop和Spark集群。它用于图像搜索和内容分类以及其他使用场合。
支持的操作系统：Windows、Linux和macOS
链接：https://github.com/yahoo/CaffeOnSpark

ConvNetJS
这个JavaScript库让用户可以从浏览器来训练深度学习模型。它承诺“无软件要求、无需编译器、无需安装、无需GPU、无需流汗水。”
支持的操作系统：Linux
链接：http://cs.stanford.edu/people/karpathy/convnetjs/

DeepDetect
DeepDetect被空中客车和微软之类的企业组织所使用，它是基于Caffe、TensorFlow和XGBoost的开源深度学习服务器系统。它为图像分类、对象检测、文本及数字数据分析提供了一套易于使用的API。
支持的操作系统：Windows、Linux和macOS
链接：https://deepdetect.com/

Deeplearning4j
Deeplearning4j声称是“为Java和Scala编写的第一个商业级开源分布式深度学习库。”通过Skymind提供商业支持。
支持的操作系统：Windows、Linux和macOS
链接：http://deeplearning4j.org/

DSSTNE
DSSTNE的全称是“深度可扩展稀疏张量网络引擎”，它是亚马逊用来训练和部署其推荐引擎的软件库。主要功能包括：多GPU规模、大层次以及可处理稀疏数据集。
支持的操作系统：Windows、Linux和macOS
链接：https://github.com/amzn/amazon-dsstne

H2O
H2O拥有10多万用户，声称是“世界领先的开源深度学习平台。”除了开源版本，该公司还供应提供付费支持的高级版。
支持的操作系统：Windows、Linux和macOS
链接：http://www.h2o.ai/

微软认知工具包
微软认知工具包以前名为CNTK，承诺可训练深度学习算法，像人脑那样思考。它拥有速度快、可扩展性、商业级质量以及与C++和Python兼容等优点。微软使用它来支持Skype、Cortana和必应（Bing）中的AI功能。
支持的操作系统：Windows和Linux
链接：https://www.microsoft.com/en-us/cognitive-toolkit/

Theano
Theano适用于深度学习，自称是“一种Python库，让你可以高效地定义、优化和评估涉及多维数组的数学表达式。”主要功能包括GPU支持、与NumPy整合、高效的符号微分法、C代码动态生成等更多功能。
支持的操作系统：Windows、Linux和macOS
链接：http://www.deeplearning.net/software/theano/

游戏

DeepMind Lab
DeepMind Lab旨在用于AI研究，它是一种3D游戏环境。它由谷歌的DeepMind部门开发而成，据说尤其适用于深度强化学习研究。
支持的操作系统：Linux
链接：https://deepmind.com/research/ ... -lab/

Project Malmo
Project Malmo是微软领导的项目，使用游戏《我的世界》作为AI研究平台。据官网声称：“《我的世界》对人工智能研究而言很理想，这跟它吸引着每天进入其虚拟世界的成千上万粉丝是同一个道理。不像其他电脑游戏，《我的世界》为用户提供了无穷无尽的可能性，从简单任务（比如一路寻宝）到复杂任务（比如与一群队友搭建建筑物），不一而足。”
支持的操作系统：Windows、Linux和macOS
链接：https://www.microsoft.com/en-u ... almo/

《星际争霸II》 API库
谷歌的DeepMind和暴雪娱乐公司在共同开展一个项目，可使用《星际争霸II》视频游戏作为AI研究平台。它是一种跨平台的C ++库，可用于构建脚本化的机器人程序。
支持的操作系统：Windows、Linux、macOS、Android和iOS
链接：https://us.battle.net/forums/e ... 16786

Stockfish
这个开源国际象棋引擎是世界上最好的引擎之一，可击败大多数人类大师。请注意：它还有一个移动应用程序。
支持的操作系统：Windows、Linux和macOS
链接：https://stockfishchess.org/

梯度提升

XGBoost
XGBoost支持梯度提升树，这是一种易于训练的决策权，提供了神经网络之外的一种选择。它支持回归、分类、排序及其他类型的算法。
支持的操作系统：Windows、Linux和macOS
链接：http://xgboost.readthedocs.io/en/latest/

机器智能

Numenta
Numenta组织提供了与层级实时记忆（HTM）有关的众多开源项目。实际上，这些项目试图基于生物界对于人类新大脑皮层的了解来生成机器智能。
支持的操作系统：Windows、Linux和macOS
链接： http://numenta.org/

Open Cog
Open Cog不是专注于AI的狭窄方面，比如深度学习或神经网络，旨在生成有益的强人工智能（AGI）。该项目正致力于打造能够拥有类人智能的系统和机器人。
支持的操作系统：Linux
链接：http://opencog.org/

机器学习

Accord.NET框架
Accord.NET承诺机器学习可在“1分钟内搞定”。它基于微软技术，包括示例应用程序和详细的说明文档，以帮助开发人员迅速创建生产环境级计算机视觉、计算机听觉、信号处理和统计应用软件。
支持的操作系统：Windows
链接：http://accord-framework.net/

AForge.NET框架
AForge.NET专为计算机视觉和人工智能应用而设计，这种C#框架适用于图像处理、神经网络、遗传算法、模糊逻辑、机器学习和机器人等。它包括几个库和示例应用程序。
支持的操作系统：Windows
链接：http://www.aforgenet.com/framework/

Aerosolve
这个“为人类设计的机器学习包”由Airbnb创建，旨在帮助为主机支持动态定价建议。它基于Java，特别适用于拥有地理位置相关变量的项目。
支持的操作系统：Windows、Linux和macOS
链接：http://airbnb.io/aerosolve/

分布式机器学习工具包
这个微软机器学习项目包括DMTK框架、Light LDA主题模型算法、分布式（多重）单词嵌入算法以及LightGBM梯度提升树框架。随着研究深入开展，该公司计划为该工具包添加更多的算法和组件。
支持的操作系统：Windows和Linux
链接：http://www.dmtk.io/

Dlib
Dlib提供了一套可快速执行的C ++机器学习库。它包括诸多算法，可用于二进制分类、多类分类、回归、结构预测、深度学习、聚类、非监督学习、半监督/度量学习、强化学习和特征选择。
支持的操作系统：Windows、Linux和macOS
链接：http://dlib.net/ml.html

Encog
Encog自2008年以来就在积极开发中，它是由数据科学家杰夫·希顿（Jeff Heaton）创建的一种机器学习框架。它支持神经网络、支持向量机、贝叶斯网络、隐马尔可夫模型、遗传编程和遗传算法。
支持的操作系统：Windows、Linux和macOS
链接：http://www.heatonresearch.com/encog/

GoLearn
GoLearn自诩为面向Go编程语言的“一应俱全的”机器学习库。它力求简单性和可定制性。
支持的操作系统：Linux和macOS
链接：https://github.com/sjwhitworth/golearn

Mahout
Mahout是Apache软件基金会赞助的众多机器学习项目之一，它提供了用于构建可扩展的机器学习应用程序的编程环境和框架。它还包括预制算法和名为Samsara的向量数学实验环境。
支持的操作系统：Windows、Linux和macOS
链接：http://mahout.apache.org/

MLlib
作为Apache Spark项目的一部分，MLlib是一个机器学习库，承诺性能比MapReduce高100倍。它包括众多算法，用于分类、回归、决策树、推荐、聚类、主题建模、模式挖掘等。
支持的操作系统：Windows、Linux和macOS
链接：https://spark.apache.org/mllib/

Pattern
基于Python的Pattern提供了众多工具，可用于数据挖掘、自然语言处理、机器学习、网络分析和可视化。它尤其适用于Web挖掘这个应用场合。
支持的操作系统：Windows、Linux和macOS
链接：https://www.clips.uantwerpen.be/pages/pattern

Prophet
Prophet由Facebook开发和使用，可预测时间序列数据。它是用R或Python实现的，具有全自动、准确、快速和可调整​优的特点。
支持的操作系统：Windows和Linux
链接：https://facebookincubator.github.io/prophet/

Oryx 2
Oryx 2由Cloudera开发，实现了用于机器学习的lambda架构。它基于Apache Spark和Kafka。
支持的操作系统：Windows、Linux和macOS
链接：http://oryx.io/

PredictionIO
PredictionIO现在是Apache孵化项目，这种机器学习服务器系统拥有可定制模板、实时查询响应、从多个平台获取数据的功能等特性。它与其他开源工具整合起来，比如Spark、Mllib、HBase、Spray和Elasticsearch。
支持的操作系统：Windows、Linux和macOS
链接：http://predictionio.incubator. ... .html

SAMOA
SAMOA是Apache孵化项目，全称是“可扩展高级大规模在线分析”。它是一种面向分布式流应用的机器学习框架。
支持的操作系统：Linux
链接：https://samoa.incubator.apache.org/

Scikit-learn
Scikit-learn基于NumPy、SciPy和matplotlib，提供了用于机器学习的Python工具。它使用分类、回归、聚类以及降维等方面的算法来处理数据挖掘和数据分析。
支持的操作系统：Windows和Linux
链接：http://scikit-learn.org/stable/

Shark
Shark自称是一种“快速、模块化、功能丰富的开源C ++机器学习库。”它提供了监督学习、非监督学习、进化算法、基本线性代数以及优化等方面的算法。
支持的操作系统：Windows、Linux和macOS
链接：http://image.diku.dk/shark/sph ... .html

Shogun
Shogun自1999年以来就在开发中，它是一套成熟的机器学习工具，支持Python、Octave、R、Java/Scala、Lua、C#、Ruby及其他语言。它还有一项免费的云服务，用户可以试用该软件。
支持的操作系统：Windows、Linux和macOS
链接：http://www.shogun-toolbox.org/

Smile
Smile的全称是“统计机器智能和学习引擎”，拥有极快的机器学习，支持Java、Scala及其他JVM语言。它声称“性能显著优于R、Python、Spark、H2O和xgboost。”
支持的操作系统：Windows、Linux和macOS
链接：http://haifengl.github.io/smile/

SystemML
SystemML最初是IBM研究部门的一个项目，现在是Apache顶级项目。它自称是“使用大数据进行机器学习的最佳工作环境”，并与Spark整合起来。
支持的操作系统：Windows、Linux和macOS
链接：http://systemml.apache.org/

TensorFlow
TensorFlow由谷歌大脑团队开发，供谷歌内部使用，现在是最著名的开源机器学习平台之一。谷歌还向研究人员免费提供基于云的TensorFlow版本（https://www.tensorflow.org/tfrc/）。
支持的操作系统：Windows、Linux、macOS和Android
链接：https://www.tensorflow.org/

Torch
Torch基于LuaJIT，是一种“科学计算框架，广泛支持机器学习算法。”主要功能包括强大的N维数组、GPU支持、线性代数例程和神经网络等。
支持的操作系统：Linux和macOS
链接：http://torch.ch/

WEKA
基于Java的WEKA提供了适用于数据挖掘的众多机器学习算法。它是在新西兰怀卡托大学开发的，以一种好奇心非常强的新泽西鸟命名。
支持的操作系统：Windows、Linux和macOS
链接：http://www.cs.waikato.ac.nz/~ml/weka/

自然语言处理

Stanford CoreNLP
这种基于Java的自然语言处理软件可识别单词的基本形式、词性以及它们是不是公司或人员的名称，还能规范日期和时间，从短语和句法依赖关系来标记句子结构，表明名词短语是不是指同样的实体，识别情感，提炼提及的实体之间特定或开放式的关系，并获得引用。它是为英语设计的，但也支持阿拉伯语、汉语、法语、德语和西班牙语。
支持的操作系统：Windows、Linux和macOS
链接：https://stanfordnlp.github.io/CoreNLP/

MALLET
MALLET全称是“机器学习语言E工具包”，包括用于统计自然语言处理、文档分类、聚类、主题建模、信息提取等方面的工具。它最初是在2002年由马萨诸塞州大学阿默斯特分校和宾夕法尼亚大学的师生共同开发的。
支持的操作系统：Windows和Linux
链接：http://mallet.cs.umass.edu/

OpenNLP
OpenNLP是个Apache项目，执行自然语言处理任务，比如标记化、句子分割、词性标注、命名实体提取、分块、解析、语言检测和共指消解。新西兰航空公司的聊天机器人Oscar基于该项目。
支持的操作系统：Windows、Linux和macOS
链接：https://opennlp.apache.org/

神经网络

Darknet
Darknet用C和CUDA编写，支持使用CPU或GPU计算的神经网络。它提供了出色的图像分类功能。
支持的操作系统：Linux
链接：https://pjreddie.com/darknet/

DyNet
DyNet之前名为cnn，是一种面向C++和Python的神经网络库，主要在卡内基·梅隆大学开发而成。它适合于语法解析、机器翻译和形态曲折变化更多应用场合。
支持的操作系统：Windows、Linux和macOS
链接：https://dynet.readthedocs.io/en/latest/#

Neuroph
Neuroph最初只是一个研究生论文项目，这是种基于Java的轻量级神经网络框架。旨在用起来足够容易，那样初学者可以快速入门，同时又提供高级用户需要的灵活性和工具。
支持的操作系统：Windows和Linux
链接：http://neuroph.sourceforge.net/

OpenNN
OpenNN全称“开放神经网络”，是用于实现神经网络的C++库。它声称拥有高性能和深度架构。提供商业支持。
支持的操作系统：Windows、Linux和macOS
链接：http://www.opennn.net/

Sonnet
Sonnet由谷歌的DeepMind团队开发，这种神经网络库在TensorFlow上运行。据开发人员声称，它提供了比其他TensorFlow框架更强的灵活性。
支持的操作系统：Linux和macOS
链接：https://deepmind.github.io/sonnet/

虚拟助理

Mycroft
Mycroft自称是“世界上第一个开源助理。”它可回答问题、播放音频及视频、控制与物联网连接的设备等。它对系统的要求很低，甚至可以在Raspberry Pi上运行。
支持的操作系统：Windows、Linux和macOS
链接：https://mycroft.ai/

Open Assistant
Open Assistant仍在大力开发中，旨在提供Siri、Cortana和Google Now之外的一种开源选择。目的是创建一种能够进行交谈的完全可定制的AI。
支持的操作系统：Linux
链接：http://openassistant.org/about/

---------------------------------------------------------------
https://github.com/ty4z2008/Qix/blob/master/dl.md

---------------------------------------------------------------
Loading Wikipedia's Search Index For Testing
http://www.elastic.co/blog/loading-wikipedia

#维基百科简体中文语料的获取
http://licstar.net/archives/262

#维基百科简体中文dump
：http://download.wikipedia.com/zhwiki/latest/zhwiki-latest-pages-articles.xml.bz2

#使用 Wikipedia Extractor 抽取正文文本
Wikipedia Extractor 是意大利人用 Python 写的一个维基百科抽取器，使用非常方便。下载之后直接使用这条命令即可完成抽取，运行了大约半小时的时间。
　　bzcat zhwiki-latest-pages-articles.xml.bz2 | python WikiExtractor.py -b 1000M -o extracted >output.txt
　　参数 -b 1000M 表示以 1000M 为单位切分文件，默认是 500K。由于最后生成的正文文本不到 600M，把参数设置的大一些可以保证最后的抽取结果全部存在一个文件里。
  
#繁简转换
解决这个问题最佳的办法应该是直接使用维基百科自身的繁简转换方法（参照 http://zh.wikipedia.org/wiki/Wikipedia:繁简处理）。不过维基百科网站虽然是开源的，但要把里面的繁简转换功能拆解出来，有一定的难度。
　　为了方便起见，我直接使用了开源项目 opencc。参照安装说明的方法，安装完成之后，使用下面的命令进行繁简转换，整个过程大约需要1分钟。
　　opencc -i wiki_00 -o wiki_chs -c zht2zhs.ini
　　命令中的 wiki_00 这个文件是此前使用 Wikipedia Extractor 得到的。
  
  
