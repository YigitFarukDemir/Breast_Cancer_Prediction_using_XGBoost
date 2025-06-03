This project aims to create a machine learning model that helps breast cancer diagnosis using the XGBoost algorithm. Python is used as the software language.
This project made by Mehmet Akif Ersoy University students
Yiğit Faruk Demir,
Hilmi Can Ürlü, 
Vagıf Beyoğlu,
Mert Samet Çeliker,
Gül Karaman

Breast Cancer Classification with XGBoost / XGBoost ile Meme Kanseri Sınıflandırması
📌 Overview / Genel Bakış
English:
This project demonstrates a machine learning workflow for classifying breast cancer tumors as benign or malignant using the Wisconsin Breast Cancer Dataset and the XGBoost algorithm.

Türkçe:
Bu proje, Wisconsin Meme Kanseri Veri Seti ve XGBoost algoritması kullanılarak meme kanseri tümörlerinin iyi huylu (benign) veya kötü huylu (malignant) olarak sınıflandırılması sürecini göstermektedir.

📁 Dataset / Veri Seti
English:
The Wisconsin Breast Cancer Dataset includes:

699 instances

10 attributes (9 features + 1 target)

Target variable: Class (2 = benign, 4 = malignant → mapped to 0 and 1)

Türkçe:
Wisconsin Meme Kanseri Veri Seti şu bilgileri içerir:

699 örnek

10 özellik (9 giriş + 1 hedef değişken)

Hedef değişken: Sınıf (2 = iyi huylu, 4 = kötü huylu → 0 ve 1'e dönüştürülmüştür)

Features / Özellikler:

Clump Thickness / Yumak Kalınlığı

Uniformity of Cell Size / Hücre Boyutu Tutarlılığı

Uniformity of Cell Shape / Hücre Şekli Tutarlılığı

Marginal Adhesion / Kenar Yapışkanlığı

Single Epithelial Cell Size / Tek Epitel Hücresi Boyutu

Bare Nuclei / Çıplak Çekirdekler

Bland Chromatin / Donuk Kromatin

Normal Nucleoli / Normal Çekirdekçikler

Mitoses / Mitoz Sayısı

⚙️ Workflow / İş Akışı
Data Loading & Exploration / Veri Yükleme ve Keşif

Preprocessing / Ön İşleme

Handling missing values / Eksik verilerin işlenmesi

Feature encoding / Özellik dönüştürme

Model Training with XGBoost / XGBoost ile Model Eğitimi

Evaluation / Değerlendirme

Accuracy, precision, recall, F1-score

Visualization / Görselleştirme

🧩 Dependencies / Gereksinimler
Python 3.x

pandas

numpy

scikit-learn

xgboost

seaborn

matplotlib

🚀 Installation / Kurulum
bash
Kopyala
Düzenle
git clone [repository-url]
cd [repository-directory]
pip install pandas numpy scikit-learn xgboost seaborn matplotlib
▶️ Usage / Kullanım
Place the dataset file breast_cancer.csv in the project directory.
Veri dosyasını (breast_cancer.csv) proje dizinine yerleştirin.

Run the script / Scripti çalıştırın:

bash
Kopyala
Düzenle
python breast_cancer_classification.py
📊 Results & Metrics / Sonuçlar ve Performans Ölçütleri
Outputs / Çıktılar:

Dataset info & stats / Veri kümesi bilgisi

Class distribution plot / Sınıf dağılımı grafiği

Confusion matrix / Karmaşıklık matrisi

Accuracy, F1-score, Precision, Recall

Histograms and violin plots of features / Özelliklerin histogram ve violin grafikleri

Typical Performance / Tipik Performans:

Accuracy / Doğruluk: %97–99

F1 Score: %96–98

Precision / Kesinlik: %96–99

Recall / Duyarlılık: %95–98

🛠️ Customization / Özelleştirme
You can change / Aşağıdaki ayarları değiştirebilirsiniz:

Test size (default: 20%) / Test veri oranı (%20)

Random state / Rastgelelik durumu

XGBoost hyperparameters / XGBoost hiperparametreleri

Plot styles / Grafik stilleri

📄 License / Lisans
MIT License — This project is open-source.
Bu proje açık kaynaklıdır ve MIT lisansı altındadır.

🙏 Acknowledgments / Teşekkürler
University of Wisconsin Hospitals – for the original dataset

XGBoost, scikit-learn, matplotlib, seaborn geliştiricileri

