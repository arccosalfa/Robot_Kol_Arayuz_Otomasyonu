## 🥾 Robot Kol Kontrol Arayüzü

Bu proje, **ESP32** tabanlı bir robot kol sistemini **C# WinForms arayüzü** üzerinden manuel veya otomatik olarak kontrol etmeye yarar.
Ayrıca sistem, **Isı ve Nem Haritası** görüntüleme özelliğine sahiptir.

---

### 🚀 Özellikler

* 🔧 **Manuel Kontrol:**
  Her bir servo motorun açısı `+` ve `–` butonlarıyla 0–180° arasında ayarlanabilir.
  JSON dosyası üzerinden güncel motor açıları kaydedilir.

* 🤖 **Otomatik Kontrol:**
  Arayüzdeki "Başla" ve "Durdur" butonları ile robot kolun otomatik moda geçişi yapılabilir.
  JSON dosyasındaki `"mode": "AUTO"` değeri sistemin otonom çalışmasını tetikler.

* 🌡️ **Isı Haritası Görüntüleme:**
  Python tarafında oluşturulan `heatmap.png` dosyası arayüzde görüntülenir.

* 💧 **Nem Haritası Görüntüleme:**
  Python tarafında oluşturulan `humiditymap.png` dosyası arayüzde görüntülenir.

