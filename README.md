# Mahsul Hastalıkları Sınıflandırması

Bu proje, mahsul hastalıklarının sınıflandırılması için derin öğrenme mimarilerini kullanır. Projede Alex-Net, VGG-net, Resnet ve GoogleNet mimarileri uygulanmıştır.

## Proje Yapısı

- `data/`: Veri kümesi dosyaları.
- `models/`: Model mimarileri ve ağırlık dosyaları.
- `results/`: Sonuçlar ve karşılaştırma tabloları.
- `README.md`: Proje açıklaması ve rehber.
- `requirements.txt`: Gerekli kütüphaneler.

## Performans Karşılaştırması

Aşağıdaki tablo, modellerin doğruluk, kesinlik, geri çağırma ve F-ölçüsü metriklerini göstermektedir:

| Model     | Doğruluk | Kesinlik | Geri Çağırma | F-Ölçüsü |
|-----------|----------|----------|--------------|----------|
| AlexNet   | 0.7154   | 0.6916   | 0.7154       | 0.6946   |
| VGGNet    | 0.6820   | 0.6420   | 0.6820       | 0.6436   |
| ResNet    | 0.7327   | 0.7302   | 0.7327       | 0.7289   |
| GoogleNet | 0.7795   | 0.7726   | 0.7795       | 0.7751   |




