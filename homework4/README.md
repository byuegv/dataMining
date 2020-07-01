# 数据集
## 1 [wave\_benchmarks](https://ir.library.oregonstate.edu/concern/parent/47429f155/file_sets/jh343z59f)
wave\_benchmarks.zip Public      
File Details    
Depositor Imholt, Sarah     
Date Uploaded 2018-07-12    
Date Modified 2018-07-12  
Fixity Check Fixity checks have not yet been run on this object  
Characterization File Format: zip (ZIP Format)   
Original Checksum: c4979ab004f4b81bba792d08cb2b7969 
Mime Type: application/zip  
## 2 [pageb\_benchmarks](https://ir.library.oregonstate.edu/concern/parent/47429f155/file_sets/1g05fh87w)
pageb\_benchmarks.zip Public    
File Details    
Depositor Imholt, Sarah 
Date Uploaded 2018-07-12    
Date Modified 2018-07-12    
Fixity Check Fixity checks have not yet been run on this object 
Characterization File Format: zip (ZIP Format)  
Original Checksum: b5b0765137a3e3d006520d3fbaa2237a 
Mime Type: application/zip  

# 离群点异常点检测算法/模型
+ 单一数据模型
  - KNN
  - PCA
  - LOF
+ 组合模型
  - Average: average scores of all detectors.
  - maximization: maximum score across all detectors.
  - Average of Maximum (AOM): divide base detectors into subgroups and take the maximum score for each subgroup. The final score is the average of all subgroup scores.
  - Maximum of Average (MOA): divide base detectors into subgroups and take the average score for each subgroup. The final score is the maximum of all subgroup scores.

# 数据挖掘互评作业四：离群点分析与异常检测

1. 问题描述

  本次作业将从Anomaly Detection Meta-Analysis Benchmarks提供的benchmark数据集中任选两个进行分析。

2. 数据来源

  Anomaly Detection Meta-Analysis Benchmarks  
  注意：第一个不是数据集，是用于生成benchmark数据的代码。  
  可以使用Python Outlier Detection (PyOD)或其他已知的工具包来完成分析工作。  

3. 提交的内容

  完整的分析代码  
  分析报告：展示分析的思路，详细过程，结果及你的分析。  
  所选择的数据集在README中说明，数据文件不要上传到Github中  
  乐学平台提交注意事项：  
  仓库地址：记得加上  
  报告：附件，word，pdf，html格式都可以  
