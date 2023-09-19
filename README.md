# Federated-Learning-Papers
Research Advances in the Latest Federal Learning Papers (***Updated ~~March 27~~ June 26, 2023***)

Research papers related to federated learning and blockchain, anonymity, incentives, privacy protection, trustworthy fairness, and security attacks.

(**Note that: :blush: represents a newly added paper ! ! !**)
##  :blush: 联邦学习推荐10篇必读论文
* **(1) Federated Machine Learning： Concept and Applications（TIST19)** https://arxiv.org/pdf/1902.04885v1.pdf
    * 推荐理由：一篇联邦学习经典论文，主要介绍联邦学习基本概念、分类等。
 
* **(2) A Survey on Security and Privacy of Federated Learning (FGCS21)** https://www.sciencedirect.com/science/article/pii/S0167739X20329848
    * 推荐理由：非常详细的介绍了联邦学习中可能面对安全与隐私威胁问题。
  
* **(3) Communication-Efficient Learning of Deep Networks from Decentralized Data (PMLR17)** http://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf
    * 推荐理由：谷歌开山之作FedAvg经典聚合算法。
    
* **(4) Practical secure aggregation for privacy-preserving machine learning (CCS17)** https://dl.acm.org/doi/pdf/10.1145/3133956.3133982
    * 推荐理由：首篇安全聚合方法、隐私保护的经典论文。
     
* **(5) Local Model Poisoning Attacks to Byzantine-Robust Federated Learning (Usenix Security 20)** https://www.usenix.org/system/files/sec20-fang.pdf
    * 推荐理由：介绍了现在经典的防御算法，又有比较完整攻击构造思路，可以比较快对安全方面攻防有了解。
 
* **(6) How To Backdoor Federated Learning (PMLR20)** http://proceedings.mlr.press/v108/bagdasaryan20a/bagdasaryan20a.pdf
    * 推荐理由：后门攻击首篇，讲了ML与FL的后门，补充一下攻击后门内容。 
     
* **(7) Privacy-Enhanced Federated Learning against Poisoning Adversaries (TIFS21)** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9524709&tag=1
    * 推荐理由：首个有效检测密文下中毒行为、用密码学实现模型隐私保护加鲁棒的方法，后续基本沿用这个思路。
  
* **(8) Advances and Open Problems in Federated Learning (arXiv21)** https://arxiv.org/pdf/1912.04977.pdf
    * 推荐理由：由60+位作者撰写的120+多页的联邦学习研究进展，非常详细介绍了FL分类、提升效率方法和开放问题等。
    
* **(9) 机器学习的隐私保护研究综述 (计算机研究与发展20)** https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7i8oRR1PAr7RxjuAJk4dHXovrKXcg6e1rYhPkHBifcN9saK_Xm5GXczqfF-Um9sk33&uniplatform=NZKPT
    * 推荐理由：一篇经典的中文论文，详细地介绍了两条隐私保护技术路线，并指出还面临的挑战。
    
* **(10) 联邦学习系统攻击与防御技术研究综述 (计算机学报 23)** http://cjc.ict.ac.cn/online/bfpub/gy-2023222151851.pdf
    * 推荐理由：一篇最新的中文论文，非常详细地介绍了FL中攻击和防御方法。
  
## 一、CCF B及以上安全会议收录情况（2020~2023）
### 1.1 S&P (CCF A)
* 2020年收录情况：

  * **Private Aggregation from Fewer Anonymous Messages**. https://arxiv.org/abs/1909.11073v1
  * **Beyond Software Watermarking: Traitor-Tracing for Pseudorandom Functions**. https://eprint.iacr.org/2020/316.pdf

* 2021年收录情况：
无

