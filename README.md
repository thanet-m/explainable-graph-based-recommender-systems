# Existing explainable graph-based recommender systems 


The following table presents existing explainable graph-based recommender systems, ordered by the proposed year.


| Model | Learning method | Explaining method | Explanation type | Implementation |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ----------------------------------------| 
| SemAuto [1] | Embedding-based | Model-specific | Node level | https://github.com/sisinflab/SEMAUTO |
| Ai et al.’s [2] | Embedding-based | Model-specific | Path level | - |
| RippleNet [3] | Hybrid |  Model-specific | Path level | https://github.com/hwwang55/RippleNet |
| SEP [4] | Path-based | Model-agnostic | Path level | - |
| KGAT [5] | Embedding-based | Model-specific | Path level | https://github.com/xiangwang1223/knowledge_graph_attention_network |
| PGPR [6] | Embedding-based | Model-specific | Path level | https://github.com/orcax/PGPR |
| LDSDMF [7] | Path-based | Model-specific | Node level | - |
| KPRN [8] | Path-based | Model-specific | Path level | https://github.com/xiangwang1223/KPRN |
| RuleRec [9] | Path-based | Model-agnostic | Meta-path level | https://github.com/THUIR/RuleRec |
| EIUM [10] | Hybrid | Model-agnostic | Path level | - |
| Liu et al.’s [11] | Embedding-based | Model-specific | Node level | - |
| HAGERec [12] | Embedding-based | Model-specific | Path level | - |
| MSRE [13] | Path-based | Model-specific | Node, path, and meta-path levels | - | 
| MP4Rec [14] | Path-based | Model-specific | Meta-path level and implicit | - |
| FairKG4Rec [15] | Path-based | Model-agnostic | Path level | - |
| PRINCE [16] | Path-based | Model-agnostic | Node level | https://github.com/azinmatin/prince |
| ADAC [17] | Hybrid | Model-specific | Path level | - |
| CAFE [18] | Hybrid | Model-specific | Path level | https://github.com/orcax/CAFE |
| GEAPR [19] | Hybrid | Model-specific | Node level | https://github.com/zyli93/GEAPR |
| KGIN [20] | Embedding-based | Model-specific | Node level | https://github.com/huangtinglin/Knowledge_Graph_based_Intent_Network |
| MKRLN [21] | Embedding-based | Model-specific | Path level | - |
| TMER [22] | Path-based | Model-specific | Path level | https://github.com/Abigale001/TMER | 
| UCPR [23] | Embedding-based | Model-specific | Path level | https://github.com/johnnyjana730/UCPR |
| LOGER [24] | Embedding-based | Model-specific | Path level | https://github.com/orcax/LOGER |
| KGAT+ [25] | Embedding-based | Model-specific | Path level | - |
| TPRec [26] | Embedding-based | Model-specific | Path level | https://github.com/Go0day/TPRec |
| ReMR [27] | Embedding-based | Model-specific | Path level | - |
| PLM-Rec [28] | Path-based | Model-specific | Path level | - | 
| METoNR [29] | Path-based | Model-specific | Meta-path level | https://github.com/T0UGH/METoNR | 
| KR-GCN [30] | Hybrid | Model-specific | Path level | - |



References 

[1] Vito Bellini, Angelo Schiavone, Tommaso Di Noia, Azzurra Ragone, and Eugenio Di Sciascio. 2018. Knowledge-Aware Autoencoders for Explainable Recommender Systems. In Proceedings of the 3rd Workshop on Deep Learning for Recommender Systems. Association for Computing Machinery, New York, NY, USA, 24–31. 

[2] Qingyao Ai, Vahid Azizi, Xu Chen, and Yongfeng Zhang. 2018. Learning Heterogeneous Knowledge Base Embeddings for Explainable Recommendation. Algorithms 11, 9 (2018), 137.

[3] Hongwei Wang, Fuzheng Zhang, Jialin Wang, Miao Zhao, Wenjie Li, Xing Xie, and Minyi Guo. 2018. RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems. In Proceedings of the 27th ACM International Conference on Information and Knowledge Management. 417–426.

