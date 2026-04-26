# BIST Hacim Tarayıcısı

TradingView Scanner API ile BIST hisselerinde alım ilgisi ve satış baskısı taraması.

## Hızlı başlangıç — Colab (kurulum yok)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makerstorage/turkiye-fintech-veri-atlasi/blob/main/bist_hacim_tarayici.ipynb)

Tek tıkla tarayıcıda aç, **Çalıştır → Tümünü çalıştır**. Google hesabı yeterli.

## Yerel kurulum — VSCode

Gerekenler: Python 3.10+, VSCode + **Python** ve **Jupyter** eklentileri.

```bash
git clone https://github.com/makerstorage/turkiye-fintech-veri-atlasi.git
cd turkiye-fintech-veri-atlasi
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
code .
```

VSCode'da `bist_hacim_tarayici.ipynb` dosyasını aç → sağ üstten **Select Kernel** → `.venv/bin/python`'u seç → oynat tuşuna bas.

## Dosyalar

- `bist_hacim_tarayici.ipynb` — notebook
- `requirements.txt` — Python bağımlılıkları
