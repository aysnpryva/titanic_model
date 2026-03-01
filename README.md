 Titanic Survival Prediction (82.68% Accuracy)

Bu layihədə Titanik faciəsində sərnişinlərin sağ qalma ehtimalını proqnozlaşdıran bir Maşın Öyrənməsi modeli qurulmuşdur.

Layihənin Xülasəsi
Data: Seaborn kitabxanasından götürülmüş Titanic dataset.
Model: Random Forest Classifier.
Dəqiqlik:82.68%.

İstifadə Olunan Alətlər
Python
Pandas & NumPy (Məlumat manipulyasiyası)
Seaborn (Məlumatın yüklənməsi)
Scikit-Learn(Modelin qurulması və qiymətləndirilməsi)

 Məlumatın Təmizlənməsi (Preprocessing)
 Yaş sütunundakı boşluqlar median (orta) dəyərlə dolduruldu.
 Cinsiyyət və Liman məlumatları rəqəmsal formata (Label Encoding) çevrildi.
 Lazımsız sütunlar ('deck', 'who', 'alive' və s.) modelin dəqiqliyini artırmaq üçün silindi.

 Necə İşlətməli?
1. Kitabxanaları yükləyin: 'pip install seaborn scikit-learn pandas'
2. Jupyter Notebook faylını (Titanic_Survival_Prediction.ipynb) işlədin.
