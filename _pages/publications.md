---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## 2025
Ezekiel O. Soremekun, Mike Papadakis, Maxime Cordy, Yves Le Traon. ["Software Fairness: An Analysis and Survey](), in ACM Computing Surveys, to appear.

Amal AKLI, Maxime Cordy, Mike Papadakis, Yves Le Traon. ["On the Application of AutoML for Parameter-Efficient Fine-Tuning of Pre-Trained Code Models”](), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**), to appear.


Asma Hamidi, Ahmed Khanfir, and Mike Papadakis. ["Intent-Based Mutation Testing”](pdfs/Mutation25.pdf), in the 20th Inter- national Workshop on Mutation Analysis (**MUTATION**), ICST Workshops 2025.

Yu Pei, Jeongju Sohn and Mike Papadakis. ["An empirical study of web flaky tests: Understanding and unveiling DOM event interaction challenges”](pdfs/ICST25.pdf), in the 18th IEEE International Conference on Software Testing, Verification and Validation (**ICST**), 2025. 

Rafael Ramires, Ana Respıcio, Iberia Medeiros, Mike Papadakis. ["KAVe: A Tool to Detect XSS and SQLi Vulnerabilities using a Multi-Agent System over a Multi-Layer Knowledge Graph”](), in the ACM SIGSOFT International Symposium on the Foundations of Software Engineering (**FSE**), Demonstrations track.

Qiang Hu, Zeming Dong, Yuejun Guo, Zhenya Zhang, Maxime Cordy, Mike Papadakis, Yves Le Traon, Jianjun Zhao. ["Boosting Source Code Learning with Text-Oriented Data Augmentation: An Empirical Study”](https://link.springer.com/content/pdf/10.1007/s10664-025-10624-2.pdf), in Empirical Software Engineering Journal (**EMSE**). 

Qiang Hu, Yuejun Guo, Xiaofei Xie, Maxime Cordy, Wei Ma, Mike Papadakis, Lei Ma, Yves Le Traon. ["Assessing the Robustness of Test Selection Methods for Deep Neural Networks”](https://dl.acm.org/doi/pdf/10.1145/3715693), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**), to appear.




## 2024
Guillaume Haben, Sarra Habchi, John Micco, Mark Harman, Mike Papadakis, Maxime Cordy, Yves Le Traon.[“The Importance of Accounting for Execution Failures when Predicting Test Flakiness”](https://dl.acm.org/doi/pdf/10.1145/3691620.3695261), in the 39th IEEE/ACM International Conference on Automated Software Engineering -- Industry Showcase (**ASE 2024 Industry Showcase**).

Yu Pei, Jeongju Sohn, Sarra Habchi and Mike Papadakis. [“Non-Flaky and Nearly-Optimal Time-based Treatment of Asynchronous Wait Web Tests”](https://dl.acm.org/doi/pdf/10.1145/3695989), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**), to appear.

Ana Belen Sanchez, Jose Antonio Parejo, Sergio Segura, Amador Duran Toro, Mike Papadakis. [“Mutation Testing in Practice: Insights from Open-Source Software Developers”](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10472898), in IEEE Transactions on Software Engineering Journal (**TSE**), to appear.

Luiz Carvalho, Renzo Degiovanni, Maxime Cordy, Nazareno Aguirre, Yves Le Traon and Mike Papadakis. [“SpecBCFuzz: Fuzzing LTL Solvers with Boundary Conditions”](pdfs/Fuzzing_LTL_Solvers.pdf), in the 46th International Conference on Software Engineering (**ICSE**), 2024.

Agustın Nolasco, Facundo Molina, Renzo Degiovanni, Alessandra Gorla, Diego Garbervetsky, Mike Papadakis, Sebastian Uchitel, Nazareno Aguirre, Marcelo F. Frias. [“Abstraction-Aware Inference of Metamorphic Relations”](pdfs/metamorphic_relation_inference.pdf), in the ACM International Conference on the Foundations of Software Engineering (**FSE**), 2024.

Aayush Garg, Renzo Degiovanni, Mike Papadakis and Yves Le Traon. [“On the Coupling between Vulnerabilities and LLM-generated Mutants: A Study on Vul4J dataset”](pdfs/ICST24.pdf), in the 17th IEEE International Conference on Software Testing, Verification and Validation (**ICST**) 2024.

Qiang Hu, Yuejun Guo, Xiaofei Xie, Maxime Cordy, Lei Ma, Mike Papadakis, Yves Le Traon. [“Active Code Learning: Benchmarking Sample-Efficient Training of Code Models”](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10471610), in IEEE Transactions on Software Engineering Journal (**TSE**), to appear.


Qiang Hu, Yuejun Guo, Xiaofei Xie, Maxime Cordy, Lei Ma, Mike Papadakis, Yves Le Traon. [“Test Optimization in DNN Testing: A Survey”](https://dl.acm.org/doi/pdf/10.1145/3643678), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**), to appear.


Xueqi Dang, Yinghua Li, Mike Papadakis, Jacques Klein, Tegawende Bissyande, Yves Le Traon. [“Test input prioritization for Machine Learning Classifiers”](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10382258), in IEEE Transactions on Software Engineering Journal (**TSE**), to appear.

Zeming Dong, Qiang Hu, Zhenya Zhang, Yuejun Guo, Maxime Cordy, Mike Papadakis, Yves Le Traon and Jianjun Zhao. [“On the Effectiveness of Hybrid Pooling in Mixup-Based Graph Learning for Lan- guage Processing”](https://arxiv.org/pdf/2210.03123), in Journal of Systems and Software (**JSS**), to appear.

Xueqi Dang, Yinghua Li, Wei Ma, Yuejun Guo, Qiang Hu, Mike Papadakis, Maxime Cordy and Yves Le Traon. [“Towards Exploring the Limitations of Test Selection Techniques on Graph Neural Networks: An Empirical Study”](https://link.springer.com/content/pdf/10.1007/s10664-024-10515-y.pdf), in Empirical Software Engineering Journal (**EMSE**). 



## 2023
Salah Ghamizi, Jingfeng Zhang, Maxime Cordy, Mike Papadakis, Masashi Sugiyama, Yves Le Traon. [“GAT: Guided Adversarial Training with Pareto-optimal Auxiliary Tasks”](https://doi.org/10.48550/arXiv.2302.02907), in the 40th International Conference on Machine Learning (**ICML**), 2023.

Ezekiel Soremekun, Lukas Kirschner, Marcel Böhme, Mike Papadakis. [“Evaluating the Impact of Experimental Assumptions in Automated  Fault Localization”](pdfs/ICSE23.Debugging.pdf), in the 45th International Conference on Software Engineering (**ICSE**), 2023.

Qiang Hu, Yuejun Guo, Xiaofei Xie, Maxime Cordy, Lei Ma, Mike Papadakis, Yves Le Traon. [“Aries: Efficient Testing of Deep Neural Networks via  Labeling-Free Accuracy Estimation”](pdfs/ICSE2023_Acc_Estimation.pdf), in the 45th International Conference on Software Engineering (**ICSE**), 2023.

Milos Ojdanic, Aayush Garg, Ahmed Khanfir, Renzo Degiovanni, Mike Papadakis, Yves Le Traon. [“Syntactic Vs. Semantic similarity of Artificial and Real Faults in Mutation Testing Studies”](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10136793), in IEEE Transactions on Software Engineering Journal (**TSE**), to appear.

Xueqi Dang, Yinghua Li, Mike Papadakis, Jacques Klein, Tegawende Bissyande, Yves Le Traon. [“GraphPrior: Mutation-based Test Input Prioritization for Graph Neural Networks”](https://dl.acm.org/doi/pdf/10.1145/3607191), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**), to appear.

Yuejun Guo, Qiang Hu, Xiaofei Xie, Maxime Cordy, Mike Papadakis, Yves Le Traon. [“KAPE: kNN-Based Performance Testing for Deep Code Search”](https://dl.acm.org/doi/pdf/10.1145/3624735), in ACM Transactions on Software Engineering and Method- ology Journal (**TOSEM**), to appear.

Qiang Hu, Yuejun Guo, Xiaofei Xie, Maxime Cordy, Mike Papadakis, Yves Le Traon. [“LaF: Labeling-Free Model Selection for Automated Deep Neural Network Reusing”](https://dl.acm.org/doi/pdf/10.1145/3611666), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**), to appear.

Milos Ojdanic, Mike Papadakis, Mark Harman. [“Keeping Mutation Test Suites Consistent and Relevant with Long-Standing Mutants”](pdfs/FSE_NIER_2023.pdf), in the ACM SIGSOFT International Symposium on the Foundations of Software Engineering, Ideas, Visions and Reflections track (**FSE-IVR 2023**).

Aayush Garg, Renzo Degiovanni, Facundo Molina, Mike Papadakis, Nazareno Aguirre, Maxime Cordy, Yves Le Traon. [“Enabling Efficient Assertion Inference”](pdfs/Seeker-.pdf), in the 34th IEEE International Symposium on Software Reliability Engineering (**ISSRE**) 2023.

Matıas Brizzio, Renzo Degiovanni, Maxime Cordy, Mike Papadakis, Nazareno Aguirre, Cesar Sanchez. . ["Automated Repair of Unrealisable LTL Specifications Guided by Model Counting”](https://arxiv.org/pdf/2105.12595.pdf), in the Genetic and Evolutionary Computation Conference (**GECCO**), 2023.

Zeming Dong, Qiang Hu, Yuejun Guo, Maxime Cordy, Mike Papadakis, Zhenya Zhang, Yves Le Traon, Jianjun Zhao. [“MixCode: Enhancing Code Classification by Mixup-Based Data Augmentation”](pdfs/SANER__MixCode_Enhancing_Code_Classification_by_Mixup_Based_Data_Augmentation.pdf), in the 30th IEEE International Conference on Software Analysis, Evolution and Reengineering (**SANER**), 2023.

Luiz Carvalho, Renzo Degiovanni, Mat ́ıas Brizzio, Maxime Cordy, Nazareno Aguirre, Yves Le Traon, Mike Papadakis. [“ACoRe: Automated Goal-Conflict Resolution”](https://arxiv.org/pdf/2303.05213), in 26th International Conference on Fundamental Approaches to Software Engineering (**FASE**), 2023.

Salah Ghamizi, Maxime Cordy, Mike Papadakis and Yves Le Traon. [“On evaluating adversarial robustness of Chest X-ray classification: Requirements & Good Practices”](https://arxiv.org/pdf/2212.08130.pdf), in the AAAI Workshop on Artificial Intelligence Safety (**SafeAI**), 2023.  

Qiang Hu, Yuejun Guo, Xiaofei Xie, Maxime Cordy, Lei Ma, Mike Papadakis, Yves Le Traon. [“Towards Code Model Generalization Under Distribution Shift”](pdfs/ICSE23_NIER_CodeS.pdf), in the 45th International Conference on Software Engineering, New Ideas and Emerging Results track (**ICSE-NIER**), 2023.

Amal Akli, Guillaume Haben, Sarra Habchi, Mike Papadakis and Yves Le Traon. [“FlakyCat: Predicting Flaky Tests Categories using Few-Shot Learning”](pdfs/FlakyCat.pdf), in the 4th ACM/IEEE International Conference on Automation of Software Test (**AST**), 2023.

Milos Ojdanic, Ahmed Khanfir, Aayush Garg, Renzo Degiovanni, Mike Papadakis and Yves Le Traon. [“On Comparing Mutation Testing Tools through Learning-based Mutant Selection”](pdfs/AST_2023.pdf), in the 4th ACM/IEEE International Conference on Automation of Software Test (**AST**), 2023. **Best paper award**.

Qiang Hu, Yuejun Guo, Maxime Cordy, Xiaofei Xie, Wei Ma, Mike Papadakis, Yves Le Traon. [“Towards Understanding Model Quantization for Reliable Deep Neural Network Deployment”](pdfs/CAIN2023_quantization.pdf), in 2nd International Conference on AI Engineering – Software Engineering for AI (**CAIN**) 2023.

Qiang Hu, Yuejun Guo, Maxime Cordy, Mike Papadakis, Yves Le Traon.  [“MUTEN: Mutant-Based Ensembles for Boosting Gradient-Based Adversarial Attack”](pdfs/MUTEN.pdf), in the 38th IEEE/ACM International Conference on Automated Software Engineering, New Ideas and Emerging Results track (**ASE-NIER 2023**).


## 2022
Ahmed Khanfir, Anil Koyuncu, Mike Papadakis, Maxime Cordy, Tegawende F. Bissyande, Jacques Klein and Yves Le Traon. ["IBIR: Bug Report driven Fault Injection"](https://arxiv.org/pdf/2012.06506.pdf), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**).

Aayush Garg, Milos Ojdanic, Renzo Degiovanni, Thierry Titcheu Chekam, Mike Papadakis, Yves Le Traon. ["Cerebro: Static Subsuming Mutant Selection"](https://arxiv.org/pdf/2112.14151), in IEEE Transactions on Software Engineering Journal (**TSE**).

Milos Ojdanic,Ezekiel Soremekun, Renzo Degiovanni, Mike Papadakis and Yves Le Traon. ["Mutation Testing in Evolving Systems: Studying the relevance of mutants to code evolution"](https://arxiv.org/pdf/2112.14566), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**).

Renaud Rwemalika, Sarra Habchi, Mike Papadakis, Yves Le Traon, Marie-Claude Brasseur. ["Smells in System User Interactive Tests"](https://arxiv.org/pdf/2111.02317.pdf), in Empirical Software Engineering Journal (**EMSE**). 

Milos Ojdanic, Wei Ma, Thomas Laurent, Thierry Titcheu Chekam, Anthony Ventresque, Mike Papadakis. ["On the Use of Commit-Relevant Mutants"](pdfs/ESE_2021_extension.pdf), in Empirical Software Engineering Journal (**EMSE**). 

Aayush Garg, Renzo Degiovanni, Matthieu Jimenez, Maxime Cordy, Mike Papadakis, Yves Le Traon.  ["Learning from What We Know: How to Perform Vulnerability Prediction using Noisy Historical Data"](https://arxiv.org/pdf/2012.11701),  in Empirical Software Engineering Journal (**EMSE**).

Qiang Hu, Yuejun Guo, Maxime Cordy, Xiaofei Xie, Lei Ma, Mike Papadakis, Yves Le Traon. ["An Empirical Study on Data Distribution-Aware Test Selection for Deep Learning Enhancement"](pdfs/TOSEM_DAT.pdf), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**).

Yuejun Guo, Qiang Hu, Maxime Cordy, Mike Papadakis, Yves Le Traon. ["DRE: density-based data selection with entropy for adversarial-robust deep learning models"](https://link.springer.com/content/pdf/10.1007/s00521-022-07812-2.pdf), in Neural Computing and Applications (2022). 

Maxime Cordy, Renaud Rwemalika, Adriano Franci, Mike Papadakis, Mark Harman. [“FlakiMe: Laboratory-Controlled Test Flakiness Impact Assessment”](pdfs/ICSE22___Flakime.pdf), in the 44th International Conference on Software Engineering (**ICSE**), 2022.

Zeyu Sun, Jie Zhang, Yingfei Xiong, Mark Harman, Mike Papadakis, Lu Zhang. [“Improving Machine Translation Systems via Isotopic Replacement”](pdfs/ICSE22_CAT.pdf), in the 44th International Conference on Software Engineering (**ICSE**), 2022.

Salah Ghamizi, Maxime Cordy, Mike Papadakis, Yves Le Traon. [“Adversarial Robustness in Multi-Task Learning: Promises and Illusions"](https://arxiv.org/pdf/2110.15053.pdf), in the 36th AAAI Conference on Artificial Intelligence (**AAAI**) 2022.

Martin Gubri, Maxime Cordy, Mike Papadakis, Yves Le Traon, Koushik Sen. ["Boosting Adversarial Example Transferability from Geometric Vicinity"](https://arxiv.org/pdf/2207.13129), in the European Conference on Computer Vision (**ECCV**) 2022.

Martin Gubri, Maxime Cordy, Mike Papadakis, Yves Le Traon, Koushik Sen [“Efficient and Transferable Adversarial Examples from Bayesian Neural Networks"](https://arxiv.org/pdf/2011.05074), in the 38th Conference on Uncertainty in Artificial Intelligence (**UAI**) 2022.

Wei Ma, Mengjie Zhao, Ezekiel Soremekun, Qiang Hu, Jie Zhang, Mike Papadakis, Maxime Cordy, Xiaofei Xie, Yves Le Traon. ["GraphCode2Vec: Generic Code Embedding via Lexical and Program Dependence Analyses"](pdfs/MSR22.pdf), in the 19th International Conference on Mining Software Repositories (**MSR**), 2022.

Sarra	Habchi, Guillaume	Haben, Mike	Papadakis, Maxime	Cordy, Yves	Le Traon. ["A Qualitative Study on the Sources, Impacts, and Mitigation Strategies of Flaky Tests"](https://arxiv.org/pdf/2112.04919.pdf), in the 15th IEEE International Conference on Software Testing, Verification and Validation (**ICST**) 2022.

Jeongju Sohn and Mike Papadakis. ["CEMENT: On the use of Evolutionary Coupling between tests and code units. A case study on fault localization"](https://arxiv.org/pdf/2203.11343), in the 33rd IEEE International Symposium on Software Reliability Engineering (**ISSRE**) 2022.

Sarra Habchi, Guillaume Haben, Jeongju Sohn, Adriano Franci, Mike Papadakis, Maxime Cordy and Yves Le Traon. ["What Made This Test Flake? Pinpointing Classes Responsible for Test Flakiness"](https://arxiv.org/pdf/2207.10143), in 38th IEEE International Conference on Software Maintenance and Evolution (**ICSME**), 2022.

Ahmed Khanfir, Matthieu Jimenez, Mike Papadakis, Yves Le Traon. ["CodeBERT-nt: code naturalness via CodeBERT"](https://arxiv.org/pdf/2208.06042), in the 22nd IEEE International Conference on Software Quality, Reliability, and Security (**QRS**), 2022.

Benjamin Petit, Ahmed Khanfir, Ezekiel Soremekun, Gilles Perrouin and Mike Papadakis. ["IntJect: Vulnerability Intent Bug Seeding"](pdfs/Vulnerability_Injection___QRS_2022.pdf), in the 22nd IEEE International Conference on Software Quality, Reliability, and Security (**QRS**), 2022.

Renzo Degiovanni and Mike Papadakis. ["μBERT: Mutation Testing using Pre-Trained Language Models"](https://arxiv.org/pdf/2203.03289), in the 17th International Workshop on Mutation Analysis (**MUTATION**), 2022.

Yu Pei, Sarra Habchi, Renaud Rwemalika, Jeongju Sohn, Mike Papadakis. ["An empirical study of async wait flakiness in front-end testing"](https://ceur-ws.org/Vol-3245/paper7.pdf). Belgium-Netherlands Software Evolution Workshop (**BENEVOL**) 2022.

Franci Adriano, Maxime Cordy, Martin Gubri, Mike Papadakis, Yves Le Traon. ["Influence-Driven Data Poisoning in Graph-Based Semi-Supervised Classifiers"](https://arxiv.org/pdf/2012.07381.pdf), in the 1st International Conference on AI Engineering – Software Engineering for AI (**CAIN**) 2022. 

## 2021
Thierry Titcheu Chekam, Mike Papadakis, Maxime Cordy, Yves Le Traon. [“Killing Stubborn Mutants with Symbolic Execution”](pdfs/TOSEM2021.pdf), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**), vol 30(2), 2021, pp. 19:1-19:23

Wei Ma, Mike Papadakis, Anestis Tsakmalis, Maxime Cordy, Yves Le Traon. [“Test Selection for Deep Learning Systems”](pdfs/TOSEM2021B.pdf), in ACM Transactions on Software Engineering and Methodology Journal (**TOSEM**), vol 30(2), 2021, pp. 13:1-13:22.

Wei Ma, Thierry Titcheu Chekam, Mike Papadakis, Mark Harman. [“MuDelta: Delta-Oriented Mutation Testing at Commit Time”](pdfs/ICSE2021.pdf), in the 43rd International Conference on Software Engineering (**ICSE**), 2021, pp. 897-909.

Guillaume Haben, Sarra Habchi, Mike Papadakis, Maxime Cordy, Le Traon Yves. [“A Replication Study on the Usability of Code Vocabulary in Predicting Flaky Tests”](pdfs/MSR2021.pdf), in the 18th International Conference on Mining Software Repositories (**MSR**), 2021, pp. 219-229.

Qiang Hu, Yuejun Guo, Maxime Cordy, Xiaofei Xie, Wei Ma, Mike Papadakis, Yves Le Traon. [“Towards Exploring the Limitations of Active Learning: An Empirical Study”](pdfs/ASE2021.pdf), in the 36th IEEE/ACM International Conference on Automated Software Engineering (**ASE**), 2021, pp. 917-929.

Salah Ghamizi, Maxime Cordy, Mike Papadakis, Yves Le Traon. [“Evasion Attack STeganography: Turning Vulnerability Of Machine Learning ToAdversarial Attacks Into A Real-world Application”](pdfs/EAST_ICCV2021.pdf), 2nd Workshop on Adversarial Robustness In the Real World, **ICCV Workshop**, 2021.

William Bonnaventure, Ahmed Khanfir, Alexandre Bartel, Mike Papadakis, Yves Le traon. [“Confuzzion: A Java Virtual Machine Fuzzer for Type Confusion Vulnerabilities”](pdfs/QRS2021.pdf), 21st IEEE International Conference on Software Quality, Reliability, and Security (**QRS**), 2021, **Best paper award**.

Maxime Cordy, Sami Lazreg, Mike Papadakis, Axel Legay. [“Statistical model checking for variability-intensive systems: applications to bug detection and minimization](https://doi.org/10.1007/s00165-021-00563-2). Formal Aspects of Computing (2021).

## 2020

Thierry Titcheu Chekam, Mike Papadakis, Tegawende Bissyande, Yves Le Traon and Koushik Sen. [“Selecting Fault Revealing Mutants”](pdfs/EMSE2020.pdf), in Empirical Software Engineering Journal (**EMSE**), vol. 25(1), 2020, pp. 434-487.

Wei Ma, Thomas Laurent, Milos Ojdanic, Thierry Titcheu Chekam, Anthony Ventresque, Mike Papadakis. [“Commit-Aware mutation Testing”](pdfs/ICSME2020.pdf), in 36th IEEE International Conference on Software Maintenance and Evolution (**ICSME**), 2020, pp. 394-405. **Distinquished paper award**.

Salah Ghamizi, Maxime Cordy, Martin Gubri, Mike Papadakis, Andrey Boystov, Yves Le Traon, Anne Goujon. [“Search-Based Adversarial Testing and Improvement of Constrained Credit Scoring Systems”](pdfs/FSE2020.pdf), in the Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (**ESEC/FSE**), 2020, pp. 1089-1100.

Zeyu Sun, Jie M. Zhang, Mark Harman, Mike Papadakis, Lu Zhang, [“Automatic Testing and Improvement of Machine Translation”](pdfs/ICSE2020.pdf), in the 42nd International Conference on Software Engineering (**ICSE**), 2020, pp. 974-985.

Salah Ghamizi, Renaud Rwemalika, Maxime Cordy, Lisa Veiber, Tegawend F. Bissyand, Mike Papadakis, Jacques Klein and Yves Le Traon. [“Data-driven Simulation and Optimization for Covid-19 Exit-Strategies”](pdfs/KDD2020.pdf), 26th SIGKDD conference on Knowledge Discovery and Data Mining, (**KDD-AI for COVID**) track, 2020, pp. 3434-3442. **Best paper award**.

Maxime Cordy, Mike Papadakis and Axel Legay, [“Statistical Model Checking for Variability-Intensive Systems”](pdfs/FASE2020.pdf), in the 23rd International Conference on Fundamental Approaches to Software Engineering (**FASE**), 2020, pp. 294-314.

Salah Ghamizi, Maxime Cordy, Mike Papadakis, Yves Le Traon. [“FeatureNET: Diversity-driven Generation of Deep Learning Models”](pdfs/ICSE-Tool2020.pdf), in the 42nd International Conference on Software Engineering (**ICSE**), tool demo track, 2020, pp. 41-44.

Thierry Titcheu Chekam, Mike Papadakis and Yves Le Traon, [“Muteria: An Extensible and Flexible Multi-Criteria Software Testing Framework”](pdfs/AST2020.pdf), in the 1st IEEE/ACM International Conference on Automation of Software Test (**AST**), 2020, pp. 97-100.

## 2019
Mike Papadakis, Marinos Kintis, Jie Zhang, Yue Jia, Yves Le Traon and Mark Harman, [“Mutation Testing Advances: An Analysis and Survey”](pdfs/MutationSurvey2019.pdf), in **Advances in Computers**, Elsevier, Vol. 112, pp. 275-378, doi https://doi.org/10.1016/bs.adcom.2018.03.015, 2019.

Donghwan Shin, Shin Yoo, Mike Papadakis, Doo-Hwan Bae. [“Empirical Evaluation of Mutation-based Test Case Prioritization Techniques”](pdfs/STVR2018.pdf), in Software Testing, Verification and Reliability Journal (**STVR**), vol. 29, 2019, pp. e1695.

Thierry Titcheu Chekam, Mike Papadakis, and Yves Le Traon. [“Mart: A Mutant Generation Tool for LLVM”](pdfs/FSE2019-Tool.pdf), in the Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (**FSE-Demo**), 2019, pp. 1080-1084.

Renaud Rwemalika, Marinos Kintis, Mike Papadakis, Yves Le Traon and Pierre Lorrach. [“Ukwikora: Continuous inspection for Keyword-Driven Testing”](pdfs/ISSTA2019-Tool.pdf), in the International Symposium on Software Testing and Analysis (**ISSTA-Demo**), 2019, pp. 402-405.

Matthieu Jimenez, Renaud Rwemalika, Mike Papadakis, Federica Sarro, Yves Le Traon and Mark Harman, [“The importance of accounting for real-world labelling when predicting software vulnerabilities”](pdfs/FSE2019.pdf), in the Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (**ESEC/FSE**), 2019, pp. 695-705. **Distinquished paper award**.

Renaud Rwemalika, Marinos Kintis, Mike Papadakis, Yves Le Traon and Pierre Lorrach. [“An industrial study on the differences between pre-release and post-release bugs”](pdfs/ICSME2019.pdf), in 35th IEEE International Conference on Software Maintenance and Evolution (**ICSME**), 2019, pp. 92-102.

Claire Leong, Abhayendra Singh, Mike Papadakis, Yves Le Traon and John Micco. [“Assessing Transition-based Test Selection Algorithms at Google”](pdfs/ICSE-SEIP2019.pdf), in the 41st International Conference on Software Engineering (**ICSE-SEIP**) track, 2019, pp. 101-110.

Salah Ghamizi, Maxime Cordy, Mike Papadakis and Yves Le Traon. [“Automated search for configurations of convolutional neural network architectures”](pdfs/SPLC2019.pdf), in 23rd ACM International Conference on Software Product Lines (**SPLC**), 2019, pp. 21:1-21:12.

Xavier Schmitt, Sylvain Kubler, Jeremy Robert, Mike Papadakis, Yves Le Traon. [“A Replicable Comparison Study of NER Software: StanfordNLP, NLTK, OpenNLP, SpaCy, Gate”](pdfs/SNAMS2019.pdf), in Sixth International Conference on Social Networks Analysis, Management and Security (**SNAMS**), 2019, pp. 338-343.

Rohan Padhye, Caroline Lemieux, Koushik Sen, Mike Papadakis and Yves Le Traon. [“Semantic Fuzzing with Zest”](pdfs/ISSTA2019B.pdf), in the International Symposium on Software Testing and Analysis (**ISSTA**), 2019, pp. 329-340. **Distinquished artifact award**.

Maxime Cordy, Steve Muller, Mike Papadakis and Yves Le Traon. [“Search-based Test and Improvement of Machine-Learning-Based Anomaly Detection Systems”](pdfs/ISSTA2019.pdf), in the International Symposium on Software Testing and Analysis (**ISSTA**), 2019, pp. 158-168. **Distinquished artifact award**.

Renaud Rwemalika, Marinos Kintis, Mike Papadakis, Yves Le Traon and Pierre Lorrach. [“On the Evolution of Keyword-Driven Test Suites”](pdfs/ICST2019.pdf), in the 12th International Conference on Software Testing (**ICST**), 2019, pp. 335-345.

Rohan Padhye, Caroline Lemieux, Koushik Sen, Mike Papadakis and Yves Le Traon. [“Validity fuzzing and parametric generators for effective random testing”](https://mpapad.github.io/Publications/), in the 41st International Conference on Software Engineering (**ICSE-poster**), track, 2019, pp. 266-267.

## 2018

Xavier Devroey, Gilles Perrouin, Mike Papadakis, Axel Legay, Pierre-Yves Schobbens and Patrick Heymans. [“Model-based mutant equivalence detection using automata language equivalence and simulations”](pdfs/JSS2018.pdf), in Journal of Systems and Software (**JSS**), vol. 141, 2018, pp. 1-15.

Jabier Martinez, Tewfik Ziadi, Mike Papadakis, Tegawende F. Bissyande, Jacques Klein, Yves le Traon, [“Benchmark for feature location techniques using Eclipse variants”](pdfs/IST2018.pdf), in Information & software Technology Journal (**IST**), vol. 104, 2018, pp. 46-59.

Marinos Kintis, Mike Papadakis, Andreas Papadopoulos, Evangelos Valvis, Nicos Malevris and Yves Le Traon. [“How Effective Mutation Testing Tools Are? An Empirical Analysis of Java Mutation Testing Tools with Manual Analysis and Real Faults”](pdfs/EMSE2018.pdf), in Empirical Software Engineering Journal (**EMSE**), vol. 23, no. 4, 2018, pp. 2426-2463.

Marinos Kintis, Mike Papadakis, Yue Jia, Nicos Malevris, Yves Le Traon, and Mark Harman, [“Detecting Trivial Mutant Equivalences via Compiler Optimisations”](pdfs/TSE2018.pdf), in IEEE Transactions on Software Engineering Journal (**TSE**), vol. 44, no. 4, 2018, pp. 308-333.

Mike Papadakis, Donghwan Shin, Shin Yoo and Doo-Hwan Bae, [“Are Mutation Scores Correlated with Real Fault Detection? A Large Scale Empirical study on the Relationship Between Mutants and Real Faults”](pdfs/ICSE2018.pdf), in the 40th International Conference on Software Engineering (**ICSE**), 2018, pp. 537-548.

Michael Marcozzi, Sebastien Bardin, Nikolai Kosmatov, Mike Papadakis, Virgile Prevosto and Loc Correnson, [“Time to Clean your Test Objectives”](pdfs/ICSE2018B.pdf), in the 40th International Conference on Software Engineering (**ICSE**), 2018, pp. 456-467.

Mike Papadakis, Titcheu Chekam Thierry and Yves Le Traon, [“Mutant Quality Indicators”](pdfs/MUTATION2018.pdf), in the 13th International Workshop on Mutation Analysis (**MUTATION**), ICST Workshops 2018, pp. 32-39.

Matthieu Jimenez, Maxime Cordy, Yves Le Traon and Mike Papadakis. [“On the Impact of Tokenizer and Parameters on N-Gram Based Code Analysis”](pdfs/ICSME2018.pdf), in the International Conference on Software Maintenance and Evolution (**ICSME**), 2018, pp. 437-448.

Matthieu Jimenez, Titcheu Chekam Thierry, Marinos Kintis, Maxime Cordy, Mike Papadakis, Yves Le Traon and Mark Harman. [“Are mutants really natural? A study on how ‘naturalness’ helps mutant selection”](pdfs/ESEM2018.pdf), in the International Symposium on Empirical Software Engineering and Measurement (**ESEM**) 2018, pp. 3:1-3:10.

Florian Delavernhe, Takfarinas Saber, Mike Papadakis and Anthony Ventresque. [“A Hybrid Algorithm for Multi-objective Test Case Selection in Regression Testing”](pdfs/CEC2018.pdf), in the IEEE Congress on Evolutionary Computation (**CEC**) 2018, pp. 1-8.

Matthieu Jimenez, Yves Le Traon and Mike Papadakis. [“Enabling the Continous Analysis of Security Vulnerabilities with VulData7”](pdfs/SCAM2018.pdf), in the 18th IEEE International Working Conference on Source Code Analysis and Manipulation, (**SCAM**), (Engineering Track) 2018, pp. 56-61.

Matthieu Jimenez, Maxime Cordy, Yves Le Traon and Mike Papadakis. [“TUNA: TUning Naturalness-based Analysis”](pdfs/ICSME2018-Artifact.pdf), in the International Conference on Software Maintenance and Evolution (**ICSME**), (Artifacts) 2018, pp. 715.

Thierry Titcheu Chekam, Mike Papadakis, Tegawende Bissyande and Yves Le Traon. [“Poster: Predicting the Fault Revelation Utility of Mutants”](pdfs/ICSE2018-Poster.pdf), in the 40th International Conference on Software Engineering (**ICSE**), poster track, 2018, pp. 408-409.

Renaud Rwemalika, Marinos Kintis, Mike Papadakis and Yves Le Traon. [“Can we automate away the main challenges of end-to-end testing?”](pdfs/BENEVOL2018.pdf), in the 17th Belgium-Netherlands Software Evolution Workshop (**BENEVOL**), 2018.

## 2017

Li Li, Tegawende F. Bissyande, Mike Papadakis, Siegfried Rasthofer, Alexandre Bartel, Damien Octeau, Jacques Klein, and Yves Le Traon, [“Static Analysis of Android Apps: A Systematic Literature Review”](pdfs/IST2017.pdf), in Information & Software Technology journal (**IST**), vol. 88, 2017 pp. 67-95.

Titcheu Chekam Thierry, Mike Papadakis, Yves Le Traon and Mark Harman, [“Empirical Study on Mutation, Statement and Branch Coverage Fault Revelation that Avoids the Unreliable Clean Program Assumption”](pdfs/ICSE2017.pdf), in the 39th International Conference on Software Engineering (**ICSE**), 2017, pp. 597-608.

Xavier Devroey, Gilles Perrouin, Mike Papadakis, Axel Legay, Pierre-Yves Schobbens and Patrick Heymans. [“Automata Language Equivalence vs. Simulations for Model-based Mutant Equivalence: An Empirical Evaluation”](pdfs/ICST2017b.pdf), in the 10th IEEE International Conference on Software Testing, Verification and Validation (**ICST**), 2017, pp. 424-429.

Thomas Laurent, Mike Papadakis, Marinos Kintis, Christopher Henard, Yves Le Traon and Anthony Ventresque. [“Assessing and Improving the Mutation Testing Practice of PIT”](pdfs/ICST2017.pdf), in the 10th IEEE International Conference on Software Testing, Verification and Validation (**ICST**), 2017, 430-435.

Thomas Loise, Xavier Devroey, Gilles Perrouin, Mike Papadakis and Patrick Heymans. [“Towards Security-aware Mutation Testing”](pdfs/Mutation2017.pdf), in the 12th International Workshop on Mutation Analysis (**MUTATION**), 2017, pp. 97-102.

## 2016

Mike Papadakis, Christopher Henard, Mark Harman, Yue Jia, and Yves Le Traon. [“Threats to Validity of Mutation-Based Test Assessment”](pdfs/ISSTA2016.pdf), in the International Symposium on Software Testing and Analysis (**ISSTA**), 2016, pp. 354-365.

Henry Coles, Thomas Laurent, Christopher Henard, Mike Papadakis, Anthony Ventresque. [“PIT a Practical Mutation Testing Tool for Java (Demo)”](pdfs/ISSTA-tool2016.pdf), in the International Symposium on Software Testing and Analysis (**ISSTA**), 2016, pp. 449-452.

Christopher Henard, Mike Papadakis, Mark Harman, Yue Jia, and Yves Le Traon. [“Comparing White-box and Black-box Test Prioritization”](pdfs/ICSE2016.pdf), in the 38th International Conference on Software Engineering (**ICSE**), 2016, pp. 523-534.

Xavier Devroey, Gilles Perrouin, Mike Papadakis, Axel Legay, Pierre-Yves Schobbens and Patrick Heymans. [“Featured Model-based Mutation Analysis”](pdfs/ICSE2016B.pdf), in the 38th International Conference on Software Engineering (**ICSE**), 2016, pp. 655-666.

Matthieu Jimenez, Mike Papadakis and Yves Le Traon. [“Vulnerability Prediction Models: A case study on the Linux Kernel”](pdfs/SCAM2016.pdf), in 16th IEEE International Working Conference on Source Code Analysis and Manipulation (**SCAM**), 2016, pp. 1-10.

Marinos Kintis, Mike Papadakis, Andreas Papadopoulos, Evangelos Valvis and Nicos Malevris. [“Analysing and Comparing the Effectiveness of Mutation Testing Tools: A Manual Study”](pdfs/SCAM2016B.pdf), in 16th IEEE International Working Conference on Source Code Analysis and Manipulation (**SCAM**), 2016 pp. 147-156. **Best paper award**.

Matthieu Jimenez, Mike Papadakis, Tegawende F. Bissyande, and Jacques Klein, [“Profiling Android Vulnerabilities”](pdfs/QRS2016.pdf), in International Conference on Software Quality, Reliability and Security (**QRS**), 2016, pp. 222-229.

Matthieu Jimenez, Mike Papadakis and Yves Le Traon. [“An Empirical Analysis of Vulnerabilities in OpenSSL and the Linux Kernel”](pdfs/APSEC2016.pdf), in 23rd Asia-Pacific Software Engineering Conference (**APSEC**), 2016, pp. 105-112.

Jabier Martinez, Tewfik Ziadi, Mike Papadakis, Tegawende. F Bissyande, Jacques Klein and Yves Le Traon. [“Feature Location Benchmark for Software Families using Eclipse Community Releases”](pdfs/ICSR2016.pdf), in the 15th International Conference on Software Reuse (**ICSR**), 2016, pp. 267-283.

Francisco Carlos M. Souza, Mike Papadakis, Yves Le Traon and Marcio Eduardo Delamaro. [“Strong Mutation-Based Test Data Generation using Hill Climbing”](pdfs/SBST2016.pdf), in the 9th International Workshop on Search-Based Software Testing (**SBST**), 2016, pp. 45-54.

## 2015

Marinos Kintis, Mike Papadakis, and Nicos Malevris, [“Employing Second Order Mutation for Isolating First Order Equivalent Mutants”](pdfs/STVR2015-EQ.pdf), in Software Testing, Verification and Reliability Journal (**STVR**), vol. 25, no. 5-7, 2015, pp. 508-535.

Mike Papadakis and Yves Le Traon, [“Metallaxis-FL: Mutation-based Fault Localization”](pdfs/STVR2015.pdf), in Software Testing, Verification and Reliability Journal (**STVR**), vol. 25, no. 5-7, 2015, pp. 605-628.

Antonia Bertolino, Said Daoudagh, Donia El Kateb, Christopher Henard, Yves Le Traon, Francesca Lonetti, Eda Marchetti, Tejeddine Mouelhi, and Mike Papadakis, [“Similarity Testing for Access-Control”](pdfs/ist2015.pdf), in Information & Software Technology journal (**IST**), vol. 58, 2015, pp. 355372.

Mike Papadakis, Yue Jia, Mark Harman, and Yves Le Traon. [“Trivial Compiler Equivalence: A Large Scale Empirical Study of a Simple, Fast and Effective Equivalent Mutant Detection Technique”](pdfs/ICSE2015B.pdf), in the 37th International Conference on Software Engineering (**ICSE**), 2015, pp. 936-946.

Christopher Henard, Mike Papadakis, Mark Harman, and Yves Le Traon. [“Combining Multi-Objective Search and Constraint Solving for Configuring Large Software Product Lines”](pdfs/ICSE2015A.pdf), in the 37th International Conference on Software Engineering (**ICSE**), 2015, pp. 517-528.

Sebastien Bardin, Mickal Delahaye, Nikolai Kosmatov, Robin David, Mike Papadakis, Yves Le Traon and Jean-Yves Marion. [“Sound and Quasi-Complete Detection of Infeasible Test Requirements”](pdfs/ICST2015.pdf), in the 8th IEEE International Conference on Software Testing, Verification and Validation (**ICST**), 2015, pp. 1-10.

Christopher Henard, Mike Papadakis, Yves Le Traon. [“Flattening or not of the combinatorial interaction testing models?”](pdfs/CIT2015.pdf), in **ICST Workshops** 2015, pp. 1-4.

## 2014

Christopher Henard, Mike Papadakis, Gilles Perrouin, Jacques Klein, Patrick Heymans and Yves Le Traon, [“Bypassing the Combinatorial Explosion: Using Similarity to Generate and Prioritize T-wise Test Configurations for Software Product Lines”](pdfs/tse2014.pdf), in IEEE Transactions on Software Engineering Journal (**TSE**), vol. 40, no. 7, 2014, pp. 650-670.

Mike Papadakis, Marcio Delamaro and Yves Le Traon, [“Mitigating the Effects of Equivalent Mutants with Mutant Classification Strategies”](pdfs/SCP2014.pdf), in Science of Computer Programming Journal (**SCP**), vol. 95, 2014, pp. 298-319.

Christopher Henard, Mike Papadakis and Yves Le Traon. [“Mutation-based Generation of Software Product Line Test Configurations”](pdfs/ssbse14.pdf), in Symposium on Search-Based Software Engineering (**SSBSE**), 2014, pp. 92-106.

Mike Papadakis, Christopher Henard, and Yves Le Traon, [“Sampling Program Inputs with Mutation Analysis: Going Beyond Combinatorial Interaction Testing”](pdfs/icst2014-CITMUT.pdf), in Software Testing, Verification, and Validation, International Conference on (**ICST**), 2014, pp. 1-10.

Mike Papadakis and Yves Le Traon, [“Effective Fault Localization via Mutation Analysis: A Selective Mutation Approach”](pdfs/sac2014-FL.pdf), in 29th ACM Symposium On Applied Computing (**SAC**), 2014, pp. 1293-1300.

Tewfik Ziadi, Christopher Henard, Mike Papadakis, Yves Le Traon and Mikal Ziane, [“Towards a Language-Independent Approach for Reverse-Engineering of Software Product Lines”](pdfs/sac2014-extractorpl.pdf), in 29th ACM Symposium On Applied Computing (**SAC**), 2014, 1064-1071.

Francisco Carlos Souza, Mike Papadakis, Vincius Durelli and Marcio Eduardo Delamaro. [”Techniques for Test Data Generation for Mutation Testing: A Systematic Mapping”](pdfs/eselaw2014.pdf), in the XVII Ibero-American Conference on Software Engineering (**CIBSE**), 2014, pp. 419-432.

Christopher Henard, Mike Papadakis and Yves Le Traon. [“MutaLog: a Tool for Mutating Logic Formulas”](pdfs/icst2014_MUTLOG.pdf), in 7th International Conference on Software Testing, Verification and Validation Workshops (**ICSTW**), 2014, pp. 399-404.

Xavier Devroey, Gilles Perrouin, Maxime Cordy, Mike Papadakis, Axel Legay, and Pierre-Yves Schobbens. [“A Variability Perspective of Mutation Analysis”](pdfs/fse14vc_vcid11_Devroey_VariabilityPerspectiveMutation.pdf), in 22nd ACM SIGSOFT International Symposium on the Foundations of Software Engineering (**FSE**), Visions and Challenges track, 2014, pp. 841-844.

## 2013

Christopher Henard, Mike Papadakis, Gilles Perrouin, Jacques Klein and Yves Le Traon. [“Multi-objective Test Generation for Software Product Lines”](pdfs/SPLC2013.pdf), in 17th ACM International Conference on Software Product Lines (**SPLC**), 2013, pp. 62-71.

Christopher Henard, Mike Papadakis, Gilles Perrouin, Jacques Klein and Yves Le Traon. [“Towards Automated Testing and Fixing of Re-engineered Feature Models”](pdfs/icse13nier-id30-p-15773-preprint.pdf), in 35th International Conference on Software Engineering (**ICSE**), New Ideas and Emerging Results track, 2013, pp. 1245-1248.

Mike Papadakis and Yves Le Traon, [“Mutation Testing Strategies using Mutant Classification”](pdfs/Sac2013.pdf), in 28th ACM Symposium On Applied Computing (**SAC**), 2013, pp. 1223-1229.

Christopher Henard, Mike Papadakis, Gilles Perrouin, Jacques Klein and Yves Le Traon. [“Assessing software product line testing via model-based mutation: An application to similarity testing”](pdfs/AMOST2013.pdf), in the 9th Workshop on Advances in Model Based Testing (**A-MOST**), ICST Workshops 2013 pp. 188-197.

Mike Papadakis and Nicos Malevris. [“Searching and generating test inputs for mutation testing”](https://springerplus.springeropen.com/track/pdf/10.1186/2193-1801-2-121.pdf), in **SpringerPlus** Journal, vol. 2, 2013, pp. 121.

Phu H. Nguyen, Mike Papadakis and Iram Rubab. [“Testing Delegation Policy via Mutation Analysis”](pdfs/Mutation2013.pdf), in the 8th International Workshop on Mutation Analysis (**MUTATION**), ICST Workshops 2013, pp. 34-42.

Mike Papadakis, Marcio Delamaro and Yves Le Traon, [“Proteum/FL: a Mutation-based Fault Localization Tool”](pdfs/ScamTool2013.pdf), in 13th IEEE International Working Conference on Source Code Analysis and Manipulation (**SCAM**), 2013, pp. 85-90.

Christopher Henard, Mike Papadakis, Gilles Perrouin, Jacques Klein and Yves Le Traon. [“PLEDGE: A Product Line Editor and Test Generation Tool”](pdfs/splc2013Tool.pdf), in 17th International Conference on Software Product Lines (**SPLC**) 2013, pp. 126-129.

## 2012

Mike Papadakis and Nicos Malevris, [“Mutation based test case generation via a path selection strategy”](pdfs/IST2012.pdf), Information & Software Technology journal (**IST**), vol. 54, no. 9, 2012, pp. 915-932.

Marinos Kintis, Mike Papadakis, and Nicos Malevris, [“Isolating First Order Equivalent Mutants via Second Order Mutation”](http://www0.cs.ucl.ac.uk/mutation2012/papers/4670a701.pdf), in Software Testing, Verification, and Validation, International Conference on (**ICST**), 2012, pp. 701-710.

Mike Papadakis and Yves Le Traon, [“Using Mutants to Locate ‘Unknown’ Faults”](http://www0.cs.ucl.ac.uk/mutation2012/papers/4670a691.pdf), in Software Testing, Verification, and Validation, International Conference on (**ICST**), 2012, pp. 691-700.

# 2011

Mike Papadakis and Nicos Malevris. [“Automatically Performing Weak Mutation with the Aid of: Symbolic Execution, Concolic and Search Based Testing”](pdfs/SQJ2011.pdf), in Software Quality Journal (**SQJ**), vol. 19, no. 4, 2011, pp. 691-723.

Mike Papadakis and Nicos Malevris. [“Automatic Mutation based Test Data Generation”](pdfs/Gecco2011.pdf), in Annual conference on Genetic and evolutionary computation, (**GECCO**), 2011, pp. 247-248.

## 2010

Mike Papadakis and Nicos Malevris. [“Automatic Mutation Test Case Generation Via Dynamic Symbolic Execution”](pdfs/ISSRE2010.pdf), in 21st International Symposium on Software Reliability Engineering (**ISSRE**) 2010, pp.121-130.

Marinos Kintis, Mike Papadakis and Nicos Malevris. [“Evaluating Mutation Testing Alternatives: A Collateral Experiment”](pdfs/apsec2010.pdf), in 17th Asia-Pacific Software Engineering Conference (**APSEC**), 2010, pp. 300-309.

Mike Papadakis and Nicos Malevris. [“A Symbolic Execution Tool Based on the Elimination of Infeasible Paths”](pdfs/icsea2010.pdf), in Proceedings of the 5th International Conference on Software Engineering Advances (ICSEA’10), 2010, pp. 435-440.

Mike Papadakis, Nicos Malevris and Maria Kallia. [“Towards Automating the Generation of Mutation Tests”](pdfs/AST2010.pdf), in Proceedings of the 5th International Workshop on Automation of Software Test (**AST**), 2010, pp. 111-118.

Mike Papadakis and Nicos Malevris. [“An Empirical Evaluation of the First and Second Order Mutation Testing Strategies”](pdfs/mutation2010.pdf), in Proceedings of the 5th International Workshop on Mutation Analysis (**MUTATION**), 2010, pp. 90-99.

Mike Papadakis, Nicos Malevris and Marinos Kintis. [“Mutation Testing Strategies: A Collateral Approach”](pdfs/ICSOFT2010.pdf), in Proceedings of the 5th International Conference on Software and Data Technologies (**ICSOFT**), 2010, vol.2, pp. 325-328.

## 2009

Mike Papadakis and Nicos Malevris. [“An Effective Path Selection Strategy for Mutation Testing”](pdfs/apsec2009.pdf), in Proceedings of the 16th Asia-Pacific Software Engineering Conference (**APSEC**), 2009, pp. 422-429.

Mike Papadakis and Nicos Malevris. [“Improving Evolutionary Test Data Generation with the Aid of Symbolic Execution”](pdfs/AIAI2009.pdf), in Proceedings of the 2nd International Workshop on Artificial Intelligence Techniques in Software Engineering (**AISEW**), 2009, pp. 201-210.




## Additional Material
Further details about my work can be found in my [DBLP](https://dblp.org/pid/00/7677.html) and [Google Scholar](https://scholar.google.com/citations?user=4O3EolUAAAAJ) pages.    

## Disclaimer
This page contains personal archived (pre-print versions) articles published by IEEE, ACM, Elsevier, Springer, Wiley and other publishers. Copyright and all rights therein are retained by authors or by other copyright holders. Personal use of this material is permitted. However, permission to reprint/republish this material for advertising or promotional purposes or for creating new collective works for resale or redistribution to servers or lists, or to reuse any copyrighted component of this work in other works, must be obtained from the copyright holder.