* 2022年收录情况：
  * **Back to the Drawing Board: A Critical Evaluation of Poisoning Attacks on Federated Learning.** https://arxiv.53yu.com/pdf/2108.10241.pdf
  * **SNARKBlock: Federated Anonymous Blocklisting from Hidden Common Input Aggregate Proofs.** https://eprint.iacr.org/2021/1577.pdf 
  * **SoK: How Robust is Image Classification Deep Neural Network Watermarking?** https://arxiv.org/pdf/2108.04974
  * **Copy, Right? A Testing Framework for Copyright Protection of Deep Learning Models.** https://arxiv.org/pdf/2112.05588

* 2023年收录情况：

  * **FedRecover: Recovering from Poisoning Attacks in Federated Learning using Historical Information.** https://arxiv.org/pdf/2210.10936.pdf.
      * 简要内容：如何从投毒攻击中恢复全局模型仍然是一个未解决的挑战。本文提出了可以从投毒攻击中恢复精确全局模型的方法，且对客户端来说计算量和通信成本很小。

  * **RAB: Provable Robustness Against Backdoor Attacks.** https://arxiv.org/pdf/2003.08904.pdf 
      * 简要内容：对后门攻击的可证明鲁棒性仍然很大程度未被探索。本文重点验证了机器学习模型对一般威胁模型，特别是后门攻击的鲁棒性。

  * **Certified Robustness for Deep Neural Networks.** https://arxiv.org/pdf/2009.04131.pdf 
      * 简要内容：基于深度神经网络（DNNs）容易受到对抗性攻击问题。本文系统化证明鲁棒方法和相关实践和理论。还为现有的鲁棒性验证和不同数据集上的训练方法提供了一个综合基准。

  *  :blush: **RoFL: Robustness of Secure Federated Learning.** https://www.computer.org/csdl/proceedings-article/sp/2023/933600a453/1NrbXOE6imk. 
      * 简要内容：RoFL是一种新的安全FL系统，它通过隐私保护输入验证扩展了安全聚合。具体而言，RoFL可以在高维加密模型更新中强制执行L_2和L_∞边界等约束。
  
  *  :blush: **Flamingo: Multi-Round Single-Server Secure Aggregation with Applications to Private Federated Learning.** https://eprint.iacr.org/2023/486. 
      * 简要内容：Flamingo专注于在联邦学习中发现的多轮设置，新的轻量级退出弹性协议，新的本地选择所谓客户端邻域的方法，这些技术帮助Flamingo减少了客户机和服务器之间的交互次数，从而大大减少了完整培训会话的端到端运行时时间。

  *  :blush: **ELSA: Secure Aggregation for Federated Learning with Malicious Actors.** https://eprint.iacr.org/2022/1695.
      * 简要内容：ELSA提供了一种基于跨两台服务器的分布式信任构建的新型安全聚合协议，只要一台服务器是诚实的，就可以保持单个客户端更新的私密性，防御恶意客户端，并且是高效的端到端。

  *  :blush: **BayBFed: Bayesian Backdoor Defense for Federated Learning.** https://arxiv.org/abs/2301.09508.

  *  :blush: **FedRecover: Recovering from Poisoning Attacks in Federated Learning using Historical Information.** https://arxiv.org/abs/2210.10936. 

  *  :blush: **ADI: Adversarial Dominating Inputs in Vertical Federated Learning Systems.** https://www.computer.org/csdl/proceedings-article/sp/2023/933600b875/1NrbZgBwxa0.
      * 简要内容：发现参与者的某些输入，称为对抗性主导输入 (ADI)，可以主导对对手意志方向的联合推理，并迫使其他（受害者）参与者做出微不足道的贡献，失去通常根据他们在联邦学习场景中贡献的重要性而提供的奖励。我们通过首先证明它们存在于典型的 VFL 系统中来对 ADI 进行系统研究。
   
  *  :blush: **3DFed: Adaptive and Extensible Framework for Covert Backdoor Attack in Federated Learning.** https://www.computer.org/csdl/proceedings-article/sp/2023/933600b893/1NrbZhCP5ao. 
      * 简要内容：本文提出了一种自适应的、可拓展的多层框架：3DFed，通过约束损失的后门训练、噪声掩码和诱饵模型三个模块对FL系统发起隐蔽的后门攻击。

