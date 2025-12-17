# Programlama Dersi – Proje Raporu LaTeX Şablonu

Bu depo, **Programlama dersi öğrencilerinin** proje raporlarını düzenli, okunabilir ve ortak bir formatta hazırlayabilmeleri için hazırlanmış **LaTeX rapor taslağını** içerir.  
Şablon; özet, giriş, problem tanımı, yöntem/tasarım, uygulama (kod), testler, sonuç, kaynakça ve ekler gibi bölümleri hazır sunar. Ayrıca raporun sonunda **“Proje Sunumu ve Teslimi”** kısmında **onay kutulu** teslim/sunum teyit alanı bulunmaktadır.

## İçerik / Özellikler
- A4, okunaklı sayfa düzeni ve başlık yapısı
- Türkçe karakter ve Türkçe rapor dili uyumu
- Otomatik İçindekiler
- Kod eklemek için `listings` hazır ayarları
- Tablo ve görsel ekleme altyapısı
- “Proje Sunumu ve Teslimi” bölümünde onay kutuları ve imza alanı

## Hızlı Başlangıç
### Overleaf ile
1. Bu depoyu indir / zip olarak al
2. Overleaf’te **New Project → Upload Project** ile yükle
3. `rapor.tex` dosyasını açıp doldurmaya başla

### Bilgisayarında (TeX Live / MikTeX)
```bash
pdflatex rapor.tex
