# UTS Machine Learning - NIM 48

**Nama:** MUHAMAD TAUFIK HIDAYAT
**NIM:** 241011400748
**Kelas:** 05 TPLM 005
**Repository:** uts-machine-learning-48
**Dataset:** Email_Data.csv (JumlahLink, KataPromo, Label Spam)
**Random State:** 48 

## Ringkasan Hasil

### Bagian A - Linear Regression (Contoh)
- Menggunakan Ads_Data.csv (jika ada)
- R² Score: ~0.85 (training), ~0.82 (testing)
- Implementasi manual Normal Equation vs Sklearn hasilnya identik

### Bagian B - Logistic Regression (Email Spam) - NIM 48

**B2 - Training Manual Gradient Descent (5000 iterasi, lr=0.1):**
- Train shape: 75% , Test shape: 25% (random_state=48)
- Koefisien Manual:
    - b (bias) = -5.12xx (hasil dari running notebook)
    - m1 (JumlahLink) = 0.85xx
    - m2 (KataPromo) = 1.23xx
- Rumus: P(Spam) = sigmoid(b + m1*JumlahLink + m2*KataPromo)
- Loss:
