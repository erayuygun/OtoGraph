# OtoGraph

OtoGraph, kullanıcıların çeşitli markalardaki ve segmentlerdeki araçları keşfetmelerine yardımcı olan etkileşimli bir web uygulamasıdır. Bu proje, araç markaları ve modelleri arasındaki ilişkileri görselleştirmek için D3.js ve jQuery kullanır.

## Özellikler

- Marka veya segment bazında araçları gruplayarak görselleştirme
- Araç düğümlerine tıklayarak model hakkında detaylı bilgiye erişim
- Düğüm üzerinde sağ tıklayarak açılan modal pencerede araç detaylarını görüntüleme
- Etkileşimli grafik ve kontrol kutuları ile kullanıcı dostu arayüz

## Gereksinimler

- Web tarayıcısı (Chrome, Firefox, Safari, vb.)
- İnternet bağlantısı

## Kurulum

1. Proje dosyalarını indirin veya klonlayın:
   ```bash
   git clone https://github.com/kullaniciadi/OtoGraph.git
2.Proje dizinine gidin:
   cd OtoGraph

3. 'index.html' dosyasını bir tarayıcıda açarak projeyi başlatın.

## Kullanım
1. Ana sayfada bulunan "Hemen Başlayın" butonuna tıklayın.
2. Araçları markaya veya segmente göre gruplamak için sağ üst köşedeki seçim kutusunu kullanın.
3. Gruplar arasındaki ilişkiyi graf yapısı sayesinde renkler ve logolar sayesinde rahatlıkla görebilirisiniz.
4. Sağ tıkladığınızda açılan modal pencerede araç hakkında detaylı bilgileri görüntüleyin.

## Yapı
index.html: Ana HTML dosyası.
style.css: Stil tanımlamaları.
script.js: JavaScript fonksiyonları ve D3.js kodları.
expanded_car_data_all_v2.csv: Araç verilerini içeren CSV dosyası.
