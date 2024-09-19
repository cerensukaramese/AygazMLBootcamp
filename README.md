# Malicious URLs Dataset Projesi

## Proje Hakkında
Bu proje, zararlı URL'leri tespit etmek için makine öğrenmesi tekniklerinin kullanıldığı bir çalışmadır. Projede, Kaggle'dan alınan **Malicious URLs Dataset** kullanılarak gözetimli ve gözetimsiz öğrenme algoritmaları uygulanmıştır. Amaç, zararlı URL'lerin sınıflandırılması ve analizi ile bu tür URL'lerin tespitine yönelik etkili bir model geliştirmektir.

## Kullanılan Veri Seti
Veri seti, çeşitli zararlı ve zararsız URL'leri içeren bir koleksiyondur. Veri setinin bağlantısı: [Malicious URLs Dataset]((https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset))

## Yöntemler
Proje kapsamında aşağıdaki yöntemler uygulanmıştır:
- **Gözetimli Öğrenme:** Random Forest algoritması kullanılarak model oluşturulmuş ve değerlendirilmiştir.
- **Gözetimsiz Öğrenme:** k-Ortalama kümeleme yöntemi ile veri analizi gerçekleştirilmiştir.

## Model Değerlendirmesi
Model performansı, aşağıdaki metriklerle değerlendirilmiştir:
- Doğruluk (Accuracy)
- Kesinlik (Precision)
- Duyarlılık (Recall)
- F1 Skoru

Ayrıca, sınıflandırma sonuçları için karışıklık matrisi (Confusion Matrix) oluşturulmuştur.

## Kurulum ve Çalıştırma
Projenin çalıştırılabilmesi için gerekli kütüphaneler:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
## Kaggle Defterimin Bağlantısı:
- https://www.kaggle.com/code/cerensukaramese/maliciousurlmlproject
