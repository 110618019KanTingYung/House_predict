# House_predict
machine learning house prodict
requirement.txt :環境的安裝需求
機器學習-房價預測報告.pptx:有詳細程序介紹
1.先從google drive載入資料，並用pandas讀取csv檔
2.視覺化及觀察格特徵與價錢之間的相關性，並替除掉相關性低的特徵
3.對資料進行標準化，避免各特徵資料的數值差異過大，導致訓練結果不佳
4.使用keras的Sequential建立模型
5.利用X_train,Y_train進行訓練，使用X_valid, Y_valid進行驗證
6.並將訓練中的loss,valid_loss印出來，方便觀察模型的學習情況
7.最後再將X_test放進模型中進行預測
8.將預測結果以csv檔形式儲存，方便上傳至kaggle評分
