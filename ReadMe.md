# FDToolBox_Ver0.9 Description
## Quick Start：
1. first Add all folders and subfolders to the working directory
2. second run Demo_***Dataset.m
## Original intention：
1. For beginner: 想了解数据驱动的故障诊断这一研究方向的科研人员，快速入门，了解现有方法。
2. For researcher: 为新方法的研究提供对比方法基准、数据基准，避免重复工作，提高对比结果的科学性和可信度。
3. For non-specialist: 非故障诊断研究领域人员快速上手、快速验证能否适用于自己要解决的问题。
## Content：
### 该工具箱目前仅包含部分故障检测方法代码和验证数据集，具体内容如下：  
1. 基于PCA的故障检测方法[1] Qin S J.Statistical process monitoring: basics and beyond[J].Journal of Chemometrics,2003, 17 (8-9): 480-502.
2. 基于ICA的故障检测方法[2] Lee J-M, Qin S J, Lee I-B.Fault detection and diagnosis based on modified independent component analysis[J].AIChE Journal,2006, 52 (10): 3501-3514.
3. 基于KPCA的故障检测方法[3] Cho J H, Lee J M, Choi S W, et al.Fault identification for process monitoring using kernel principal component analysis[J].Chemical Engineering Science,2005, 60 (1): 279-288.  
4. 基于GMM的故障检测方法 未发表.
5. 基于SVDD的故障检测方法[4] Du W Y, Zhou W.An Intelligent Fault Diagnosis Architecture for Electrical Fused Magnesia Furnace Using Sound Spectrum Submanifold Analysis[J].IEEE Transactions on Instrumentation and Measurement,2018, 67 (9): 2014-2023. 
6. 基于GDT的故障检测方法[5] Du W, Zhang Y, Zhou W.Modified non-Gaussian multivariate statistical process monitoring based on the Gaussian distribution transformation[J].Journal of Process Control,2020, 85: 1-14. 
7. 数据集：chiang的TEP仿真数据集.
8. 数据集：Ricker的Simulink模型生成的TEP仿真数据集（10万个正常数据样本，28种故障数据）
9. 数据集：某民用航空器脱敏数据集。  
## References：
###工具箱中引用和借鉴了一些优秀的工具箱和公开代码，作者尽力提供最原始的出处，这些工具箱和方法包括：
1. FastICA 工具箱：[1] Hyvärinen A.Independent component analysis: recent advances[J].Philosophical transactions. Series A, Mathematical, physical, and engineering sciences,2013, 371 (1984): 20110534.
2. LibSVM3.22工具箱：[2] Chang C C, Lin C J.LIBSVM: A library for support vector machines[J].ACM Trans. Intell. Syst. Technol.,2011, 2 (3): 1-27.
## Author list:  
该工具箱由沈阳航空航天大学自动化学院故障诊断课题组开发，该版本开发成员：杜文友、杨峻培、张浩然、王乙臣、翟广宇。  数据驱动的故障诊断这一研究领域优秀成果众多，限于作者能力，在经过多年学习后也仅仅了解了一些基础方法，仅供后来学者参考。工具箱中代码难免有错误和疏漏之处，欢迎碰巧打开此文档的您不吝提出宝贵的意见和建议（邮箱：wen-you.du@sau.edu.cn）。 
