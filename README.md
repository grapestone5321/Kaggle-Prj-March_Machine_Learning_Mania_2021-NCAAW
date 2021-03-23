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
       num_parallel_tree = 11  LB 0.35404     ver14   --- (Best)
       num_parallel_tree = 12  LB 0.35413     ver11
       num_parallel_tree = 13  LB 0.35469     ver13
       num_parallel_tree = 14  LB 0.35585     ver12
       
       
### min_child_weight = 40,

num_parallel_tree = 11:
      
       min_child_weight =  2      LB 0.23180     ver25   --- (Best)
       min_child_weight =  4      LB 0.24238     ver24
       min_child_weight =  8      LB 0.26539     ver23
       min_child_weight = 12      LB 0.28305     ver22
       min_child_weight = 16      LB 0.29529     ver21
       min_child_weight = 20      LB 0.30797     ver20
       min_child_weight = 24      LB 0.32040     ver19
       min_child_weight = 28      LB 0.33273     ver18
       min_child_weight = 32      LB 0.34291     ver17
       min_child_weight = 36      LB 0.35069     ver16
       min_child_weight = 40      LB 0.35404     ver14
       min_child_weight = 44      LB 0.36103     ver15

### gamma = 10

min_child_weight =  2:

       gamma = 10          LB 0.23180     ver25   --- (Best)
       gamma = 12          LB 0.23186     ver26
       
### eta = 0.02

min_child_weight =  2, gamma = 10, subsample = 0.7
       
       eta = 0.02         LB 0.23180     ver25   --- (Best)
       eta = 0.04         LB 0.23207     ver27
       eta = 0.1          LB 0.23314     ver28

### subsample = 0.7

eta = 0.02:

       subsample = 0.7     LB 0.23180     ver25   --- (Best)
       subsample = 0.8     LB 0.22896     ver30

eta = 0.04:

       subsample = 0.8     LB 0.22895     ver29
       subsample = 0.9     LB 0.22839     ver31   --- (Best)

subsample = 0.9:
             
       min_child_weight =  1      LB 0.22490     ver32   --- (Best)
       min_child_weight =  2      LB 0.22839     ver31
       
min_child_weight =  1:

       colsample_bytree = 0.5     LB 0.21499     ver33   --- Best
       colsample_bytree = 0.8     LB 0.22490     ver32
       
       
            
-------

### xgb_parameters = 
      list(objective = cauchyobj, 
      eval_metric = "mae",
      booster = "gbtree", 
       
       eta = 0.02,
       eta = 0.04,
       
       subsample = 0.9,
       colsample_bytree = 0.5,       
       num_parallel_tree = 11,       
       min_child_weight = 1,       
       gamma = 10,
       max_depth = 16

-------

      regresults <- read.csv("../input/ncaaw-march-mania-2021/WRegularSeasonDetailedResults.csv")
      results <- read.csv("../input/ncaaw-march-mania-2021/WNCAATourneyDetailedResults.csv")
      sub <- read.csv("../input/ncaaw-march-mania-2021/WSampleSubmissionStage1.csv")
      seeds <- read.csv("../input/ncaaw-march-mania-2021/WNCAATourneySeeds.csv")

-------

## Stage2

      import os
      os.listdir('/kaggle/input/ncaaw-march-mania-2021/WDataFiles_Stage2')


      ['Conferences.csv',
       'WNCAATourneyDetailedResults.csv',
       'WRegularSeasonCompactResults.csv',
       'WGameCities.csv',
       'WNCAATourneySlots.csv',
       'Cities.csv',
       'WTeams.csv',
       'WNCAATourneyCompactResults.csv',
       'WSeasons.csv',
       'WNCAATourneySeeds.csv',
       'WRegularSeasonDetailedResults.csv',
       'WSampleSubmissionStage2.csv',
       'WTeamSpellings.csv',
       'WTeamConferences.csv']

-------

      regresults <- read.csv("../input/ncaaw-march-mania-2021/WDataFiles_Stage2/WRegularSeasonDetailedResults.csv")
      results <- read.csv("../input/ncaaw-march-mania-2021/WDataFiles_Stage2/WNCAATourneyDetailedResults.csv")
      sub <- read.csv("../input/ncaaw-march-mania-2021/WDataFiles_Stage2/WSampleSubmissionStage2.csv")
      seeds <- read.csv("../input/ncaaw-march-mania-2021/WDataFiles_Stage2/WNCAATourneySeeds.csv")


-------

## Stage2

      15 days to go:   LB 0.34893      -> 18