### 1.2 CCS (CCF A)
* 2021年收录情况：

  * **Private Hierarchical Clustering in Federated Networks.** https://dl.acm.org/doi/pdf/10.1145/3460120.3484822 
  * **Private and Reliable Neural Network Inference.** https://files.sri.inf.ethz.ch/website/papers/ccs22-phoenix.pdf

* 2022年收录情况：
  * **EIFFeL: Ensuring Integrity for Federated Learning.** https://arxiv.53yu.com/pdf/2112.12727.pdf 
  * **Eluding Secure Aggregation in Federated Learning via Model Inconsistency.** https://arxiv.53yu.com/pdf/2111.07380.pdf
      * 简要内容：安全聚合阻止了服务器了解用户提供的各个模型来源，从而阻碍了推理和数据归因攻击。本文展示了恶意服务器很容易逃避安全聚合，并设计了两种不同攻击，能够推断私人数据集信息，独立于参与聚合的用户数量。

  * **Federated Boosted Decision Trees with Differential Privacy.** https://arxiv.53yu.com/pdf/2210.02910.pdf 
  * **Foundations of Coin Mixing Services.** https://eprint.iacr.org/2022/942.pdf

* 2023年收录情况：
未出

### 1.3 Usenix Security (CCF A)
* 2020年收录情况：

  * **Local model poisoning attacks to byzantine-robust federated learning.** https://arxiv.org/abs/1911.11815 

* 2021年收录情况：
无

* 2022年收录情况：
  * **Label Inference Attacks Against Vertical Federated Learning.** https://www.usenix.org/system/files/sec22-fu-chong.pdf 
  * **FLAME: Taming backdoors in federated learning.** https://arxiv.org/pdf/2101.02281v4.pdf
  * **Orca: Blocklisting in Sender-Anonymous Messaging.** https://www.usenix.org/conference/usenixsecurity22/presentation/tyagi

* 2023年收录情况：
  * **Gradient Obfuscation Gives a False Sense of Security in Federated Learning.** https://www.usenix.org/system/files/sec23summer_372-yue-prepub.pdf 
      * 简要内容：本文提出了一个新的重构攻击框架，针对FL的图像分类任务。
  
  * **Monero with Multi-Grained Redaction.** https://ieeexplore.ieee.org/abstract/document/10057988

### 1.4 NDSS (CCF A)
* 2021年收录情况：

  * **FLTrust: Byzantine-robust Federated Learning via Trust Bootstrapping.** https://arxiv.53yu.com/pdf/2012.13995.pdf 
      * 简要内容：恶意客户端仍能通过发送精心制作的局部模型更新来破坏全局模型。本文提出了一种新的FLTrust方法使服务器自己引导信任。通过收集一个小而干净的数据集。

  * **Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses for Federated Learning.** https://par.nsf.gov/servlets/purl/10286354 
  * **POSEIDON: Privacy-Preserving Federated Neural Network Learning.** https://arxiv.org/pdf/2009.00349

* 2022年收录情况：
  * **DeepSight: Mitigating Backdoor Attacks in Federated Learning Through Deep Model Inspection.** https://www.ndss-symposium.org/wp-content/uploads/2022-156-paper.pdf 

* 2023年收录情况：
  * **PPA: Preference Profiling Attack Against Federated Learning.**  https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s171_paper.pdf
      * 简要内容：由于推理攻击、FL中的数据隐私仍然存在泄露。本文提出了一种新型的隐私推理攻击，称为偏好分析攻击（PPPA），它准确地分析了本地服务器的私有信息。

  * **Securing Federated Sensitive Topic Classification against Poisoning Attacks.** https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s112_paper.pdf
      * 简要内容：本文提出了一个基于FL的解决方案，用来构建一个分布式分类器，来检测相关敏感内容，如健康、政治信仰、性取向等。

### 1.5 ACSAC (CCF B)
* 2021年收录情况：

  * **Efficient, Private and Robust Federated Learning.** https://tianweiz07.github.io/Papers/21-acsac.pdf 

