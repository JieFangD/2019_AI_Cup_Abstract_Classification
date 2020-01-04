# [2019_AI_CUP_Abstract_Classification](https://tbrain.trendmicro.com.tw/Competitions/Details/9)

## Competition Description
In this task, we are given a set of papers from arXiv. Given title, abstract, author, category, and date from paper, we are asked to predict the paper's type in four classes: theoretical paper, engineering paper, empirical paper, or others, where the paper can belong to multiple classes.

## Score
 Team Name: SDML_AndyIsMyBoss
 
 Public Score:
  - 0.725234 (Rank:4/420)
  
 Private Score:
  - 0.747832 (Rank:2/420)

## Data and File Decription
  Training data: 
  - data/task2_trainset.csv
  
  Testing data: 
  - data/task2_public_testset.csv 
  - data/task2_private_testset.csv
  
  Sample submission data: 
  - data/task2_sample_submission.csv 
  
  Train File
  - src/Training (SciBert-DNN).ipynb
  
  Test File
  - src/Testing.ipynb

  Boost File
  - src/Boost.ipynb

  Well-trained Model
  - src/well-trained-model

## How to Reproduce Results?
1. Download [Scibert](https://s3-us-west-2.amazonaws.com/ai2-s2-research/scibert/pytorch_models/scibert_scivocab_uncased.tar) model
2. You can train by yourself through "Training (SciBert-DNN).ipynb" or utilize the provided well-trained model
3. Use "Testing.ipynb" to predict testing data
4. Boost all the results to improve prediction accuracy
5. For more details, please refer to the provided [presentation](https://github.com/JieFangD/2019_AI_Cup_Abstract_Classification/blob/master/Presentation.pdf) and [report](https://github.com/JieFangD/2019_AI_Cup_Abstract_Classification/blob/master/Report.pdf) files

## Contact Information

   ```
Chieh-Fang Teng:
        + jeff@access.ee.ntu.edu.tw
        + d06943020@ntu.edu.tw
Yi-Ta Chen:
        + edan@access.ee.ntu.edu.tw
        + d06943017@ntu.edu.tw
   ```
