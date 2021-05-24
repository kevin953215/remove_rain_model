# remove_rain_model
This model still needs to be modified and more training data should be added

此模型為利用GAN生成技術來去除雨水痕跡,但目前我的(模型參數量/training data參數量)約等於0.522544975,應該降至0.25以內較佳,我只是提供一個簡易成形的model歡迎自行更改,我認為修改方式應為增加更多的training data,ex:若照片採用224x224x1至少應採用約600張照片來訓練。或著修改layer數量並加入batch normalization應該也會有不錯的效果


進階修改方式:亦可以參考許多論文都有用到的技術【CGAN】會有更佳優秀的效果,但模型和loss function要自行重建


訓練資料集可上網搜尋BSD300


PS:此處照片我將其分解為YUV channel並取Y channel來做training
