# Kaggle-Prj-March_Machine_Learning_Mania_2021-NCAAM
Kaggle-Prj-March_Machine_Learning_Mania_2021-NCAAM


-------

# Timeline
All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. 

## Stage 1 - Model Building
### Saturday, Mar 13 - Prior to this deadline, competitors build and test models on historical data. 

The leaderboard shows the model performance on historical tournament outcomes.



## Stage 2 - Championship
### Sunday, Mar 14 - Selection Sunday® (68 teams announced)
### Monday, Mar 15 - Kaggle begins to accept 2021 predictions. 

Release of up-to-date 2020-2021 season data.

### Friday, Mar 19 3PM UTC - Final deadline to submit 2021 predictions.

### Mar 19 onward - Watch your tournament results play out! 

The Kaggle Team will refresh the leaderboard throughout the competition as games are finalized.



-------

## Evaluation

Submissions are scored on the log loss



-------

## Progress

### Public Best LB Score: 0.50225

### Private Score:

-------

## NCAAM 2021 - LGB w/ FE on three Datasets

### 'learning_rate': 0.05   ##default

      'learning_rate': 0.07    LB  0.52867   ver4
      'learning_rate': 0.06    LB  0.52605   ver6
      'learning_rate': 0.055   LB  0.52225   ver7
      'learning_rate': 0.051   LB  0.52589   ver9
      'learning_rate': 0.05    LB  0.51968   ver2    ##default
      'learning_rate': 0.049   LB  0.52290   ver10
      'learning_rate': 0.045   LB  0.52179   ver8
      'learning_rate': 0.04    LB  0.52425   ver5
      'learning_rate': 0.01    LB  0.55852   ver3             
              
 -------             
              
 ## Massey's ordinals, Massey's ordinals-2            


      sub_df[['ID', 'Pred']].to_csv('s float_format='%.3g')     LB  0.51571   ver1 
      sub_df[['ID', 'Pred']].to_csv('s float_format='%.4g')     LB  0.51569   ver2 
      sub_df[['ID', 'Pred']].to_csv('s float_format='%.5g')     LB  0.51569   ver4   --- Best -> 42
      sub_df[['ID', 'Pred']].to_csv('s float_format='%.8g')     LB  0.51569   ver5
      
      sub_df[['ID', 'Pred']].to_csv('s float_format='%.16g')     LB  0.51569   ver6, ver7 
      
 -------     
  
 ## 2021 NCAAM First Step 
 https://www.kaggle.com/svyatoslavsokolov/2021-ncaam-first-step
 
n_splits=10:

      LB: 0.50754     ver1
      LB: 0.50708     ver2
      LB: 0.52465     ver3
      LB: 0.51593     ver4
      LB: 0.51512     ver5
      LB: 0.50225     ver6   --- Best
      LB: 0.51415     ver7
      LB: 0.52401     ver8
      
### kf = KFold(n_splits=10, shuffle=True)

      n_splits= 8        LB: 0.54551     ver10
      n_splits= 9        LB: 0.50993     ver11
      n_splits=10        LB: 0.50225     ver6   --- Best
      n_splits=11        LB: 0.50447     ver12
      n_splits=12        LB: 0.63946     ver9

n_splits=11:

      LB: 0.50447     ver12
      LB: 0.50843     ver13
      LB: 0.59928     ver14
      LB: 0.53396     ver15


### early_stopping_rounds = 100

n_splits=10:

      early_stopping_rounds = 100    LB: 0.50225     ver6   --- Best
      early_stopping_rounds = 200    LB: 0.50731     ver16
      early_stopping_rounds = 300    LB: 0.51671     ver17


 -------
 
## 2019 1st Solution (With parameter optimization)
https://www.kaggle.com/imoore/2019-1st-solution-with-parameter-optimization 

      
### early_stopping_rounds = 25

      early_stopping_rounds = 25        LB: 0.47176    ver1
      early_stopping_rounds = 50        LB: 0.47176    ver2
      early_stopping_rounds = 100       LB: 0.47176    ver3

### max_depth = 4

early_stopping_rounds = 25:

      max_depth = 4       LB: 0.47176    ver1
      max_depth = 8       LB: 0.43349    ver4
      max_depth = 12      LB: 0.42729    ver5
      max_depth = 14      LB: 0.42714    ver9
      max_depth = 15      LB: 0.42695    ver11
      max_depth = 16      LB: 0.42676    ver6   --- Best
      max_depth = 17      LB: 0.42678    ver10
      max_depth = 18      LB: 0.42679    ver8
      max_depth = 20      LB: 0.42679    ver7
      
      
      
### num_parallel_tree = 10

max_depth = 16

      num_parallel_tree = 8      LB: 0.42849    ver14
      num_parallel_tree = 9      LB: 0.42741    ver15
      num_parallel_tree = 10     LB: 0.42676    ver6   --- Best
      num_parallel_tree = 11     LB: 0.42836    ver16      
      num_parallel_tree = 12     LB: 0.42928    ver13
      
      
      
      
      
      
       
       
-------



       

