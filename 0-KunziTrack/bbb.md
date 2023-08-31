# Recommender system 思路

## RS检索

RS太广了，检索后大致分为：

* 结合了xx问题提出了xxRS+application+evaluation
* new findings surrounding RS, always related to people feelings or actions. (the titles always are declarative sentences)  eg: Artificial intelligence in communication impacts language and social relationships. 
* RS is just background, the core issue is 协同过滤方法/dataset/...
* principles of RS.  To be more specific, the usage of RS leads to some problems (largely) related the technology, (then talk about the problems) or to make the usage perfect, some issues should be considered, and researchers solve them.  **(my focus)**

## Filter bubble / Information cocoon & RS 检索

* Definition: provide a mathematically explicit definition Strategy *Hou, 2022*

* Strategy:

* | Method             | Dataset        | Cite        |
  | ------------------ | -------------- | :---------- |
  | 协同过滤算法(ICF)  | video-iqiyi    | *Hou, 2022* |
  | 强化学习；因果推理 | video-kuaishou | *Gao, 2023* |
  |                    |                |             |
  |                    |                |             |

* affection
* 

## Narrow down

several options:

1. 爬虫下来针对于xx事件的看法（比如？山东地震？洪水？），语义分析。但是不是英文？和Bubbles没啥关系？
2. 推荐系统strategies 综述，但是技术上的看不懂且文献少，且自己高度不够怎么归纳，且不适合在文科论文里？
3. 选一个strategy复现（已完成），但是有啥意义？研究目的是什么？

brainstorming

1. reveal the affection of Bubbles. visualization. If no bubbles, the curve, to contrast 
2. 

一张美貌的图！*Santos, 2021*

![](https://raw.githubusercontent.com/kunzi051/BlogImage/main/HexoUsed/20230816020628.png)

## Discussion

首先，我一开始以为过滤气泡是推荐系统导致的，这是推荐系统的优势，因为可以convince或者引导人的思想和行为 persuade...

直到看了*Gao, 2023*，我意识到，算法的操控者是不想用户陷入到过滤气泡里的，会使得满意度降低，他们想要decrease/burst。所以采用了xxx methods，并将使用methods前后的效果做对比

但是我拿不到methods前（没有使用eg, RL）之前算法的用户数据。（之后的也没有ww）

就算是复现了 出了几张对比图有什么用呢 那是在评估人家的算法而已





References

Hou, L., Pan, X., Liu, K., Yang, Z., Liu, J., & Zhou, T. (2022). Information cocoons in online navigation. *iScience*, *26*(1), 105893. https://doi.org/10.1016/j.isci.2022.105893

Gao, C., Wang, S., Li, S., Chen, J., He, X., Lei, W., Li, B., Zhang, Y., & Jiang, P. (2023). *CIRS: Bursting Filter Bubbles by Counterfactual Interactive Recommender System* (arXiv:2204.01266). arXiv. https://doi.org/10.48550/arXiv.2204.01266

Santos, F. P., Lelkes, Y., & Levin, S. A. (2021). Link recommendation algorithms and dynamics of polarization in online social networks. *Proceedings of the National Academy of Sciences of the United States of America*, *118*(50), e2102141118. https://doi.org/10.1073/pnas.2102141118

