# Kaggle-Prj-March_Machine_Learning_Mania_2021-NCAAW
Kaggle-Prj-March_Machine_Learning_Mania_2021-NCAAW

-------

# Timeline
All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. 

## Stage 1 - Model Building
### Sunday, Mar 14 - Prior to this deadline, competitors build and test models on historical data. 

The leaderboard shows the model performance on historical tournament outcomes.



## Stage 2 - Championship
### Monday, Mar 15 - Selection Show® (64 teams announced)
### Tuesday, Mar 16 - Kaggle begins to accept 2021 predictions. 

Release of up-to-date 2020-2021 season data.

### Sunday, Mar 21 3PM UTC - Final deadline to submit 2021 predictions.

### Mar 21 onward - Watch your tournament results play out! 

The Kaggle Team will refresh the leaderboard throughout the competition as games are finalized.



-------

## Evaluation

Submissions are scored on the log loss


-------

## Progress

### Public Best LB Score: 0.42701

### Private Score:



-------

## 2021 NCAAW Basketball Tournament LightGBM

### 'learning_rate': 0.009   default     
                   
      'learning_rate': 0.009    LB 0.44091    ver1    #default
      'learning_rate': 0.01     LB 0.44071    ver2
      'learning_rate': 0.011    LB 0.44169    ver6
      'learning_rate': 0.015    LB 0.44207    ver3
      'learning_rate': 0.011    LB 0.44169    ver4

### 'num_leaves': 32

'learning_rate': 0.01:

      'num_leaves': 16     LB 0.44171    ver7
      'num_leaves': 32     LB 0.44071    ver2
      'num_leaves': 64     LB 0.44071    ver5
      'num_leaves': 128    LB 0.44071    ver9


-------

## NCAAW 2021 - LGB w/ FE on three Datasets
https://www.kaggle.com/tnmasui/ncaaw-2021-lgb-w-fe-on-three-datasets


### 'learning_rate': 0.05   #default


      'learning_rate': 0.06     LB 0.44590    ver3
      'learning_rate': 0.05     LB 0.44527    ver1     #default
      'learning_rate': 0.04     LB 0.44321    ver4
      'learning_rate': 0.03     LB 0.44419    ver5     
      'learning_rate': 0.01     LB 0.50073    ver2


-------

## 2021-NCAAW-Basketball-LightGBM-2

### 'learning_rate': 0.05   #default

      'learning_rate': 0.08     LB 0.44012     ver5
      'learning_rate': 0.071    LB 0.43944     ver6   --- Best
      'learning_rate': 0.07     LB 0.43946     ver4
      'learning_rate': 0.06     LB 0.43964     ver3
      'learning_rate': 0.05     LB 0.43994     ver1     #default
      'learning_rate': 0.04     LB 0.44064     ver2
           
  
-------  
  
## NCAA W 2021 | Linear Regression
  
      Public Score: 0.42701



-------

## NCAAW-ModelBuild


### N_SPLITS = 10

      N_SPLITS = 10     LB 0.42428     ver1
      N_SPLITS = 14     LB 0.42430     ver4
      N_SPLITS = 15     LB 0.42034     ver2   --- Best
      N_SPLITS = 20     LB 0.42195     ver3


-------

## 2021 NCAAW First Step V.2
https://www.kaggle.com/svyatoslavsokolov/2021-ncaaw-first-step-v-2


       Public Score: 0.44855    ver1

n_splits=10:

       Public Score: 0.40738    ver2
       Public Score: 0.41068    ver3
       Public Score: 0.41580    ver4
       Public Score: 0.40634    ver5

### kf = KFold(n_splits=10, shuffle=True)
kf = KFold(n_splits=12, shuffle=True)

      n_splits= 8          LB 0.46692     ver7
      n_splits= 9          LB 0.44017     ver8
      n_splits=10          LB 0.40634     ver5
      n_splits=11          LB 0.40124     ver9   --- (Best)
      n_splits=12          LB 0.53842     ver6

n_splits=11:

      Public Score: 0.40124     ver9   --- (Best)
      Public Score: 0.41283     ver10


### early_stopping_rounds = 100
                  
n_splits=11:

      early_stopping_rounds = 100     LB 0.40124     ver9
      early_stopping_rounds = 150     LB 0.42256     ver14
      early_stopping_rounds = 200     LB 0.40087     ver11   --- Best
      early_stopping_rounds = 225     LB 0.41897     ver15
      early_stopping_rounds = 250     LB 0.39294     ver13
      early_stopping_rounds = 300     LB 0.42062     ver12
      
      
      
-------

## 2019M 1st Solution (With parameter optimization)
https://www.kaggle.com/imoore/2019m-1st-solution-with-parameter-optimization


### max_depth = 4)

       max_depth = 4      LB 0.42062     ver1
       max_depth = 8      LB 0.35872     ver3
       max_depth = 12     LB 0.35608     ver4     
       max_depth = 14     LB 0.35600     ver9
       max_depth = 15     LB 0.35599     ver10
       max_depth = 16     LB 0.35599     ver5   --- (Best)
       max_depth = 20     LB 0.35599     ver6
       max_depth = 24     LB 0.35599     ver7




### num_parallel_tree = 10,

max_depth = 16:
       
       num_parallel_tree = 10  LB 0.35599     ver5
       num_parallel_tree = 11  LB      ver
       num_parallel_tree = 12  LB 0.35413     ver11   --- Best
       num_parallel_tree = 13  LB 0.35469     ver13
       num_parallel_tree = 14  LB 0.35585     ver12
       
       
       
       
-------