* 2022年收录情况：
  * **Learning from Failures: Secure and Fault-Tolerant Aggregation for Federated Learning.** https://m-mansouri.com/docs/FTSA-22.pdf 
  * **Compressed Federated Learning Based on Adaptive Local Differential Privacy.** https://dl.acm.org/doi/pdf/10.1145/3564625.3567973 
  * **AFLGuard: Byzantine-robust Asynchronous Federated Learning.** https://arxiv.53yu.com/pdf/2212.06325.pdf 
  * **Closing the Loophole: Rethinking Reconstruction Attacks in Federated Learning from a Privacy Standpoint.** https://www.acsac.org/2022/program/papers/293-Na-Applied_Crypto_Privacy_and_Anonymity.pdf 

* 2023年收录情况：
未出

### 1.6 ESORICS (CCF B)
* 2020年收录情况：

  * **Data Poisoning Attacks Against Federated Learning Systems.** https://arxiv.53yu.com/pdf/2007.08432.pdf 
  * **A Framework for Evaluating Client Privacy Leakages in Federated Learning.** https://linkspringer.53yu.com/chapter/10.1007/978-3-030-58951-6_27 

* 2021年收录情况：
  * **CONTRA: Defending Against Poisoning Attacks in Federated Learning.** https://par.nsf.gov/servlets/purl/10294585 
  * **Romoa: Robust Model Aggregation for the Resistance of Federated Learning to Model Poisoning Attacks.** https://linkspringer.53yu.com/chapter/10.1007/978-3-030-88418-5_23 
  * **FLOD: Oblivious Defender for Private Byzantine-Robust Federated Learning with Dishonest-Majority.** https://eprint.iacr.org/2021/993.pdf 
  * **A k-Anonymised Federated Learning Framework with Decision Trees.** https://linkspringer.53yu.com/chapter/10.1007/978-3-030-93944-1_7 
      * 简要内容：本文提出了一个隐私保护框架，在FL设置中使用Mondrian k匿名和决策树来保护水平分区的数据，并使用新方法通过解决优化问题来创建Non-IID数据分区。

* 2022年收录情况：
  * **Local Differential Privacy for Federated Learning.** https://linkspringer.53yu.com/chapter/10.1007/978-3-031-17140-6_10 
  * **FLMJR: Improving Robustness of Federated Learning via Model Stability.** https://link.springer.com/chapter/10.1007/978-3-031-17143-7_20 
  * **Long-Short History of Gradients Is All You Need: Detecting Malicious and Unreliable Clients in Federated Learning.** https://linkspringer.53yu.com/chapter/10.1007/978-3-031-17143-7_22 

* 2023年收录情况：
未出

### 1.7 SRDS (CCF B)
* 2020年收录情况：

  * **Double Insurance: Incentivized Federated Learning with Differential Privacy in Mobile Crowdsensing.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9251919 

* 2021年收录情况：
  * **WAFFLE: Watermarking in Federated Learning.** https://arxiv.53yu.com/pdf/2008.07298.pdf 

* 2022年收录情况：
  * **D-Cliques: Compensating for Data Heterogeneity with Topology in Decentralized Federated Learning.** https://arxiv.53yu.com/pdf/2104.07365.pdf 
  * **AGIC: Approximate Gradient Inversion Attack on Federated Learning.** https://arxiv.53yu.com/pdf/2204.13784.pdf 
  * **Never Too Late: Tracing and Mitigating Backdoor Attacks in Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9996850 
  * **FWC: Fitting Weight Compression Method for Reducing Communication Traffic for Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9996830 

* 2023年收录情况：
未出

### 1.8 DSN Workshops (CCF B)
* 2021年收录情况：

  * **An Approach for Peer-to-Peer Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9502443 

* 2022年收录情况：
  * **Federated Learning with Anomaly Client Detection and Decentralized Parameter Aggregation.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833835 
  * **On the impact of non-IID data on the performance and fairness of differentially private federated learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833842 

