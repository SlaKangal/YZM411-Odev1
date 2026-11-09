# YZM 411 Bilgisayarlı Görü — Ödev 1: Renk, Aydınlatma ve Örnekleme

**Sıla Kangal — 230212051** · 2026–2027 Güz

Kendi kurduğum masaüstü sahnesinde (peluş tavşan, beyaz A4, barkodlu etiket, ahşap masa) üç ışık koşulunda
(normal, gölge, lamba) çekilen fotoğraflarla:

1. Görüntünün sayısal yapısı (boyut, veri türü, `img[y, x, kanal]`, BGR/RGB)
2. Sabit RGB ve HSV eşikleriyle aydınlatmanın maskelere etkisi
3. Parlaklık kaydırması (b = +40) ve gama dönüşümü (γ = 0,5 / 2,0)
4. 1/4 küçültmede INTER_NEAREST ve INTER_AREA karşılaştırması

Her deneyden önce tahmin yazıldı, ardından ölçümle karşılaştırıldı.

## Dosyalar
| Dosya | İçerik |
|---|---|
| `YZM411_Odev1_230212051_Rapor.pdf` | 2 sayfalık rapor |
| `YZM411_Odev1_230212051.ipynb` | Çalıştırılabilir notebook (tahminler, ölçümler, yorumlar) |
| `sonuc_tablosu.csv` | Tüm ham ölçümler |
| `kaynak_beyani.md` | Veri kaynağı, kaynaklar ve yapay zekâ beyanı |
| `veri/` | Kendi çektiğim üç fotoğraf |
| `cikti/` | Maskeler ve şekiller |

## Çalıştırma
`pip install numpy opencv-python matplotlib pandas` → notebook'u `veri/` ile aynı klasörde açıp *Restart & Run All*.
