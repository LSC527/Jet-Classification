# Jet-Classification
https://www.biendata.com/competition/jet/

reduce_mem 减小原始数据大小，并存储为feather格式  
  
lightgbm:  
feature + model_lgb 老特征  
new_feature + new_model_lgb 新特征  
new_feature_jet_level + new_model_jet_level 新特征jet_level样本  
  
particlenet:  
运行顺序 trans → trans1 → trans2 → trans3+train
