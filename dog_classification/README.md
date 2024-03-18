dog_classification.h5 : cnn model </br>
test_data.xlsx : 最終結果

1.把train,valid,test裡不同資料夾(狗的種類)做label，再把每張照片的尺寸都轉成224*224 </br>
2.轉成numpy的格式並且打亂資料集 </br>

以cnn模型做預測，train acc:0.9732 train loss:0.1225 </br>
                valid acc:0.2671 valid loss:3.4165 </br>
                test acc:0.2771  test loss:3.3662
    
