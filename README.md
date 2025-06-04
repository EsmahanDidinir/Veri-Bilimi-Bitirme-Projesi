# Veri-Bilimi-Bitirme-Projesi
# İnme (Stroke) Tahmin Projesi

## 📌 Proje Özeti

Bu proje, bireylerin sağlık verilerine göre inme geçirip geçirmeyeceğini tahmin etmeyi amaçlamaktadır. Veri kümesinde yaş, cinsiyet, tansiyon, kalp hastalığı, BMI ve glukoz seviyesi gibi değişkenler kullanılmıştır.

## 🗃️ Veri Kümesi

Veri kümesinde hedef değişken `stroke` olup, sınıflar dengesizdir (çok az kişi inme geçirmiştir). Bu dengesizliği gidermek için **SMOTE** yöntemi uygulanmıştır.

## ⚙️ Kullanılan Yöntemler

- **Veri Ön İşleme:** Eksik değer temizleme, kategorik değişken kodlama, standardizasyon
- **Modelleme:** Lojistik Regresyon
- **Dengeleme:** SMOTE ile örnek sayılarının eşitlenmesi

## 🎯 Sonuçlar

- Dengesiz veri ile model yüksek doğruluk verirken pozitif sınıfı (inme) tanımakta başarısızdı.
- SMOTE sonrası model, inme geçiren bireyleri daha iyi tahmin etti ancak genel doğruluk azaldı.
