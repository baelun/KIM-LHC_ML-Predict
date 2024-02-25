# KIM-LHC_ML-Predict	
> 以Joint Angle作為模型Input，比較多類別常使用之三種ML module進行預測之績效，得出最佳模型
### Model training & testing ######
  * 經由REC認證所蒐取之人體姿態數據進行frame cutting
  * 以每項frame所得出之joint angle進行姿態類別標籤
  * 將資料集分為train.csv與test.csv，經由one-hot-encoding等資料前處理後，轉化為X_train,X_test,Y_train,Y_test做訓練資料集
  * 使用 AI argrithm XGBoost、GBM、KNN進行最佳化參數調整與訓練得出績效最高模型
### Application ######
  * Combine with a website (Python-Flask based)
