# az_whatIsAI

Source：
<pre>
1.神经网络浅讲：从神经元到深度学习
http://www.cnblogs.com/subconscious/p/5058741.html

2.Tensorflow playground展示了数据是如何“流动”的。
http://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-gauss&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.25784&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=regression&initZero=false&hideText=false

3.
元原则：机器人不得实施行为，除非该行为符合机器人原则。（防止机器人陷入逻辑两难困境而当机）第零原则：机器人不得伤害人类整体，或者因不作为致使人类整体受到伤害。第一原则：除非违反高阶原则，机器人不得伤害人类个体，或者因不作为致使人类个体受到伤害。第二原则：机器人必须服从人类的命令，除非该命令与高阶原则抵触。机器人必须服从上级机器人的命令，除非该命令与高阶原则抵触。（处理机器人之间的命令传递问题）第三原则：如不与高阶原则抵触，机器人必须保护上级机器人和自己之存在。第四原则：除非违反高阶原则，机器人必须执行内置程序赋予的职能。（处理机器人在没有收到命令情况下的行为）繁殖原则：机器人不得参与机器人的设计和制造，除非新机器人的行为符合机器人原则。（防止机器人通过设计制造无原则机器人而打破机器人原则）

4.
机器人三大定律
第一定律：机器人不得伤害人，也不得见人受到伤害而袖手旁观。
第二定律：机器人应服从人的一切命令，但不得违反第一定律。
第三定律：机器人应保护自身的安全，但不得违反第一、第二定律。
         ——艾萨克·阿西莫夫《我，机器人》

5. books
计算机书籍控
http://bestcbooks.com/

6.
人工智能：用AIML写一个机器人
http://lcllcl987.iteye.com/blog/473256

7.小i机器人
http://www.xiaoi.com/cloud/ibotcloud.html

8.Eliza, computer therapist
http://manifestation.com/neurotoys/eliza.php3/

9. javascript robot
http://www.cleverscript.com/about/

10. Neural Conversational Model in Torch(Chinese)
https://github.com/majoressense/chatbot-zh-torch7

11. Neural Conversational Model in Torch
https://github.com/chenb67/neuralconvo

12. TORCH
http://torch.ch/
Torch is a scientific computing framework with wide support for machine learning algorithms that puts GPUs first. It is easy to use and efficient, thanks to an easy and fast scripting language, LuaJIT, and an underlying C/CUDA implementation.

A summary of core features:

    a powerful N-dimensional array
    lots of routines for indexing, slicing, transposing, …
    amazing interface to C, via LuaJIT
    linear algebra routines
    neural network, and energy-based models
    numeric optimization routines
    Fast and efficient GPU support
    Embeddable, with ports to iOS and Android backends

13. A Neural Conversational Model (google)
https://arxiv.org/pdf/1506.05869v2.pdf

14. Google's artificial intelligence bot thinks the purpose of life is 'to live forever'
https://www.businessinsider.com.au/google-tests-new-artificial-intelligence-chatbot-2015-6

15. 第773回：自然対話プラットフォーム とは
http://k-tai.watch.impress.co.jp/docs/column/keyword/1020914.html

16. UnityでBotが作れるアセット「Chatbot」を試してみました
http://magicbullet.hatenablog.jp/entry/UnityAsset_Chatbot

17. docomoシナリオ対話
https://dev.smt.docomo.ne.jp/?p=docs.api.page&api_name=scenario_dialogue&p_name=api_usage_scenario

18. AIでユーザの悩みを解決
https://repl-ai.jp/

19. チャットボットの対話設計ができる対話サービスまとめ 〜Docomo対話サービスからAmazon Lexまで〜
http://qiita.com/shiraco/items/eca5d0a6fc7fe6fb0f37

20.国語研日本語ウェブコーパス
http://pj.ninjal.ac.jp/corpus_center/nwjc/

21. AIMLチュートリアル
http://www.w3ii.com/ja/aiml/default.html

22. pandorabots.com
https://www.pandorabots.com/botmaster/ja/home

23. [TODO]


24. [TODO]

25. [TODO]

每天AI资讯这么多！该看哪些？”推荐一份优质资料清单

https://github.com/BAILOOL/DoYouEvenLearn
http://mp.weixin.qq.com/s/beIv40FGNRm5qGmxQldv8Q

26. DL4J与Torch、Theano、TensorFlow、Caffe、Paddle、MxNet、Keras 和 CNTK的比较
https://deeplearning4j.org/cn/compare-dl4j-torch7-pylearn.html

27. TensorFlow ドキュメント/応用 – ClassCat® AI Research – AI ビジネス導入コンサルティング
http://tensorflow.classcat.com/category/nlp/

28. tensorflow seq2seq chatbot for Japanese
https://github.com/tattn/tensorflow-chatbot-jp

29. いますぐ使える単語埋め込みベクトルのリスト
https://qiita.com/Hironsan/items/8f7d35f0a36e0f99752c

まずは定番な3つ: Word2Vec, GloVe, fastText
Word2Vec
一言コメント 	言わずと知れたWord2Vecの事前学習済みベクトル。何を使えばいいのかわからないならこれを使っておけば間違いはない。
発表年数 	2013年
URL 	https://code.google.com/archive/p/word2vec/

日本語を含めた多言語の学習済みベクトルは以下のリンク先からから入手することができる:

    https://github.com/Kyubyong/wordvectors

GloVe
一言コメント 	Stanfordが誇るGloVe。Word2Vecより良い性能だと謳っている。グローバルな行列分解のモデルとlocal context windowのモデルを組み合わせてよい単語ベクトルを学習した。
発表年数 	2014年
URL 	http://nlp.stanford.edu/projects/glove/
fastText
一言コメント 	Word2Vecを作った天才Mikolovが作ったfastText。とにかく学習が早い。形態素を考慮するために各単語を文字ngramで表現し、それらのベクトル表現を学習している。
発表年数 	2016年
URL1 	Download Word Vectors
URL2 	Download Word Vectors(NEologd)

※ 日本語のみ

使い方含めて以下に書きました。
fastTextの学習済みモデルを公開しました
最新の成果が適用された3つの事前学習ベクトル
Dependency-Based Word Embeddings
一言コメント 	Levyらによる単語埋め込みベクトル。依存関係を用いて学習させたことで、syntacticなタスクに強くなった。syntacticなタスクに使いたい場合はこれがいいかも。
発表年数 	2014年
URL 	https://levyomer.wordpress.com/2014/04/25/dependency-based-word-embeddings/
Meta-Embeddings
一言コメント 	ACL2016で発表されたMeta-Embeddings。異なる性質を持つ単語埋め込みベクトルの集合を組み合わせて、より良いベクトル(meta embedding)を得ることに成功した。ベクトル集合を組み合わせることでボキャブラリのカバレッジをあげられることがメリット。
発表年数 	2016年
URL 	http://cistern.cis.lmu.de/meta-emb/
LexVec
一言コメント 	こちらもACL2016で発表されたLexVec。単語類似度タスクではいくつかの評価セットにおいてWord2Vecを上回る結果を残している。
発表年数 	2016年
URL 	https://github.com/alexandres/lexvec

</pre>
