# Tweet Veri Analizi ve Duygu Sınıflandırması (LLM Karşılaştırmalı)

Bu proje, tweet verileri üzerinden duygu (sentiment) analizi yaparak pozitif, negatif ve nötr sınıflandırması yaptım. Aynı zamanda klasik makine öğrenmesi modeli ile LLM (Large Language Models) karşılaştırması yaptım.

## 📊 Kullanılan Yöntemler ve Araçlar

- Python (Pandas, Matplotlib, Scikit-learn)
- Jupyter Notebook
- CountVectorizer + Logistic Regression
- ChatGPT ve Gemini (LLM karşılaştırması)

## 🔍 Proje Özeti

- 350 tweet’ten oluşan bir veri seti ile veri analizi ve görselleştirme yapıldı.
- Makine öğrenmesi modeli eğitilerek duygu tahmini gerçekleştirildi.
- Aynı tweet’ler ChatGPT ve Gemini’ye sorularak LLM sonuçları elde edildi.
- Tahminler karşılaştırılarak yorum farkları analiz edildi.
- Sonuçlar tablo ve açıklamalarla desteklendi.

## 🤖 LLM Karşılaştırması

| Tweet | ChatGPT | Gemini | Tahmin | Açıklama |
|-------|---------|--------|--------|----------|
| It works — if crashing every 3 mins counts. | Negatif | Negatif | Negatif | İronik ifade negatif sınıflandı. |
| Used it once. No opinion yet. | Nötr | Nötr | Nötr | Net yorum içermiyor, nötr sınıf. |
 
GitHub: [github.com/esengulcelik](https://github.com/esengulcelik)  
