# Homebrew Tap for Eczaneler.ORG

Official Homebrew Tap repository for **[Eczaneler.ORG](https://eczaneler.org)** command line utilities.

---

## 📦 Kurulum (Installation)

```bash
brew tap mehmeterdogan/tap
brew install nobetci-eczane
```

---

## ⚡ Kullanım

```bash
# API anahtarınızı kaydedin
nobetci-eczane config set-key SIZIN_API_ANAHTARINIZ

# Türkiye genelinde nöbetçi eczaneleri sorgulayın
nobetci-eczane sentry

# İstanbul (34) nöbetçi eczanelerini sorgulayın
nobetci-eczane city 34

# GPS koordinatlarına göre en yakın eczaneleri bulun
nobetci-eczane nearby --lat 40.9876 --lon 29.0234
```

Detaylı dokümantasyon için: [nobetci-eczane-cli](https://github.com/mehmeterdogan/nobetci-eczane-cli)
