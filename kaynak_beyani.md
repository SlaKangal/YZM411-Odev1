# Kaynak ve Yapay Zekâ Beyanı — YZM411 Ödev 1
**Öğrenci:** Sıla Kangal — 230212051

## Veri
`veri/normal.jpg`, `veri/golge.jpg`, `veri/lamba.jpg`: kendi kurduğum masaüstü sahnesinde iPhone 13 ile kendi çektiğim fotoğraflar (AE/AF kilidi açık, beyaz dengesi otomatik). Başka bir kaynaktan veri kullanılmadı.

## Kaynaklar
- YZM 411 ders notları, Hafta 1–2
- OpenCV belgeleri: `cv2.cvtColor`, `cv2.inRange`, `cv2.resize`, `cv2.ORB_create`, `cv2.findHomography`

## Yapay zekâ beyanı
- **Araç:** Claude (Anthropic)
- **Kullanım amacı:** Notebook kod iskeletinin hazırlanması, tahminlerimi ifade etmeme yardım, ölçümlerin yorumlanması ve rapor düzenlemesi.
- **Etkilediği dosya/hücreler:** Notebook'taki tüm kod hücreleri, tahmin ve yorum metinleri; PDF rapor metni.
- **Nasıl doğruladım:** Sahneyi kendim kurup fotoğrafları kendim çektim; tahmin seçimlerini çalıştırmadan önce kendim yaptım. Kodu kendi verimle Google Colab'da baştan sona çalıştırdım; rapordaki sayıları `sonuc_tablosu.csv` ve çıktı görselleriyle karşılaştırdım.

## Çalıştırma
1. `YZM411_Odev1_230212051.ipynb` dosyasını `veri/` klasörüyle aynı dizinde açın.
2. Gerekli paketler: numpy, opencv-python, matplotlib, pandas (sürümler notebook'un ilk hücresinde yazdırılır).
3. *Restart & Run All* — çıktılar `cikti/` klasörüne yazılır.
