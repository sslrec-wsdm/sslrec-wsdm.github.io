![conf_logo](https://raw.githubusercontent.com/sslrec-wsdm/sslrec-wsdm.github.io/main/conf_logo.png)
![uq_logo](https://raw.githubusercontent.com/sslrec-wsdm/sslrec-wsdm.github.io/main/uq_logo2.jpg)
<br>
<br>

Welcome! This is the page of our tutorial "<b>Self-Supervised Learning in Recommendation: Foundations, Methods and Prospects</b>" at WSDM 2023.

(Last update: 03/10/2022)

### Time
TBA
<hr>

### Description

Recommender systems have become a necessity in this Internet era to offer personalization. However, in contrast to the increasing ease of model building and deployment, the lack of user behavioral data still remains a major pain point for modern recommender systems that constantly compromises recommendation performance. Recently, self-supervised learning (SSL), which can enable training on massive unlabeled data with automatic data annotation, has achieved tremendous success in many fields and been applied to an ever-expanding range of applications including recommendation. Many recent studies have demonstrated that all kinds of recommendation models can be significantly improved through learning with well-designed self-supervised tasks and data augmentations. In this tutorial, we will provide a panorama of the research efforts on self-supervised recommendation. Specifically, the content includes: (1) foundations and overview of self-supervised recommendation; (2) a comprehensive taxonomy of existing self-supervised recommendation methods; (3) how to apply SSL to various recommendation scenarios; (4) limitations in current research and future research directions. Additionally, we release an open-source toolkit to facilitate empirical comparisons and methodological development of self-supervised recommendation methods (released at https://github.com/Coder-Yu/SELFRec). 

<hr>

### Presenters
<table style="border: none;">
<tr style="border: none;">
<td align="center">
<img class="circlepic" src="https://raw.githubusercontent.com/ssl-recsys/ssl-recsys.github.io/main/junliang.jpg" />
</td>
<td align="center">
<img class="circlepic" src="https://raw.githubusercontent.com/ssl-recsys/ssl-recsys.github.io/main/tongchen.jpg" />
</td>
<td align="center">
<img class="circlepic" src="https://raw.githubusercontent.com/ssl-recsys/ssl-recsys.github.io/main/hongzhi.jpg" />
</td>
</tr>
<tr  style="border: none;">
<td align="center">
<b><a href="https://coder-yu.github.io/" style="color:#155799;">Junliang Yu</a></b>
</td>
<td align="center">
<b><a href="https://itee.uq.edu.au/profile/1253/rocky-chen" style="color:#155799;">Tong Chen</a></b>
</td>
<td align="center">
<b><a href="https://sites.google.com/view/hongzhi-yin/home" style="color:#155799;">Hongzhi Yin</a></b>
</td>
</tr>
</table>


#### Bio

<b>Junliang Yu</b> is a final-year Ph.D. student with the School of Information Technology and Electrical Engineering at the University of Queensland, jointly advised by A/Prof. Hongzhi Yin and Prof. Zi (Helen) Huang. He received his Bachelor and Master degrees from Chongqing University. His research interests include recommender systems, social media analytics, deep learning on graphs, and self-supervised learning. His recent research mainly focuses on efficient and explainable self-supervised learning for recommendation. He has 10+ publications on top-tier international venues such as KDD, WWW, ICDM, CIKM, AAAI, SIGIR, VLDBJ, and TKDE. He also served as the conference PC member of AAAI, CIKM, IJCAI, etc, and the journal reviewer for TOIS, TIST, TNNLS, TKDE, etc. He has rich lecture experience and tutored one relevant course of social media analytics, and also has made oral presentations on multiple top-tier conferences.  

<b>Dr. Tong Chen</b> is a Lecturer with the Data Science Discipline at The University of Queensland and a recipient of the ARC Discovery Early Career Reseracher Award. He received his PhD degree in Computer Science from The University of Queensland in 2020. Dr. Chen's research interests include data mining, machine learning, business intelligence, recommender systems, and predictive analytics. He has 60+ publications on top-tier international venues such as KDD, SIGIR, ICDE, AAAI, IJCAI, ICDM, WWW, TKDE, IJCAI, TOIS, CIKM, as well as the prestigious health informatics journal JBHI. He has been actively providing professional services to over 20 world-leading international conferences/journals in the fields of data mining, information retrieval and AI. For example, his roles include program committee member of WSDM, CIKM, SIGIR, KDD, ICDM and reviewer for TKDE, TOIS, TKDD and TNNLS. Dr. Chen’s recent research has been focused on trustworthy and lightweight graph mining and recommendation algorithms to embrace the era of edge computing and AIoT. Dr. Chen has ample track records in lecturing, witnessed by his course design and delivery experience in business analytics, full-course teaching experience in social media analytics and database systems, as well as invited talks on cutting-edge recommender systems at the WWW'22 Tutorial, ICDM’20 NeuRec Workshop, Beihang University, and Zhejiang University. He was one of the 17 nominees for the Most Effective Teacher in the Faculty of EAIT, The University of Queensland in 2022.

<b>Dr. Hongzhi Yin</b> works as ARC Future Fellow and associate professor with The University of Queensland, Australia. He was recognized as Field Leader of Data Mining & Analysis in The Australian's Research 2020 magazine, the recipient of the 2022 AI 2000 Most Influential Scholar Honorable Mention in Data Mining (10 Years Impact), and featured among the World's Top 2% Scientists List published by Stanford University (Single Year Impact) and AD Scientific Index 2022 (5 Years Impact). He received his doctoral degree from Peking University in July 2014, and his Ph.D. Thesis won the highly competitive Distinguished Doctor Degree Thesis Award of Peking University. His current main research interests include recommender systems, graph embedding and mining, chatbots, social media analytics and mining, edge machine learning, trustworthy machine learning, decentralized and federated learning, and smart healthcare. He has published 220+ papers with H-index 52, including 22 most highly cited publications in Top 1\% (CNCI), 120 CCF A and 70+ CCF B, 120 CORE A* and 70+ CORE A, such as KDD, SIGIR, WWW, WSDM, SIGMOD, VLDB, ICDE, AAAI, IJCAI, ACM Multimedia, ECCV, IEEE TKDE and TNNL, VLDB Journal and ACM TOIS. He has won 6 Best Paper Awards such as Best Paper Award at ICDE 2019, Best Student Paper Award at DASFAA 2020, ACM Computing Reviews' 21 Annual Best of Computing Notable Books and Articles, and Best Paper Award Nomination at ICDM 2018. Dr. Yin has rich lecture experience and taught 5 relevant courses such as information retrieval and web search, data mining, social media analytics, and responsible data science. He was nominated as Most Effective Teacher of EAIT Faculty in The University of Queensland for 2020, 2021 and 2022. He has delivered 12 keynotes, invited talks and tutorials at the top international conferences such as tutorials at WWW 2017, KDD 2017 and Web Conference 2022.

<hr>

### Covered Topics

In this tutorial, we will provide a panorama of self-supervised recommendation. Specifically, the topics to be covered include:

- **Foundations and overview of self-supervised recommendation**. We will give an exclusive definition and formulation of self-supervised recommendation, display the development of this line of research, and discuss its connections to related topics like pre-training and contrastive learning. 
- **Taxonomy of self-supervised recommendation**. We will introduce a comprehensive taxonomy of self-supervised recommendation, which is based on the distinct characteristics of different self-supervised tasks. Particularly, the taxonomy divides existing self-supervised methods into four categories: contrastive, generative, predictive, and hybrid. For each category, we discuss its overall idea, representative methods, and pros and cons. 
- **Applications of SSL in different recommendation scenarios**. We will share our experience of applying SSL to multiple recommendation scenarios including social recommendation, session-based recommendation, on-device recommendation and general graph recommendation to participants. Specifically, we will dive into the principle of SSL and demystify why SSL can improve recommendation performance.
- **Limitations and future research directions of self-supervised recommendation**. Current research efforts mainly focus on using SSL to improve recommendation accuracy. We will analyze the limitations of current research and identify some promising research directions which are worth exploring. 
- **Benchmarking self-supervised recommendation**. We will release a library [SELFRec](https://github.com/Coder-Yu/SELFRec) to benchmark self-supervised recommendation. It contains many representative methods and provides user-friendly interfaces for fast development of self-supervised recommendation models. The empirical comparison of different methods can be easily conducted with it under a fair experimental setting.

<hr>

### Outline

This is a 3-hour lecture-style tutorial that includes:
- <b>I. Introduction (20 mins)</b>  
  - Overview of Recommendation
  - Development of self-supervised recommendation  
- <b>II. Definition and Taxonomy of self-supervised recommendation(20 mins)</b>  
  - Definition and formulation
  - Connections to related concepts and topics
  - Taxonomy and common paradigms
- <b>III. Representative Methods (30 mins)</b> 
  - Contrastive Methods
  - Predictive Methods
  - Generative Methods
  - Hybrid Methods  
- <b>IV. Apply SSL to Different Scenarios (60 mins)</b> 
   - SSL on social recommendation
   - SSL on session-based recommendation
   - Multi-view self-supervised recommendation 
   - Efficient self-supervised recommendation 
- <b>V. Limitations and Future Research Trends (20 mins)</b> 
- <b>VI. Open-source Toolkit for Self-Supervised Recommendation (15 mins)</b> 
- <b>VII. Conclusions and Discussions (15 mins)</b>
<hr>

### Targeted Audience

The tutorial targets a broad range of audiences from recommendation to other related areas. Graduate students, practitioners, and academic and industrial researchers all can benefit from this tutorial. As for the prerequisite, basic knowledge of information retrieval and recommendation is preferred. The tutorial will also introduce the foundation for better audience engagement. After the tutorial, we expect the audience can: 1) grasp the basic concepts and taxonomy of self-supervised recommendation; 2) get a bird's-eye view of this realm to avoid getting lost in a bewildering array of self-supervised recommendation approaches; 3) keep up with the latest progress of self-supervised recommendation; and 4) know to apply SSL to common recommendation scenarios.  We also aim to provide participants with an insightful discussion of the imitations in current research and future research directions.

<hr>

### Our papers on self-supervised recommendation

+ [Self-Supervised Learning for Recommender Systems: A Survey](https://arxiv.org/abs/2203.15876).  <i><b>Submitted to TKDE</b></i> [[code]](https://github.com/Coder-Yu/SELFRec) <br>
Junliang Yu, Hongzhi Yin, Xin Xia, Tong Chen, Jundong Li, Zi Huang
+ [Are Graph Augmentations Necessary? Simple Graph Contrastive Learning for Recommendation](https://arxiv.org/abs/2112.08679).  <i><b>SIGIR'22</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/SimGCL.py) <br>
Junliang Yu, Hongzhi Yin, Xin Xia, Tong Chen, Lizhen Cui, Quoc Viet Hung Nguyen
+ [	On-Device Next-Item Recommendation with Self-Supervised Knowledge Distillation](https://arxiv.org/abs/2204.11091).  <i><b>SIGIR'22</b></i> [[code]]() <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Qinyong Wang, Guandong Xu, Quoc Viet Hung Nguyen
+ [Self-Supervised Graph Co-Training for Session-based Recommendation](https://dl.acm.org/doi/abs/10.1145/3459637.3482388).  <i><b>CIKM'21</b></i> [[code]](https://github.com/xiaxin1998/COTREC) <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Yingxia Shao, Lizhen Cui
+ [Double-Scale Self-Supervised Hypergraph Learning for Group Recommendation](https://dl.acm.org/doi/10.1145/3459637.3482426).  <i><b>CIKM'21</b></i> [[code]](https://github.com/0411tony/HHGR) <br>
Junwei Zhang, Min Gao, Junliang Yu, Lei Guo, Jundong Li, Hongzhi Yin
+ [Socially-Aware Self-Supervised Tri-Training for Recommendation](https://dl.acm.org/doi/10.1145/3447548.3467340).  <i><b>KDD'21</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/SEPT.py) <br>
Junliang Yu, Hongzhi Yin, Min Gao, Xin Xia, Xiangliang Zhang, Nguyen Quoc Viet Hung
+ [Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation](https://dl.acm.org/doi/abs/10.1145/3442381.3449844).  <i><b>WWW'21</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/MHCN.py) <br>
Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang
+ [Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/16578).  <i><b>AAAI'21</b></i> [[code]](https://github.com/xiaxin1998/DHCN) <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Qinyong Wang, Lizhen Cui, Xiangliang Zhang