[4] Fan Yang, Ninghao Liu, Suhang Wang, and Xia Hu. 2018. Towards Interpretation of Recommender Systems with Sorted Explanation Paths. Proceedings - IEEE International Conference on Data Mining, ICDM (2018).

[5] Xiang Wang, Xiangnan He, Yixin Cao, Meng Liu, and Tat-Seng Chua. 2019. KGAT: Knowledge Graph Attention Network for Recommendation. In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. 950–958.

[6] Yikun Xian, Zuohui Fu, S. Muthukrishnan, Gerard de Melo, and Yongfeng Zhang. 2019. Reinforcement Knowledge Graph Reasoning for Explainable Recommendation. In Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval. 285–294.

[7] Mohammed Alshammari, Olfa Nasraoui, and Scott Sanders. 2019. Mining Semantic Knowledge Graphs to Add Explainability to Black Box Recommender Systems. IEEE Access 7 (2019), 110563–110579.

[8] Xiang Wang, Dingxian Wang, Canran Xu, Xiangnan He, Yixin Cao, and Tat-Seng Chua. 2019. Explainable Reasoning over Knowledge Graphs for Recommendation. Proceedings of the AAAI Conference on Artificial Intelligence 33 (2019), 5329–5336.

[9] Weizhi Ma, Woojeong Jin, Min Zhang, Chenyang Wang, Yue Cao, Yiqun Liu, Shaoping Ma, and Xiang Ren. 2019. Jointly learning explainable rules for recommendation with knowledge graph. The Web Conference 2019 - Proceedings of the World Wide Web Conference, WWW 2019 (2019), 1210–1221.

[10] Xiaowen Huang, Quan Fang, Shengsheng Qian, Jitao Sang, Yan Li, and Changsheng Xu. 2019. Explainable InteractionDriven User Modeling over Knowledge Graph for Sequential Recommendation. In Proceedings of the 27th ACM International Conference on Multimedia. Association for Computing Machinery, New York, NY, USA.
[11] Ninghao Liu, Yong Ge, Li Li, Xia Hu, Rui Chen, and Soo-Hyun Choi. 2020. Explainable Recommender Systems via Resolving Learning Representations. In Proceedings of the 29th ACM International Conference on Information & Knowledge Management. Association for Computing Machinery
[12] Zuoxi Yang and Shoubin Dong. 2020. HAGERec: Hierarchical Attention Graph Convolutional Network Incorporating Knowledge Graph for Explainable Recommendation. Knowledge-Based Systems 204 (2020), 106194.
[13] Xin Wang, Ying Wang, and Yunzhi Ling. 2020. Attention-Guide Walk Model in Heterogeneous Information Network for Multi-Style Recommendation Explanation. Proceedings of the AAAI Conference on Artificial Intelligence 34, 04 (2020), 6275–6282.
[14] Makbule Gulcin Ozsoy, Diarmuid O’Reilly-Morgan, Panagiotis Symeonidis, Elias Z. Tragos, Neil Hurley, Barry Smyth, and Aonghus Lawlor. 2020. MP4Rec: Explainable and Accurate Top-N Recommendations in Heterogeneous Information Networks. IEEE Access (2020).
[15] Zuohui Fu, Yikun Xian, Ruoyuan Gao, Jieyu Zhao, Qiaoying Huang, Yingqiang Ge, Shuyuan Xu, Shijie Geng, Chirag Shah, Yongfeng Zhang, and Gerard de Melo. 2020. Fairness-Aware Explainable Recommendation over Knowledge Graphs. Association for Computing Machinery, New York, NY, USA, 69–78.
[16] Azin Ghazimatin, Oana Balalau, Rishiraj Saha Roy, and Gerhard Weikum. 2020. Prince: Provider-side interpretability with counterfactual explanations in recommender systems. WSDM 2020 - Proceedings of the 13th International Conference on Web Search and Data Mining (2020), 196–204.
[17] Kangzhi Zhao, Xiting Wang, Yuren Zhang, Li Zhao, Zheng Liu, Chunxiao Xing, and Xing Xie. 2020. Leveraging Demonstrations for Reinforcement Recommendation Reasoning over Knowledge Graphs. In Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (Virtual Event, China) (SIGIR ’20). Association for Computing Machinery, New York, NY, USA, 239–248.
[18] Yikun Xian, Zuohui Fu, Handong Zhao, Yingqiang Ge, Xu Chen, Qiaoying Huang, Shijie Geng, Zhou Qin, Gerard de Melo, S. Muthukrishnan, and Yongfeng Zhang. 2020. CAFE: Coarse-to-Fine Neural Symbolic Reasoning for Explainable Recommendation. In Proceedings of the 29th ACM International Conference on Information & Knowledge Management (Virtual Event, Ireland) (CIKM ’20). Association for Computing Machinery, New York, NY, USA, 1645–1654.
[19] Zeyu Li, Wei Cheng, Haiqi Xiao, Wenchao Yu, Haifeng Chen, and Wei Wang. 2021. You Are What and Where You Are: Graph Enhanced Attention Network for Explainable POI Recommendation. In Proceedings of the 30th ACM International Conference on Information & Knowledge Management. Association for Computing Machinery.
[20] Xiang Wang, Tinglin Huang, Dingxian Wang, Yancheng Yuan, Zhenguang Liu, Xiangnan He, and Tat-Seng Chua. 2021. Learning Intents behind Interactions with Knowledge Graph for Recommendation. In Proceedings of the Web Conference 2021. Association for Computing Machinery, New York, NY, USA.
[21] Shaohua Tao, Runhe Qiu, Yuan Ping, and Hui Ma. 2021. Multi-modal Knowledge-aware Reinforcement Learning Network for Explainable Recommendation. Knowledge-Based Systems 227 (2021), 107217.
[22] Hongxu Chen, Yicong Li, Xiangguo Sun, Guandong Xu, and Hongzhi Yin. 2021. Temporal Meta-path Guided Explainable Recommendation. Proceedings of the 14th ACM International Conference on Web Search and Data Mining (2021).
[23] Chang-You Tai, Liang-Ying Huang, Chien-Kun Huang, and Lun-Wei Ku. 2021. User-Centric Path Reasoning towards Explainable Recommendation. In Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval. Association for Computing Machinery, New York, NY, USA
[24] Yaxin Zhu, Yikun Xian, Zuohui Fu, Gerard de Melo, and Yongfeng Zhang. 2021. Faithfully Explainable Recommendation via Neural Logic Reasoning. In Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies.
[25] Ryotaro Shimizu, Megumi Matsutani, and Masayuki Goto. 2022. An explainable recommendation framework based on an improved knowledge graph attention network with massive volumes of side information. Knowledge-Based Systems 239 (2022), 107970.
[26] Yuyue Zhao, Xiang Wang, Jiawei Chen, Yashen Wang, Wei Tang, Xiangnan He, and Haiyong Xie. 2022. Time-Aware Path Reasoning on Knowledge Graph for Recommendation. ACM Transactions on Information Systems 41, 2 (2022).
[27] Xiting Wang, Kunpeng Liu, Dongjie Wang, Le Wu, Yanjie Fu, and Xing Xie. 2022. Multi-Level Recommendation Reasoning over Knowledge Graphs with Reinforcement Learning. In Proceedings of the ACM Web Conference 2022 (Virtual Event, Lyon, France) (WWW ’22). Association for Computing Machinery, New York, NY, USA, 2098–2108.
[28] Shijie Geng, Zuohui Fu, Juntao Tan, Yingqiang Ge, Gerard de Melo, and Yongfeng Zhang. 2022. Path Language Modeling over Knowledge Graphs for Explainable Recommendation. In Proceedings of the ACM Web Conference 2022 (Virtual Event, Lyon, France) (WWW ’22). Association for Computing Machinery, New York, NY, USA, 946–955.
[29] Mingwei Zhang, Guiping Wang, Lanlan Ren, Jianxin Li, Ke Deng, and Bin Zhang. 2022. METoNR: A Meta Explanation Triplet Oriented News Recommendation Model. Knowledge-Based Systems 238, C (feb 2022), 12 pages.
[30] Ting Ma, Longtao Huang, Qianqian Lu, and Songlin Hu. 2022. KR-GCN: Knowledge-Aware Reasoning with Graph Convolution Network for Explainable Recommendation. ACM Transactions on Information Systems (jan 2022).