* 2023年收录情况：
未出

## 二、CCF B及以上期刊收录情况（2020~2023）
### 2.1 TIFS (CCF A)
* 2020年收录情况：

  * **VerifyNet: Secure and Verifiable Federated Learning.** https://sci-hub.st/10.1109/tifs.2019.2929409 
  * **Federated Learning with Differential Privacy: Algorithms and Performance Analysis.** https://sci-hub.st/10.1109/tifs.2020.2988575 

* 2021年收录情况：
  * **VeriFL: Communication-Efficient and Fast Verifiable Aggregation for Federated Learning.** https://sci-hub.st/10.1109/tifs.2020.3043139 
  * **Privacy-Enhanced Federated Learning Against Poisoning Adversaries.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9524709 

* 2022年收录情况：
  * **Comment on “Federated Learning With Differential Privacy: Algorithms and Performance Analysis”.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10023534 
  * **FLCert: Provably Secure Federated Learning Against Poisoning Attacks.** https://arxiv.53yu.com/pdf/2210.00584.pdf 
  * **PVD-FL: A Privacy-Preserving and Verifiable Decentralized Federated Learning Framework.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9777682 
  * **Privacy-Preserving Byzantine-Robust Federated Learning via Blockchain Systems.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9849010 
  * **ShieldFL: Mitigating Model Poisoning Attacks in Privacy-Preserving Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9762272 
  * **PFLF: Privacy-Preserving Federated Learning Framework for Edge Computing.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9772495 

* 2023年收录情况：
  * **Privacy-Preserving and Verifiable Federated Learning Framework for Edge Computing.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9973347 
  * **Comments on "Privacy-Enhanced Federated Learning Against Poisoning Adversaries".** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10023534 
  * **LSFL: A Lightweight and Secure Federated Learning Scheme for Edge Computing.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9947081 
  * **Privacy-Preserving Federated Learning via Functional Encryption, Revisited.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10064312 
  * **Amplitude-Varying Perturbation for Balancing Privacy and Utility in Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10073536 
   
  *  :blush: **SAFELearning: Secure Aggregation in Federated Learning With Backdoor Detectability.** https://ieeexplore.ieee.org/document/10136231. 
      * 简要内容：本文提出了一种新的联邦学习技术SAFELearning来支持安全聚合的后门检测。通过无关随机分组（ORG）和部分参数披露（PPD）来实现。ORG将参与者划分为一次性随机子组，其配置对参与者无关，PPD允许对聚合子组模型进行安全的部分公开，以进行异常检测，而不会泄露单个模型的隐私。
    
  *  :blush: **Efficient Verifiable Protocol for Privacy-Preserving Aggregation in Federated Learning.** https://ieeexplore.ieee.org/document/10121168. 
      * 简要内容：提出了一种用于FL设置中安全聚合模型参数的通信高校协议，其中在用户设备上进行训练，而聚合训练模型可以在服务器构建而不泄露用户的原始数据。提出的协议对用户退出具有鲁棒性，使得每个用户能够独立验证服务器提供的聚合结果。
    
  *  :blush: **VCD-FL: Verifiable, Collusion-resistant, and Dynamic Federated Learning.** https://ieeexplore.ieee.org/document/10109820. 
      * 简要内容：提出了第一个可验证的，抗共谋的动态FL (VCD-FL)，通过梯度分组和压缩来优化拉格朗日插值，以实现高效的FL可验证性，提出的有效验证机制与新的承诺方案相结合，VCD-FL可以检测聚合服务器是否参与共谋攻击。
    
  *  :blush: **An Efficient Privacy-Enhancing Cross-Silo Federated Learning and Applications for False Data Injection Attack Detection in Smart Grids.** https://ieeexplore.ieee.org/document/10103703. 
      * 简要内容：提出了一种高效的具有强隐私保护的跨竖井联邦学习方案。通过设计轻量级双层加密方案，仅在建立阶段和各方重新加入时的迭代中使用秘密共享，并通过并行计算加速计算性能，实现了高效的隐私保护联邦学习协议，并且允许客户端在训练过程中退出和重新加入。
 
