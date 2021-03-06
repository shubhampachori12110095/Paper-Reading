﻿# Paper-Reading
Paper reading in natural language processing.

- [Deep Learning in NLP](#deep-learning-in-nlp)
- [Dialogue System](#dialogue-system)
- [Text Summarization](#text-summarization)
- [Topic Modeling](#topic-modeling)

***

## Deep Learning in NLP
* **Attention**: Ashish Vaswani, Noam Shazeer, Niki Parmar, et al. "Attention is All you Need". NIPS(2017) [[PDF]](./papers/deep-learning/7181-attention-is-all-you-need.pdf) 
* **Seq2Seq**: Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio. "Neural Machine Translation by Jointly Learning to Align and Translate". ICLR(2015) [[PDF]](./papers/deep-learning/1409.0473-nmt-align.pdf) 
* **Memory Network**: Sainbayar Sukhbaatar, Arthur Szlam, Jason Weston, Rob Fergus. "End-To-End Memory Networks". NIPS(2015) [[PDF]](./papers/deep-learning/5846-end-to-end-memory-networks.pdf)
* **Pointer Network**: Oriol Vinyals, Meire Fortunato, Navdeep Jaitly. "Pointer Networks". NIPS(2015) [[PDF]](./papers/deep-learning/5866-pointer-networks.pdf) 
* **Copying Mechanism**: Jiatao Gu, Zhengdong Lu, Hang Li, Victor O.K. Li. "Incorporating Copying Mechanism in Sequence-to-Sequence Learning". ACL(2016) [[PDF]](./papers/deep-learning/P16-1154.pdf) 
* **GAN**: Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, et al. "Generative Adversarial Nets". NIPS(2014) [[PDF]](./papers/deep-learning/5423-generative-adversarial-nets.pdf)
* **Graph2Seq**: Kun Xu, Lingfei Wu, Zhiguo Wang, et al. "Graph2Seq: Graph to Sequence Learning with Attention-based Neural Networks". arXiv(2018) [[PDF]](./papers/deep-learning/1804.00823-graph2seq.pdf)


## Dialogue System
* **MMI**: Jiwei Li, Michel Galley, Chris Brockett, et al. "A Diversity-Promoting Objective Function for Neural Conversation Models". NAACL-HLT(2016)  [[PDF]](./papers/dialogue-system/N16-1014.pdf) [[code]](https://github.com/jiweil/Neural-Dialogue-Generation) :star::star::star::star:
* **TA-Seq2Seq**: Chen Xing, Wei Wu, Yu Wu, et al. "Topic Aware Neural Response Generation". AAAI(2017) [[PDF]](./papers/dialogue-system/AAAI17_TA-Seq2Seq.pdf) [[code]](https://github.com/LynetteXing1991/TA-Seq2Seq) :star::star::star::star:
* **MA**: Ganbin Zhou, Ping Luo, Rongyu Cao, et al. "Mechanism-Aware Neural Machine for Dialogue Response Generation". AAAI(2017) [[PDF]](./papers/dialogue-system/14471-66751-1-PB.pdf) :star::star::star::star:
* **HRED**: Iulian Vlad Serban, Alessandro Sordoni, Yoshua Bengio, et al. "Building End-To-End Dialogue Systems Using Generative Hierarchical Neural Network Models". AAAI(2016) [[PDF]](./papers/dialogue-system/11957-56353-1-PB.pdf) [[code]](https://github.com/julianser/hed-dlg) :star::star::star::star:
* **VHRED**: Iulian Vlad Serban, Alessandro Sordoni, Ryan Lowe, et al. "A Hierarchical Latent Variable Encoder-Decoder Model for Generating Dialogues". AAAI(2017) [[PDF]](./papers/dialogue-system/14567-66703-1-PB.pdf) [[code]](https://github.com/julianser/hed-dlg-truncated) :star::star::star::star::star:
* **CVAE/KgCVAE**: Tiancheng Zhao, Ran Zhao, Maxine Eskénazi. "Learning Discourse-level Diversity for Neural Dialog Models using Conditional Variational Autoencoders". ACL(2017) [[PDF]](./papers/dialogue-system/P17-1061.pdf) [[code]](https://github.com/snakeztc/NeuralDialog-CVAE) :star::star::star::star::star:
* **ERM**: Ganbin Zhou, Ping Luo, Yijun Xiao, et al. "Elastic Responding Machine for Dialog Generation with Dynamically Mechanism Selecting". AAAI(2018) [[PDF]](./papers/dialogue-system/16316-76896-1-PB.pdf) :star::star::star::star:
* **Tri-LSTM**: Tom Young, Erik Cambria, Iti Chaturvedi, et al. "Augmenting End-to-End Dialogue Systems With Commonsense Knowledge". AAAI(2018) [[PDF]](./papers/dialogue-system/16573-76790-1-PB.pdf) :star::star::star:
* **CCM**: Hao Zhou, Tom Young, Minlie Huang, et al. "Commonsense Knowledge Aware Conversation Generation with Graph Attention". IJCAI(2018) [[PDF]](./papers/dialogue-system/IJCAI-0643.pdf) [[code]](https://github.com/tuxchow/ccm) :star::star::star::star::star:
* **PCCM**: Qiao Qian, Minlie Huang, et al. "Assigning Personality/Profile to a Chatting Machine for Coherent Conversation Generation". IJCAI(2018) [[PDF]](./papers/dialogue-system/IJCAI-0595.pdf) [[code]](https://github.com/qianqiao/AssignPersonality) :star::star::star::star::star:
* **ECM**: Hao Zhou, Minlie Huang, et al. "Emotional Chatting Machine: Emotional Conversation Generation with Internal and External Memory". AAAI(2018) [[PDF]](./papers/dialogue-system/16455-76513-1-PB.pdf) [[code]](https://github.com/tuxchow/ecm) :star::star::star::star::star:
* **Topic-Seg-Label**: Ryuichi Takanobu, Minlie Huang, Zhongzhou Zhao, et al. "A Weakly Supervised Method for Topic Segmentation and Labeling in Goal-oriented Dialogues via Reinforcement Learning". IJCAI(2018) [[PDF]](./papers/dialogue-system/IJCAI-0612.pdf) [[code]](https://github.com/truthless11/Topic-Seg-Label) :star::star::star::star:
* **AliMe**: Minghui Qiu, Feng-Lin Li, Siyu Wang, et al. "AliMe Chat: A Sequence to Sequence and Rerank based Chatbot Engine". ACL(2017) [[PDF]](./papers/dialogue-system/P17-2079.pdf) :star::star::star:
* **Retrieval+biseq2seq**: Yiping Song, Rui Yan, Xiang Li, et al.
 "Two are Better than One: An Ensemble of Retrieval- and Generation-Based Dialog Systems". arXiv(2016) [[PDF]](./papers/dialogue-system/1610.07149.pdf) :star::star::star:
* **Retrieval+multi-seq2seq**: Yiping Song, Cheng-Te Li, Jian-Yun Nie, et al. "An Ensemble of Retrieval-Based and Generation-Based Human-Computer Conversation Systems". IJCAI(2018) [[PDF]](./papers/dialogue-system/IJCAI-0609.pdf) :star::star::star::star:
* **EED**: Danish Contractor, Vineet Kumar, Sachindra Joshi, Gaurav Pandey. "Exemplar Encoder-Decoder for Neural Conversation Generation". ACL(2018) [[PDF]](./papers/dialogue-system/P18-1123.pdf) :star::star::star:
* **SMN**: Yu Wu, Wei Wu, Chen Xing, Ming Zhou, Zhoujun Li. "Sequential Matching Network: A New Architecture for Multi-turn Response Selection in Retrieval-Based Chatbots". ACL(2017) [[PDF]](./papers/dialogue-system/P17-1046.pdf)  [[code]](https://github.com/MarkWuNLP/MultiTurnResponseSelection) :star::star::star::star::star:
* **Edit-N-Rerank**: Yu Wu, Furu Wei, Shaohan Huang, Zhoujun Li, Ming Zhou. "Response Generation by Context-aware Prototype Editing". arXiv(2018) [[PDF]](./papers/dialogue-system/1806.07042.pdf) :star::star::star::star::star:
* **STD/HTD**: Yansen Wang, Chenyi Liu, Minlie Huang, Liqiang Nie. "Learning to Ask Questions in Open-domain Conversational Systems with Typed Decoders". ACL(2018) [[PDF]](./papers/dialogue-system/P18-1204.pdf) [[code]](https://github.com/victorywys/Learning2Ask_TypedDecoder) :star::star::star::star::star:
* **CSF used**: Pei Ke, Jian Guan, Minlie Huang, Xiaoyan Zhu. "Generating Informative Responses with Controlled Sentence Function". ACL(2018) [[PDF]](./papers/dialogue-system/P18-1139.pdf) [[code]](https://github.com/kepei1106/SentenceFunction) :star::star::star::star::star:
* **DAWnet**: Wenjie Wang, Minlie Huang, Xin-Shun Xu, Fumin Shen, Liqiang Nie. "Chat More: Deepening and Widening the Chatting Topic via A Deep Model". SIGIR(2018) [[PDF]](./papers/dialogue-system/p255-wang.pdf) [[code]](https://sigirdawnet.wixsite.com/dawnet) :star::star::star::star::star:
* **ZSDG**: Tiancheng Zhao, Maxine Eskenazi. "Zero-Shot Dialog Generation with Cross-Domain Latent Actions". SIGDIAL(2018) [[PDF]](./papers/dialogue-system/W18-5001.pdf) [[code]](https://github.com/snakeztc/NeuralDialog-ZSDG) :star::star::star::star::star:
* **DUA**: Zhuosheng Zhang, Jiangtong Li, Pengfei Zhu, et al. "Modeling Multi-turn Conversation with Deep Utterance Aggregation". COLING(2018) [[PDF]](./papers/dialogue-system/C18-1317.pdf) [[code]](https://github.com/cooelf/DeepUtteranceAggregation) :star::star::star::star::star:
* **DC-MMI**: Ashutosh Baheti, Alan Ritter, Jiwei Li, et al. "Generating More Interesting Responses in Neural Conversation Models with Distributional Constraints". EMNLP(2018) [[PDF]](./papers/dialogue-system/1809.01215.pdf) [[code]](https://github.com/abaheti95/DC-NeuralConversation) :star::star::star::star::star:
* **Mem2Seq**: Andrea Madotto, Chien-Sheng Wu, Pascale Fung. "Mem2Seq: Effectively Incorporating Knowledge Bases into End-to-End Task-Oriented Dialog Systems". ACL(2018) [[PDF]](./papers/dialogue-system/P18-1136.pdf) [[code]](https://github.com/HLTCHKUST/Mem2Seq) :star::star::star::star::star:


## Text Summarization
* **ABS/ABS+**: Alexander M. Rush, Sumit Chopra, Jason Weston. "A Neural Attention Model for Abstractive Sentence Summarization". EMNLP (2015) [[PDF]](./papers/text-summarization/D15-1044.pdf) :star::star::star::star::star:
* **RAS-Elman/RAS-LSTM**: Sumit Chopra, Michael Auli, Alexander M. Rush. "Abstractive Sentence Summarization with Attentive Recurrent Neural Networks. HLT-NAACL (2016) [[PDF]](./papers/text-summarization/N16-1012.pdf) [[code]](https://github.com/facebookarchive/NAMAS)  :star::star::star::star:
* **words-lvt2k-1sent**: Ramesh Nallapati, Bowen Zhou, et al. "Abstractive Text Summarization using Sequence-to-sequence RNNs and Beyond". CoNLL (2016) [[PDF]](./papers/text-summarization/K16-1028.pdf) :star::star::star::star:
* **PGN**: Abigail See, Peter J. Liu, Christopher D. Manning. "Get To The Point: Summarization with Pointer-Generator Networks". ACL (2017) [[PDF]](./papers/text-summarization/P17-1099.pdf) [[code]](https://github.com/abisee/pointer-generator) :star::star::star::star::star:
* **GAN for TextSum**: Linqing Liu, Yao Lu, Min Yang, Qiang Qu, Jia Zhu, Hongyan Li. "Generative Adversarial Network for Abstractive Text Summarization". AAAI (2018) [[PDF]](./papers/text-summarization/16238-77257-1-PB.pdf) :star::star::star:
* **Reinforced-Topic-ConvS2S**: Li Wang, Junlin Yao, Yunzhe Tao, et al. "A reinforced topic-aware convolutional sequence-to-sequence model for abstractive text summarization." IJCAI (2018) [[PDF]](./papers/text-summarization/0619.pdf) :star::star::star::star::star:
* **FTSum**: Ziqiang Cao, Furu Wei, Wenjie Li, Sujian Li. "Faithful to the Original: Fact Aware Neural Abstractive Summarization". arXiv(2017) [[PDF]](./papers/text-summarization/1711.04434.pdf) :star::star::star::star:
* **Re^3Sum**: Ziqiang Cao, Wenjie Li, Furu Wei, Sujian Li. "Retrieve, Rerank and Rewrite: Soft Template Based Neural Summarization". ACL(2018) [[PDF]](./papers/text-summarization/P18-1015.pdf) [[code]](http://www4.comp.polyu.edu.hk/~cszqcao/data/IRSum_Resource.zip) :star::star::star::star::star:
* **NeuSum**: Qingyu Zhou, Nan Yang, Furu Wei, et al. "Neural Document Summarization by Jointly Learning to Score and Select Sentences". ACL(2018) [[PDF]](./papers/text-summarization/P18-1061.pdf) :star::star::star::star::star:
* **rnn-ext+abs+RL+rerank**: Yen-Chun Chen, Mohit Bansal. "Fast Abstractive Summarization with Reinforce-Selected Sentence Rewriting". ACL(2018) [[PDF]](./papers/text-summarization/P18-1063.pdf) [[code]](https://github.com/ChenRocks/fast_abs_rl) :star::star::star::star::star:
* **Seq2Seq+CGU**: Junyang Lin, Xu Sun, Shuming Ma, Qi Su. "Global Encoding for Abstractive Summarization". ACL(2018) [[PDF]](./papers/text-summarization/P18-2027.pdf) [[code]](https://github.com/lancopku/Global-Encoding) :star::star::star::star:


## Topic Modeling
* **LDA**: David M. Blei, Andrew Y. Ng, Michael I. Jordan. "Latent Dirichlet Allocation". JMLR (2003) [[PDF]](./papers/topic-modeling/JMLR03_LDA_BleiNgJordan.pdf) [[code]](https://github.com/blei-lab/lda-c) :star::star::star::star::star:
* **DTM**: David M. Blei, John D. Lafferty. "Dynamic Topic Models". ICML (2006) [[PDF]](./papers/topic-modeling/ICML06_DTM.pdf) [[code]](https://github.com/blei-lab/dtm) :star::star::star:
* **cDTM**: Chong Wang, David Blei, David Heckerman. "Continuous Time Dynamic Topic Models". arXiv (2012) [[PDF]](./papers/topic-modeling/arXiv12_cDTM.pdf) :star::star:
* **NTM**: Ziqiang Cao, Sujian Li, Yang Liu, Wenjie Li, Heng Ji. "A Novel Neural Topic Model and Its Supervised Extension". AAAI (2015) [[PDF]](./papers/topic-modeling/AAAI15_NTM.pdf) :star::star::star::star:
* **TWE**: Yang Liu, Zhiyuan Liu, Tat-Seng Chua, Maosong Sun. "Topical Word Embeddings". AAAI (2015) [[PDF]](./papers/topic-modeling/AAAI15_TWE.pdf) :star::star::star::star:
* **RATM-D**: Shuangyin Li, Yu Zhang, Rong Pan, Mingzhi Mao, Yang Yang. Recurrent Attentional Topic Model. AAAI (2017)[[PDF]](./papers/topic-modeling/AAAI17_RATM-D.pdf) :star::star::star::star:
* **RIBS-TM**: Heng-Yang Lu, Lu-Yao Xie, Ning Kang, et al. "Don't Forget the Quantifiable Relationship between Words: Using Recurrent Neural Network for Short Text Topic Discovery". AAAI (2017) [[PDF]](./papers/topic-modeling/AAAI17_RIBS_TM.pdf) :star::star::star::star:
* **Topic coherence**: David M. Mimno, Hanna M. Wallach, Edmund M. Talley, Miriam Leenders, Andrew McCallum. "Optimizing Semantic Coherence in Topic Models". EMNLP (2011) [[PDF]](./papers/topic-modeling/EMNLP11_Topic_Coherence.pdf) :star::star::star:
* **Topic coherence**: David Newman, Jey Han Lau, Karl Grieser, Timothy Baldwin. "Automatic Evaluation of Topic Coherence". HLT-NAACL (2010) [[PDF]](./papers/topic-modeling/Automatic_Evaluation_of_Topic_Coherence.pdf) :star::star::star:
* **Gaussian-LDA**:	Rajarshi Das, Manzil Zaheer, Chris Dyer. "Gaussian LDA for Topic Models with Word Embeddings". ACL (2015) [[PDF]](./papers/topic-modeling/ACL15_Gaussian_LDA.pdf) [[code]](https://github.com/rajarshd/Gaussian_LDA) :star::star::star::star::star:
* **LFTM**:	Dat Quoc Nguyen, Richard Billingsley, Lan Du, Mark Johnson. "Improving Topic Models with Latent Feature Word Representations". TACL (2015) [[PDF]](./papers/topic-modeling/TACL15_LFTM.pdf) [[code]](https://github.com/datquocnguyen/LFTM) :star::star::star::star::star:
* **TopicVec**:	Shaohua Li, Tat-Seng Chua, Jun Zhu, Chunyan Miao. "Generative Topic Embedding: a Continuous Representation of Documents". ACL (2016) [[PDF]](./papers/topic-modeling/ACL16_TopicVec.pdf) [[code]](https://github.com/askerlee/topicvec) :star::star::star::star::star:
* **SLRTM**: Fei Tian, Bin Gao, Di He, Tie-Yan Liu. "Sentence Level Recurrent Topic Model: Letting Topics Speak for Themselves". arXiv (2016) [[PDF]](./papers/topic-modeling/arXiv16_SLRTM.pdf) :star::star::star::star:
* **NMF boosted**: Mark Belford, Brian Mac Namee, Derek Greene. "Stability of topic modeling via matrix factorization". Expert Syst. Appl. (2018) [[PDF]](./papers/topic-modeling/ESA18_Stability_of_topic_modeling_via_matrix_factorization.pdf) :star::star::star:
* **Evaluation of Topic Models**: David Newman, Sarvnaz Karimi, Lawrence Cavedon. "External Evaluation of Topic Models". Australasian Doc. Comp. Symp. (2009) [[PDF]](./papers/topic-modeling/External_Evaluation_of_Topic_Models.pdf) :star::star:
* **Topic2Vec**: Liqiang Niu, Xinyu Dai, Jianbing Zhang, Jiajun Chen. "Topic2Vec: Learning distributed representations of topics". IALP (2015) [[PDF]](./papers/topic-modeling/IALP15_Topic2Vec.pdf) :star::star::star:
* **Short text + Word embedding**: Guangxu Xun, Vishrawas Gopalakrishnan, Fenglong Ma, et al. Topic Discovery for Short Texts Using Word Embeddings. ICDM (2016) [[PDF]](./papers/topic-modeling/ICDE16_Topic_Discovery_for_Short_Texts_Using_Word_Embeddings.pdf) :star::star::star:
* **L-EnsNMF**: Sangho Suh, Jaegul Choo, Joonseok Lee, Chandan K. Reddy. "L-EnsNMF: Boosted Local Topic Discovery via Ensemble of Nonnegative Matrix Factorization". ICDM (2016) [[PDF]](./papers/topic-modeling/ICDM16_L-EnsNMF.pdf) [[code]](https://github.com/sanghosuh/lens_nmf-matlab) :star::star::star::star::star:
* **HTTM**:	Jipeng Qiang, Ping Chen, Wei Ding, et al. "Topic Discovery from Heterogeneous Texts". ICTAI (2016) [[PDF]](./papers/topic-modeling/ICTAI16_HTTM.pdf) [[code]](https://github.com/qiang2100/HTTM) :star::star:
* **DC-NMF**: Rundong Du, Da Kuang, Barry L. Drake, Haesun Park. "DC-NMF: nonnegative matrix factorization based on divide-and-conquer for fast clustering and topic modeling". J. Global Optimization (2017) [[PDF]](./papers/topic-modeling/JGO17_DC_NMF.pdf) :star::star::star::star:
* **cFTM**:	Xu Chen, Mingyuan Zhou, Lawrence Carin. "The contextual focused topic model". KDD (2012) [[PDF]](./papers/topic-modeling/KDD12_cFTM.pdf) :star::star::star::star::star:
* **CLM**: Guangxu Xun, Yaliang Li, Jing Gao, Aidong Zhang. "Collaboratively Improving Topic Discovery and Word Embeddings by Coordinating Global and Local Contexts". KDD (2017) [[PDF]](./papers/topic-modeling/KDD17_CLM.pdf) [[code]](https://github.com/XunGuangxu/2in1) :star::star::star::star::star:
* **GMTM**:	Vivek Kumar Rangarajan Sridhar. "Unsupervised Topic Modeling for Short Texts Using Distributed Representations of Words". HLT-NAACL (2015) [[PDF]](./papers/topic-modeling/NAACL15_GMTM.pdf) :star::star::star::star:
* **Parameter Estimation**: Gregor, Heinrich. "Parameter estimation for text analysis." Technical report (2005). [[PDF]](./papers/topic-modeling/Parameter_estimation_for_text_analysis.pdf) :star::star::star::star::star:
* **GPU-PDMM**:	Chenliang Li, Yu Duan, Haoran Wang, et al. "Enhancing Topic Modeling for Short Texts with Auxiliary Word Embeddings". TOIS (2017) [[PDF]](./papers/topic-modeling/TOIS17_GPU-PDMM.pdf) :star::star::star::star:
* **BPT**: Zhen Guo, Zhongfei (Mark) Zhang, Shenghuo Zhu, et al. "A Two-Level Topic Model Towards Knowledge Discovery from Citation Networks". TKDE (2014) [[PDF]](./papers/topic-modeling/TKDE14_BPT.pdf) :star::star::star::star::star:
* **BTM**: Xiaohui Yan, Jiafeng Guo, Yanyan Lan, Xueqi Cheng. "A Biterm Topic Model for Short Texts". WWW (2013) [[PDF]](./papers/topic-modeling/WWW13_BTM.pdf) [[code]](https://github.com/xiaohuiyan/BTM) :star::star::star::star:
* **HGTM**: Yuan Wang, Jie Liu, Yalou Huang, Xia Feng. "Using Hashtag Graph-Based Topic Model to Connect Semantically-Related Words Without Co-Occurrence in Microblogs". TKDE (2016) [[PDF]](./papers/topic-modeling/TKDE16_HGTM.pdf) :star::star::star::star::star:
* **WTTM**:	Ming Xu, Yang Cai, He-Sheng Wu, et al. "Intensity of Relationship Between Words: Using Word Triangles in Topic Discovery for Short Texts". APWeb/WAIM (2017) [[PDF]](./papers/topic-modeling/WAIM17_WTTM.pdf) :star::star:
* **COTM**: Yang Yang, Feifei Wang, Junni Zhang, Jin Xu, Philip S. Yu. "A topic model for co-occurring normal documents and short texts". WWW (2018) [[PDF]](./papers/topic-modeling/WWW18_COTM.pdf) :star::star::star::star::star: