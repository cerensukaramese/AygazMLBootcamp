# Malicious URLs Dataset Projesi

## Proje Hakkında
Bu proje, zararlı URL'leri tespit etmek için makine öğrenmesi tekniklerinin kullanıldığı bir çalışmadır. Projede, Kaggle'dan alınan **Malicious URLs Dataset** kullanılarak gözetimli ve gözetimsiz öğrenme algoritmaları uygulanmıştır. Amaç, zararlı URL'lerin sınıflandırılması ve analizi ile bu tür URL'lerin tespitine yönelik etkili bir model geliştirmektir.

## Kullanılan Veri Seti
Veri seti, çeşitli zararlı ve zararsız URL'leri içeren bir koleksiyondur. Veri setinin bağlantısı: https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset

## Yöntemler
Proje kapsamında aşağıdaki yöntemler uygulanmıştır:
- **Gözetimli Öğrenme:** Random Forest algoritması kullanılarak model oluşturulmuş ve değerlendirilmiştir.
- **Gözetimsiz Öğrenme:** k-Ortalama kümeleme yöntemi ile veri analizi gerçekleştirilmiştir.

## Model Değerlendirmesi
Model performansı, aşağıdaki metriklerle değerlendirilmiştir:
### RandomForest:
- Doğruluk (Accuracy) : 0.9009757353113227
- Kesinlik (Precision) :0.897792050935436
- Duyarlılık (Recall) :0.9009757353113227
- F1 Skoru : 0.8989708919643451

Ayrıca, sınıflandırma sonuçları için karışıklık matrisi (Confusion Matrix) oluşturulmuştur.
#### Confusion matrix:
![image](https://github.com/user-attachments/assets/4fb50cd1-d984-4326-afe2-39430b88499e)


### K-means:

#### Kümeleme Sonuçları:
![image](https://github.com/user-attachments/assets/470bcfc3-cbb8-4972-a6a4-a800492eb446)

#### Elbow Method:
![image](https://github.com/user-attachments/assets/ef78820d-1a19-4e97-be4b-ed385f2eaf3f)

#### Küme Sayısı: 3, Silhouette Skoru: 0.6178922124066818
#### Küme Boyutları: {0: 97617, 1: 68893, 2: 92660, 3: 97684, 4: 6831, 5: 17837, 6: 65781, 7: 79410, 8: 11029, 9: 103312}

## Kurulum ve Çalıştırma
Projenin çalıştırılabilmesi için gerekli kütüphaneler:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
## Kaggle Defterimin Bağlantısı:
- https://www.kaggle.com/code/cerensukaramese/maliciousurlmlproject