**TIFS期刊收录情况小结**：联邦学习相关论文一年比一年多，近四年中，每年都有一篇Verifiable FL论文，这个小方向需要跟进。有三篇将FL应用到Edge Computing当中。上面的论文基本都围绕隐私保护和鲁棒性相关。

### 2.2 TDSC (CCF A)
* 2021年收录情况：

  * **DeepChain: Auditable and Privacy-Preserving Deep Learning with Blockchain-Based Incentive.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8894364 

* 2022年收录情况：
  * **VOSA: Verifiable and Oblivious Secure Aggregation for Privacy-Preserving Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9969897 
  * **A Multi-shuffler Framework to Establish Mutual Confidence for Secure Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9925088 
  * **A Differentially Private Federated Learning Model against Poisoning Attacks in Edge Computing.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9760102 
  * **SEAR: Secure and Efficient Aggregation for Byzantine-Robust Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9468910 
  * **Hercules: Boosting the Performance of Privacy-preserving Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9935302 

* 2023年收录情况：
  * **VerSA: Verifiable Secure Aggregation for Cross-Device Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9609695 
  * **Comments on “VERSA: Verifiable Secure Aggregation for Cross-Device Federated Learning”.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10061268 
  * **Secure Aggregation is Insecure: Category Inference Attack on Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9618806 
  * **Heterogeneous Differential-Private Federated Learning: Trading Privacy for Utility Truthfully.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10032626 
  * **PILE: Robust Privacy-Preserving Federated Learning via Verifiable Perturbations.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10024795 
  * **Aggregation Service for Federated Learning: An Efficient, Secure, and More Resilient Realization.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9695218 
    
  *  :blush: **Privacy-Preserving and Byzantine-Robust Federated Learning.** https://ieeexplore.ieee.org/document/10093038/authors#authors. 
      * 简要内容：提出了一种隐私保护和拜占庭鲁棒FL方案II_P2Brofl，该方案在存在中毒攻击的情况下保持鲁棒性，同时保护局部模型的隐私。具体来说，II_P2Brofl利用三方计算(3PC)来安全地实现拜占庭鲁棒聚合方法。

**TDSC期刊收录情况小结**：在21年收录了一篇与区块链结合的论文，22年收录了两篇安全聚合的论文，而23年收录了三篇安全聚合的论文，安全聚合很重要。其他论文讨论了安全性和鲁棒性。

### 2.3 TPDS (CCF A)
* 2021年收录情况：
无

* 2022年收录情况：
无

* 2023年收录情况：
  *  :blush: **Securing Distributed SGD Against Gradient Leakage Threats.** https://ieeexplore.ieee.org/document/10119168. 
      * 简要内容：提出了一种梯度泄露弹性分布随机梯度下降（SGD）的整体方法。首先分析了隐私增强联邦学校的两种策略：1）随机选择或低秩滤波的梯度剪枝；2）加性随机噪声或差分隐私噪声的梯度扰动。

  *  :blush: **Dap-FL: Federated Learning Flourishes by Adaptive Tuning and Secure Aggregation.** https://ieeexplore.ieee.org/document/10103633. 
      * 简要内容：提出了一种深度确定性策略梯度（DDPG）辅助的自适应FL系统，称为Dap-FL。该系统中，所有资源异构的客户端通过本地部署的DDPG辅助的自适应超参数选择方案自适应地调整局部学习率和局部训练时间。针对安全性问题，引入Paillier密码系统，以安全和隐私保护的方式对局部模型进行聚合。

### 2.4 TSC (CCF A)
* 2023年收录情况：

  * **Privacy-Preserving and Reliable Decentralized Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10056968 
  * **FedChain: Secure Proof-of-Stake-based Framework for Federated-blockchain Systems.** https://arxiv.53yu.com/pdf/2101.12428.pdf 

**TSC期刊收录情况小结**：IEEE Trans. Services Computing只有23年开始收录了两篇联邦学习与区块链相关论文，前几年都未收录。

### 2.5 Computer & Security (CCF B)
* 2020年收录情况：

  * **A trusted feature aggregator federated learning for distributed malicious attack detection.** https://www.sciencedirect.com/science/article/pii/S0167404820303060 

* 2021年收录情况：
  * **Privacy-preserving and communication-efficient federated learning in Internet of Things.** https://www.sciencedirect.com/science/article/pii/S0167404821000237 
  * **Integration of federated machine learning and blockchain for the provision of secure big data analytics for Internet of Things.** https://www.sciencedirect.com/science/article/pii/S0167404821002170 
  * **Integration of blockchain and federated learning for Internet of Things: Recent advances and future challenges.** https://www.sciencedirect.com/science/article/pii/S0167404821001796 

* 2022年收录情况：
  * **Top-k sparsification with secure aggregation for privacy-preserving federated learning.** https://www.sciencedirect.com/science/article/pii/S0167404822003856 
  * **Preserving data privacy in federated learning through large gradient pruning.** https://www.sciencedirect.com/science/article/pii/S016740482200431X 
  * **Privacy, accuracy, and model fairness trade-offs in federated learning.**  https://www.sciencedirect.com/science/article/pii/S0167404822003005 

* 2023年收录情况：
  * **SparSFA: Towards robust and communication-efficient peer-to-peer federated learning.** https://www.sciencedirect.com/science/article/pii/S0167404823000925 
  * **2DF-IDS: Decentralized and differentially private federated learning-based intrusion detection system for industrial IoT.**
https://www.sciencedirect.com/science/article/pii/S016740482300007X 
    
  *  :blush: **Improve individual fairness in federated learning via adversarial training.** 
      * 简要内容：本文首先考虑隐私和个人公平，提出在不侵犯数据隐私的情况下，通过分布式对抗训练来促进FL中的个人公平。具体来说，我们假设一个满足个体公平性的模型对某些敏感扰动具有鲁棒性，这与对抗性训练的目标一致。

  *  :blush: **Enhancing federated learning robustness in adversarial environment through clustering Non-IID features.** 
      * 简要内容：提出一种名为Mini-Federated Learning (Mini-FL)的新FL框架，减轻了现有FL方法在非iid和对抗性场景中的上述弱点。Mini-FL遵循一般的FL方法，但考虑了FL的非iid来源，并按组汇总梯度。

**Computer & Security期刊收录情况小结**：近四年收录的数量相当，不多就两三篇，主要围绕IoT应用、安全聚合、隐私保护、性能提升等方面。

### 2.6 TII (SCI Q1\CCF C)

* 2020年收录情况：
  * **Blockchain and Federated Learning for Privacy-Preserved Data Sharing in Industrial IoT.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8843900 

* 2021年收录情况：
  * **Low-Latency Federated Learning and Blockchain for Edge Association in Digital Twin Empowered 6G Networks.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9170905 
  * **Anonymous and Privacy-Preserving Federated Learning With Industrial Big Data.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9325934 
  * **TrustFed: A Framework for Fair and Trustworthy Cross-Device Federated Learning in IIoT.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9416805 

* 2022年收录情况：
  * **A Blockchain-Empowered Cluster-Based Federated Learning Model for Blade Icing Estimation on IoT-Enabled Wind Turbine.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9739983 
  * **VFL: A Verifiable Federated Learning With Privacy-Preserving for Big Data in Industrial IoT.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9250650 
  * **Privacy-Preserved Cyberattack Detection in Industrial Edge of Things (IEoT): A Blockchain-Orchestrated Federated Learning Approach.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9760107 
  * **Block Hunter: Federated Learning for Cyber Threat Hunting in Blockchain-Based IIoT Networks.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9759988 

* 2023年收录情况：
  * **Toward Trustworthy and Privacy-Preserving Federated Deep Learning Service Framework for Industrial Internet of Things.**
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9903398 
  * **Blockchain-Based Federated Learning With Secure Aggregation in Trusted Execution Environment for Internet-of-Things.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9763363 
  * **Privacy-Preserving Federated Learning for Industrial Edge Computing via Hybrid Differential Privacy and Adaptive Compression.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9628062 
  * **Privacy-Preserved Generative Network for Trustworthy Anomaly Detection in Smart Grids: A Federated Semisupervised Approach.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9754257 
  * **Byzantine-Robust Aggregation in Federated Learning Empowered Industrial IoT.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9614992 
  * **Cloud-IIoT-Based Electronic Health Record Privacy-Preserving by CNN and Blockchain-Enabled Federated Learning.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9817643 
  * **Decentralized Federated Learning With Markov Chain Based Consensus for Industrial IoT Networks.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833351 

**TII期刊收录情况小结**：IEEE Transactions on Industrial Informatics每年收录大量联邦学习相关论文，且逐年增多，主要集中在FL的应用，如IoT、edge computing、smart grids、 big data、blockchain，22年四篇就有三篇是和区块链结合。

### 2.7 IOT (SCI Q1\CCF C)
* 2021年收录情况：

  * **DS2PM:A Data Sharing Privacy Protection Model Based on Blockchain and Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9646996 
  * **Federated Learning Meets Blockchain in Edge Computing: Opportunities and Challenges.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9403374 
  * **Hybrid Blockchain-Based Resource Trading System for Federated Learning in Edge Computing.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9223754 
  * **Privacy-Preserving Blockchain-Based Federated Learning for IoT Devices.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9170559 
  * **Blockchain-Based Federated Learning for Device Failure Detection in Industrial IoT.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9233457 
  * **Incentivizing Differentially Private Federated Learning: A Multidimensional Contract Approach.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9317806 
  * **Federated Learning Meets Blockchain: State Channel based Distributed Data Sharing Trust Supervision Mechanism.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9624959 
  * **BESIFL: Blockchain Empowered Secure and Incentive Federated Learning Paradigm in IoT.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9663227 

* 2022年收录情况：
  * **Privacy-Enhanced and Verification-Traceable Aggregation for Federated Learning.**  https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9846908 
  * **High-Quality Model Aggregation for Blockchain-Based Federated Learning via Reputation-Motivated Task Participation.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9737334 
  * **Secure and Privacy-Preserving Federated Learning via Co-Utility.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9504596 
  * **Securing Critical IoT Infrastructures With Blockchain-Supported Federated Learning.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9449650 
  * **Bift: A Blockchain-Based Federated Learning System for Connected and Autonomous Vehicles.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9650783 
  * **DIM-DS: Dynamic Incentive Model for Data Sharing in Federated Learning Based on Smart Contracts and Evolutionary Game Theory.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9831779 
  * **Cooperative Federated Learning and Model Update Verification in Blockchain-Empowered Digital Twin Edge Networks.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9606227 

* 2023年收录情况：
  * **Decentral and Incentivized Federated Learning Frameworks: A Systematic Literature Review.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9997105 
  * **Toward Trustworthy AI: Blockchain-Based Architecture Design for Accountability and Fairness of Federated Learning Systems.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9686048 
  * **Trustworthy Federated Learning via Blockchain.** 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9866512 
  * **Blockchain-Based Decentralized Model Aggregation for Cross-Silo Federated Learning in Industry 4.0.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9933813 
  * **Contract-Theory-Based Incentive Mechanism for Federated Learning in Health CrowdSensing.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9932890 
  * **Adaptive Resource Allocation for Blockchain-based Federated Learning in Internet of Things.** https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10034764 

**IOT期刊收录情况小结**：IEEE Internet of Things Journal每年收录大量联邦学习相关论文，且逐年增多，主要集中在FL的应用，如IoT、health crowdSensing、autonomous vehicles 、blockchain等，和区块链结合的论文居多，还有激励、信任、去中心化、验证和可追溯等相关论文。


