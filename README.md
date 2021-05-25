# dog_dataset
有關於狗的行為辨識資料集，主要類別為站立、坐下、趴下、爭吵、破壞東西等
使用寵物狗來進行行為辨識，預計使用自定義及現有資料集分別做標註進行訓練及測試

＊自定義資料集

目標數量：圖像及影片每楨換算約一萬張
擴增方式：分別對圖像進行隨機旋轉、平移、縮放、裁減、亮度、解析度等方式

＊現有資料集

資料集名稱：Ｇenerative Dog Images

下載連結：https://www.kaggle.com/c/generative-dog-images/data

預計使用方式說明：預計標註後和自定義資料集一起訓練

資料集名稱：Dog Centric Activity Dataset

下載連結：http://robotics.ait.kyushu-u.ac.jp/~yumi/db/first_dog.html

預計使用方式說明：預計標註後和自定義資料集一起訓練

資料集名稱：Stanford Dogs Dataset

下載連結：https://www.kaggle.com/jessicali9530/stanford-dogs-dataset

預計使用方式說明：預計標註後和自定義資料集一起訓練

資料集名稱：Dog Classification

下載連結：https://www.kaggle.com/c/dog-classification/data

預計使用方式說明：預計標註後和自定義資料集一起訓練

資料集名稱：Dog Breed Identification

下載連結：https://www.kaggle.com/c/dog-breed-identification/data

預計使用方式說明：預計標註後和自定義資料集一起訓練


進度規劃：
5/24 - 5/30：進行資料收集及資料標註等預處理，預計使用PASCAL VOC格式進行標註

5/31 - 6/06：進行資料標註的預處理及確定模型架構

6/07 - 6/13：進行模型建立及訓練

6/13 - 6/20：進行訓練參數調整及修正

6/21 - 6/23：進行模型優化及最終部署
