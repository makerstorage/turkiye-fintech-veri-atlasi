# Türkiye Fintech Veri Atlası

Türkiye finans piyasası (BIST, döviz, kripto, makro) için **Jupyter notebook** koleksiyonu. Her notebook bağımsız çalışır; bir konuyu uçtan uca gösterir: veri kaynağı, istek, yanıt, örnek tarama.

## Hızlı başlangıç — Colab (kurulum yok)

Aşağıdaki rozetlerden bir notebook'u tek tıkla aç, **Çalıştır → Tümünü çalıştır**. Google hesabı yeterli.

## Yerel kurulum — VSCode

Gerekenler: Python 3.10+, VSCode + **Python** ve **Jupyter** eklentileri.

```bash
git clone https://github.com/makerstorage/turkiye-fintech-veri-atlasi.git
cd turkiye-fintech-veri-atlasi
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
code .
```

VSCode'da bir `.ipynb` dosyasını aç → sağ üstten **Select Kernel** → `.venv/bin/python`'u seç → oynat tuşuna bas.

## Notebook'lar

| Notebook | Konu | Colab |
|----------|------|-------|
| `bist_hacim_tarayici.ipynb` | BIST · alım ilgisi & satış baskısı taraması (hacim) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makerstorage/turkiye-fintech-veri-atlasi/blob/main/bist_hacim_tarayici.ipynb) |
| `bist_hacim_tarayici_referans.ipynb` | BIST hacim taraması · hızlı referans (curl dahil) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makerstorage/turkiye-fintech-veri-atlasi/blob/main/bist_hacim_tarayici_referans.ipynb) |
| `bist_mum_formasyonu_tarayici.ipynb` | BIST · boğa & ayı mum formasyonu (candlestick) taraması | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makerstorage/turkiye-fintech-veri-atlasi/blob/main/bist_mum_formasyonu_tarayici.ipynb) |
| `turkiye_ekonomik_takvim.ipynb` | Türkiye · makro ekonomik takvim (faiz, enflasyon, vb.) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makerstorage/turkiye-fintech-veri-atlasi/blob/main/turkiye_ekonomik_takvim.ipynb) |
| `altinkaynak_fiyat_servisi.ipynb` | Altınkaynak · döviz + altın/gümüş anlık özet & detay | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makerstorage/turkiye-fintech-veri-atlasi/blob/main/altinkaynak_fiyat_servisi.ipynb) |
| `is_yatirim_hisse_tarayici.ipynb` | İş Yatırım · parametrik hisse tarayıcı (getiri pot., hedef fiyat) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makerstorage/turkiye-fintech-veri-atlasi/blob/main/is_yatirim_hisse_tarayici.ipynb) |

## Katkı · Yeni Notebook Ekleme

1. Yeni `.ipynb` dosyasını repo köküne ekle (anlamlı dosya adı: `bist_<konu>_tarayici.ipynb` gibi).
2. Notebook'un üstüne kısa bir başlık + tek paragraflık açıklama yaz.
3. Yeni bağımlılık varsa `requirements.txt`'ye ekle.
4. Üstteki tabloya bir satır ekle (Colab rozetiyle birlikte).

## Dosyalar

- `*.ipynb` — notebook'lar
- `requirements.txt` — Python bağımlılıkları
