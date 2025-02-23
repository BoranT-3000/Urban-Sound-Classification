# 🎵 Urban Sound Classification Using Machine Learning
Bu proje, **UrbanSound8K** veri seti kullanılarak şehir ortamında kaydedilmiş seslerin sınıflandırılmasını amaçlamaktadır. **Makine öğrenmesi modelleri** ile analiz edilmiş ve en iyi sonuçları veren algoritmalar belirlenmiştir.

## 📂 Veri Seti  
Veri seti, 8.732 ses dosyasından oluşmaktadır ve **10 farklı ses sınıfı** içermektedir:  
- Air Conditioner  
- Car Horn  
- Children Playing  
- Dog Bark  
- Drilling  
- Engine Idling  
- Gunshot  
- Jackhammer  
- Siren  
- Street Music  

📥 **Veri Seti Kaynağı:** [UrbanSound8K - Kaggle](https://www.kaggle.com/datasets/chrisfilo/urbansound8k)  

---

## 🛠 Kullanılan Algoritmalar  
Projede aşağıdaki **makine öğrenmesi modelleri** kullanılarak en iyi performanslı model belirlenmiştir:  

🔹 **Ağaç Tabanlı Modeller:**  
- DecisionTreeClassifier  
- RandomForestClassifier  
- ExtraTreesClassifier  
- XGBClassifier  
- CatBoostClassifier  
- LGBMClassifier  
- HistGradientBoostingClassifier  

🔹 **Boosting Modelleri:**  
- AdaBoostClassifier  
- XGBoost  
- CatBoost  
- LightGBM  

🔹 **Lineer Modeller:**  
- LogisticRegression  

📊 **Model Optimizasyonu:**  
- **Optuna** kullanılarak en iyi hiperparametreler belirlendi.  
- En iyi model **doğruluk (accuracy), ROC-AUC ve hata metriği** kullanılarak değerlendirildi.  

---

## 🎯 Model Değerlendirme  
Modeller aşağıdaki metrikler kullanılarak değerlendirildi:  
✔ **Accuracy** (Doğruluk)  
✔ **Confusion Matrix** (Karışıklık Matrisi)  
✔ **Classification Report** (Precision, Recall, F1-score)  
✔ **ROC AUC Curve** (Alıcı Çalışma Karakteristiği)  

---

## 🚀 Çalıştırma Adımları  
Aşağıdaki adımları takip ederek projeyi çalıştırabilirsiniz:

### 1️⃣ Gerekli Kütüphaneleri Kurun  
```bash
pip install numpy pandas scikit-learn xgboost lightgbm catboost optuna matplotlib
```

## 📜 Lisans
Bu proje açık kaynaklıdır ve eğitim amacıyla paylaşılmıştır. Ticari kullanımlarda lütfen veri seti sahibinin lisans koşullarını inceleyin.
