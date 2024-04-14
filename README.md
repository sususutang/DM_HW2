DM_HW2 互评作业二

学号：1120201241 姓名：赵羽菲 

仓库地址：https://github.com/sususutang/DM_HW2

本次实验选择SNAP中的引用网络Cit_HepTh数据集和DBLP数据集进行频繁模式和关联规则挖掘。

数据分析要求：

（1）数据获取与预处理；

（2）频繁模式挖掘：可以是项集、序列和图。

（3）模式命名：如论文-作者网络中合作模式、引用模式和发表模式等，不同的领域的频繁模式的含义也不尽相同，需自行确定模式的名称。

（4）对挖掘结果进行分析；

（5）可视化展示。

dblp_association.ipynb是DBLP数据集的挖掘过程报告，频繁模式为论文-作者合作模式，旨在挖掘经常一起合作的一组作者。

cit_hepth_association.ipynb是SNAP中的引用网络Cit_HepTh数据集的挖掘过程报告，频繁模式为引用模式，旨在挖掘经常一起被引用的一组论文。

Cit_HepTh数据集可以直接运行cit_hepth_association.ipynb，进行数据集处理和频繁模式与关联规则挖掘；

DBLP数据集需要先运行dblp_preprocess.py进行数据预处理获得dblp1.csv，再运行dblp_association.ipynb中数据处理和频繁模式与关联规则挖掘的部分。

另外，运行时需将数据集放置在与代码同一路径下。