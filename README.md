# 机器学习方向学习路线

1.  入门（从应用开始入门，相较于直接学习枯燥的理论基础会更容易接受）

    1.  Python

        1.  Python语言

        2.  Python相关计算库

            1.  numpy

            2.  scipy

            3.  pandas

            4.  matplotlib

        3.  【核心】Python机器学习库

            1.  Pytorch：【PyTorch深度学习快速入门教程（绝对通俗易懂！）【小土堆】】
                <https://www.bilibili.com/video/BV1hE411t7RN/?share_source=copy_web&vd_source=2b792907e36420eef6c08d474550f3b0>

            2.  scikitlearn

        4.  参考资料：《动手学深度学习Pytorch版》、官方文档及tutorial、《利用Python进行数据分析》（主要是入门基础语法以及各种库的使用）

    2.  综合实战：

        1.  猫狗分类识别任务[[https://blog.csdn.net/2301_76794217/article/details/139429485?sharetype=blogdetail&amp;sharerId=139429485&amp;sharerefer=WAP&amp;sharesource=]{.underline}](https://blog.csdn.net/2301_76794217/article/details/139429485?sharetype=blogdetail&sharerId=139429485&sharerefer=WAP&sharesource=)

        2.  Tatanic生存预测 <https://zhuanlan.zhihu.com/p/31743196>

    3.  备注：入门阶段不用深究算法原理，重点是在机器学习库的使用中了解机器学习的主要流程，并学会如何在比赛中应用这些模型，熟悉用Python相关库完成数据读取、数据预处理、特征工程、模型训练、模型评估等常规操作，学完这个阶段如果有时间就可以到Kaggle打一些练习赛了，比如：
        波士顿房价预测：<https://www.kaggle.com/c/home-data-for-ml-course>
        垃圾邮件分类: <https://www.kaggle.com/c/ds100fa19>

2.  基础（这部分是基础理论，未来你想走得更远，学得更深就需要把这部分内容学扎实）

    1.  数学基础

        1.  数学分析： 《数学分析原理》
            （把目标放在多元函数/向量函数微分学、函数的增长性和上下界分析上，不要纠结于怎么花式计算积分!）

        2.  高等代数+矩阵分析： 《线性代数应该这样学》+《矩阵分析》
            网课：
            <https://www.bilibili.com/video/BV1qt41167Sj?from=search&seid=15919091007434427062>
            （把目标放在线性空间和线性映射上，不要纠结于行列式的运算技巧!）

        3.  概率论： 《概率论及其应用》

        4.  统计学： 《统计推断》

        5.  运筹学与最优化 ：《线性与非线性规划》
            北京大学文再文老师出的新书《最优化：建模、算法与理论》及其配套课程非常不错，课程地址：<https://bicmr.pku.edu.cn/~wenzw/optbook.html>

        6.  离散数学：《计算机科学中的数学》
            网课：<https://www.bilibili.com/video/BV1Kb411n7oa>
            （最好把离散数学和算法结合在一起学，像组合数学和图论和算法联系非常紧密）

    2.  计算机基础（正常入门后这部分是已经足够的，但需要继续学更多用法以及项目工程思想）

        1.  Python语言:《流畅的Python》《Python CookBook》《Effective
            Python》
            （Python入门简单，想用好还是很难的，看完这几本书面试语言关是没问题的）

        2.  数据结构与算法：《算法导论》 网课：
            <https://www.bilibili.com/video/BV1Tb411M7FA?from=search&seid=5296358882076036915>
            实践部分可以看《挑战程序设计竞赛》然后多刷题（这类题属于传统算法题和文件操作题，更容易练基础）

    3.  机器学习基础：《统计学习方法》《机器学习》 网课：
        <https://www.bilibili.com/video/BV1rs411371e?from=search&seid=2750957756897025160>
        <https://www.bilibili.com/video/BV1jt411b76n>
        推公式！推公式！推公式！重要的事情说三遍，能自己从零实现算法更好
        ，在实践算法上遇到困难可以参考这个GitHub代码实践仓库：<https://github.com/datawhalechina/statistical-learning-method-solutions-manual>

    4.  深度学习

        1.  原理：《动手学深度学习Pytorch版》《深度学习》

        2.  实践：

            1.  直接参考深度学习框架的官方样例，比如Pytorch的：
                <https://github.com/pytorch/examples>
                Tensorflow的：<https://github.com/tensorflow/examples>

            2.  Tensorflow文档，Pytorch文档

            3.  实践时尽量要独立地搭建一个网络，对框架常用API要很熟练

    5.  备注：基础非常重要，尤其是数学基础，这些基础知识学一遍是不够的，要来回看。基础的机器学习与深度学习公式要会熟练推导。此外基础的算法要自己动手实现一遍体会才会深刻，这里给一个统计学习方法的算法实现地址：<https://github.com/WenDesi/lihang_book_algorithm>，算法导论习题答案地址：<https://github.com/gzc/CLRS>

3.  进阶（以下分方向是考虑到大家的精力有限，当然你很强的话可以学术和工程全都要）

    1.  算法研究方向（面向读研的同学）

        1.  数学进阶

            1.  随机过程：《随机过程》

            2.  多元统计：《实用多元统计》

            3.  凸优化：《凸优化》

        2.  算法进阶

            1.  随机算法：《概率与计算》

            2.  数值算法：《数值分析》《矩阵计算》

        3.  方向性课程：

            1.  计算机视觉：《计算机视觉：算法与应用》
                斯坦福CS231网课：<https://www.bilibili.com/video/BV1nJ411z7fe?spm_id_from=333.337.search-card.all.click>

            2.  自然语言处理：
                《统计自然语言处理》《基于深度学习的自然语言处理》
                网课：<https://www.bilibili.com/video/BV1pt411h7aT>
                (自然语言处理的embedding、word2vec技术在很多领域都非常广泛)

            3.  推荐系统：《深度学习推荐系统》
                （这本书强烈推荐，闪烁着工程师特有的智慧）

            4.  广告算法：《计算广告》

            5.  前沿热点：

                1.  联邦学习

                2.  强化学习

                3.  迁移学习

                4.  Auto ML

                5.  语言大模型

    2.  算法工程方向（大规模机器学习系统）

        1.  计算机进阶（做这个方向的话需要更多的计算机基础，当然不用太深，但要知道基础的概念）

            1.  计算机系统：《深入理解计算机系统》
                网课：<https://www.bilibili.com/video/BV1iW411d7hd>

            2.  Linux：《鸟哥的Linux私房菜》

            3.  数据库：《数据库系统基础教程》
                (主要学一下SQL怎么写，NoSQL数据库也要了解一下)

            4.  分布式系统：《数据密集型应用系统设计》
                论文:Google的三篇paper MIT
                6.824网课：<https://www.bilibili.com/video/BV1R7411t71W>

        2.  机器学习系统

            1.  《机器学习系统：设计与实现》<https://openmlsys.github.io/index.html>
                课程可以参考华盛顿大学的 CSE599W ：Systems for
                ML<https://dlsys.cs.washington.edu/>

        3.  分布式计算：

            1.  海量数据处理：

                1.  Hadoop

                2.  Spark

                3.  Hive

                4.  参考资料：官方文档
                    +《Hadoop权威指南》《Spark权威指南》《Hive编程指南》

            2.  分布式机器学习：

                1.  Spark MLlib

                2.  Parameter Server（已经被Tensorflow集成，调API即可）

                3.  参考资料：《分布式机器学习》（可以试着用Spark实现一个并行的梯度下降算法）
                    斯坦福CS323：分布式算法与优化：<https://stanford.edu/~rezab/classes/cme323/S17/>

        4.  云计算：

            1.  Docker

            2.  K8s

            3.  CMU 15-619
                云计算：<http://www.cs.cmu.edu/~msakr/15619-f21/>

        5.  高性能计算

            1.  CUDA

            2.  MPI

    3.  备注：这个时期非常长，甚至从本科到研究生甚至到工作后都会持续这个阶段。很多东西只有在实践中才会有深刻体会。这个阶段你可以参加许多学科竞赛来锻炼自己的能力。如云计算方面有：全国高校云计算应用创新大赛，大数据与计算智能挑战赛，华为软件精英挑战赛等；高性能计算有：先导杯，PAC，ASC等；数据科学竞赛有：全国高校计算机大赛：大数据挑战赛，泰迪杯数据挖掘竞赛等。还有一些广告算法、风控类的商业赛也很能锻炼你的水平。此外数学建模、蓝桥杯等传统学科竞赛也要积极参与。最后，要多阅读最新论文，关注一下Github上开源的最新模型，跟上学术界的步伐。也要关注Github上面一些算法工程项目，如推荐系统搭建，机器学习并行算法实现等。
