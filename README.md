# 🧠 Stroke Prediction Projesi

Bu proje, demografik ve sağlık verileri kullanılarak bireylerin **inme (stroke) geçirme riskini** makine öğrenmesi yöntemleriyle tahmin etmeyi amaçlamaktadır.  
Proje, *W-Code 2.0 Veri Bilimi ve Yapay Zeka Atölyesi* kapsamında **final projesi** olarak geliştirilmiş ve **30 proje arasından ilk 3’e girmiştir**.

---

## 📌 Problem Tanımı

İnme, erken teşhis edilmediğinde ciddi ve kalıcı sağlık sorunlarına yol açabilen kritik bir hastalıktır.  
Bu çalışmanın amacı, bireylere ait sağlık ve yaşam tarzı bilgilerini kullanarak inme riskini önceden tahmin edebilen bir model oluşturmaktır.

---

## 📊 Veri Seti

- **Kaynak:** Kaggle – Stroke Prediction Dataset  
- **Hedef Değişken:** `stroke`  
  - 0: İnme yok  
  - 1: İnme var
- **Kullanılan başlıca özellikler:**
  - Yaş
  - Cinsiyet
  - Hipertansiyon
  - Kalp hastalığı
  - Ortalama glikoz seviyesi
  - BMI
  - Sigara kullanımı
  - Çalışma türü, ikamet türü vb.

---

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

- Python  
- Pandas, NumPy – Veri işleme  
- Matplotlib, Seaborn – Veri görselleştirme  
- Scikit-learn – Modelleme ve değerlendirme  

---

## 🔍 Veri Ön İşleme

- Eksik değerlerin ele alınması (BMI vb.)
- Kategorik değişkenlerin kodlanması
- Özellik ölçeklendirme
- **Dengesiz veri problemi**nin (stroke sınıfının az olması) analizi
- Eğitim ve test verisinin ayrılması

---

## 🤖 Kullanılan Modeller

- Logistic Regression  
- Random Forest Classifier  

Modeller aşağıdaki metrikler kullanılarak karşılaştırılmıştır:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

> Veri seti dengesiz olduğu için yalnızca accuracy değil, özellikle **recall ve F1-score** değerleri dikkate alınmıştır.

---

## 📈 Sonuçlar ve Çıkarımlar

- Logistic Regression modeli, dengesiz veri yapısında daha istikrarlı sonuçlar vermiştir.
- Random Forest modeli yüksek performans göstermesine rağmen dengesiz sınıflara karşı daha hassas bulunmuştur.
- Özellik önem analizinde **yaş**, **ortalama glikoz seviyesi** ve **hipertansiyon** değişkenlerinin inme riski üzerinde belirleyici olduğu görülmüştür.

---

## 🚀 Sonuç

Bu proje, makine öğrenmesinin sağlık alanında **erken risk tespiti** amacıyla nasıl kullanılabileceğini göstermektedir.  
Özellikle tıbbi veri setlerinde doğru ön işleme adımları ve uygun değerlendirme metriklerinin seçimi kritik öneme sahiptir.

---

## 📁 Proje Yapısı

