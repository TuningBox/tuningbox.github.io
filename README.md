# TuningBox Website

GitHub Pages için TuningBox Privacy Policy ve Terms of Service sayfaları.

## 🚀 GitHub Pages'e Deploy Etme

### Adım 1: GitHub Repository Oluştur

1. GitHub'da yeni bir repository oluşturun:
   - Repository adı: `tuningbox-website`
   - Public seçin (GitHub Pages ücretsiz için gerekli)
   - README ekleyin

### Adım 2: Dosyaları Yükle

Bu klasördeki tüm dosyaları repository'ye yükleyin:

```bash
cd website
git init
git add .
git commit -m "Initial commit: Add privacy policy and terms of service"
git remote add origin https://github.com/[KULLANICI_ADI]/tuningbox-website.git
git push -u origin main
```

### Adım 3: GitHub Pages'i Aktifleştir

1. GitHub repository sayfasına gidin
2. **Settings** sekmesine tıklayın
3. Sol menüden **Pages** seçeneğine tıklayın
4. **Source** bölümünde:
   - **Branch**: `main` seçin
   - **Folder**: `/ (root)` seçin
5. **Save** butonuna tıklayın

### Adım 4: URL'i Al

Birkaç dakika sonra siteniz hazır olacak:

```
https://[KULLANICI_ADI].github.io/tuningbox-website/
```

**Örnek:**
- Ana Sayfa: `https://ariffbasaran.github.io/tuningbox-website/`
- Privacy Policy: `https://ariffbasaran.github.io/tuningbox-website/privacy.html`
- Terms of Service: `https://ariffbasaran.github.io/tuningbox-website/terms.html`

## 📝 Dosyalar

- `index.html` - Ana sayfa (Privacy Policy ve Terms linkleri)
- `privacy.html` - Gizlilik Politikası
- `terms.html` - Kullanım Şartları

## 🔧 Özelleştirme

### E-posta Adresini Değiştirme

`privacy.html` ve `terms.html` dosyalarında:
- `support@tuningbox.app` kısmını kendi e-posta adresinizle değiştirin

### Web Sitesi URL'ini Değiştirme

`privacy.html` ve `terms.html` dosyalarında:
- `https://ariffbasaran.github.io/tuningbox-website` kısmını kendi URL'inizle değiştirin

## ✅ Kontrol

Deploy sonrası şu URL'leri test edin:
- ✅ Ana sayfa açılıyor mu?
- ✅ Privacy Policy linki çalışıyor mu?
- ✅ Terms of Service linki çalışıyor mu?
- ✅ HTTPS çalışıyor mu? (otomatik)

## 📱 App Store'da Kullanım

App Store Connect'te:
- **Privacy Policy URL**: `https://[KULLANICI_ADI].github.io/tuningbox-website/privacy.html`
- **Terms of Service URL**: `https://[KULLANICI_ADI].github.io/tuningbox-website/terms.html`

---

**Not**: GitHub Pages deploy işlemi 1-5 dakika sürebilir. İlk deploy'dan sonra değişiklikler birkaç saniye içinde yansır.

