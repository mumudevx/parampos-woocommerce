# Param POS - Gelişmiş WooCommerce Ödeme Eklentisi

Bu eklenti, Param POS ödeme sistemi için geliştirilmiş gelişmiş bir WooCommerce ödeme yöntemidir. Standard eklentiye göre birkaç gelişmiş özellik sunmaktadır.

## Standard Plugin'den Farkları

### Gelişmiş Taksit Yönetimi
- **Dinamik Minimum Tutarlar**: Her taksit seçeneği için ayrı minimum tutar ayarlama
- **Esnek Taksit Seçenekleri**: 2-12 taksit arası detaylı kontrol
- **Otomatik Taksit Filtreleme**: Sepet tutarına göre uygun taksitleri gösterme
- **Gerçek Zamanlı Güncelleme**: Sepet değişimlerinde taksit seçeneklerinin otomatik güncellenmesi

### Güvenlik Özellikleri
- **Çift Katmanlı Doğrulama**: Yeni dinamik taksit yapısı için hem frontend hem backend kontrolü

## Kurulum

1. **Eklenti Dosyalarını İndirin**
   - Projeyi GitHub'dan zip olarak indirin

2. **WordPress Admin Paneli**
   - WooCommerce → Eklentiler → Yeni Ekle
   - "Eklenti Yükle" butonuna tıklayın
   - Zip dosyasını seçin ve yükleyin

3. **Eklentiyi Aktifleştirin**
   - Eklentiler sayfasından "Param POS Payment Gateway" eklentisini aktifleştirin

4. **Ödeme Ayarlarını Yapılandırın**
   - WooCommerce → Ayarlar → Ödemeler
   - "Param POS" seçeneğini bulun ve "Yönet" butonuna tıklayın

## Yapılandırma

### Temel Ayarlar
- **Client Code**: Param'dan aldığınız müşteri kodu
- **Client Username**: API kullanıcı adınız
- **Client Password**: API şifreniz
- **GUID**: Benzersiz tanımlayıcınız

### Taksit Ayarları
- **Taksit Seçimi**: Müşterilere taksit seçenekleri gösterme
- **POS Oranları**: Kullanıcı veya firma oranlarını kullanma
- **Minimum Tutarlar**: Her taksit için minimum sepet tutarı

### Güvenlik Ayarları
- **Test Modu**: Geliştirme ve test için ortam

## Teknik Özellikler
- **PHP 7.4+** uyumluluğu
- **WooCommerce 5.0+** desteği
- **WordPress 5.8+** uyumluluğu
- **SOAP API** entegrasyonu
- **AJAX** tabanlı dinamik özellikler

## Destek ve Dokümantasyon
- **API Dokümantasyonu**: https://dev.param.com.tr
- **Detaylı Kurulum Rehberi**: [Param Dokümantasyon](https://dev.param.com.tr/tr/hazir-altyapi/woocommerce-plugin-kurulumu)

## Versiyon
**v1.1.0** - Gelişmiş özellikler ve güvenlik iyileştirmeleri ile

---
*Bu eklenti, standard Param POS eklentisine göre geliştirilmiş bir versiyondur ve production ortamında kullanıma hazırdır.*

