# A-B-Testing-for-campaign-effect-on-number-of-purchases

A/B Testing Analysis: Impact of Marketing Campaign on Purchase Behavior
Proyek ini bertujuan untuk mengevaluasi efektivitas Campaign pemasaran dengan membandingkan perilaku pembelian pengguna sebelum dan sesudah Campaign menggunakan pendekatan statistik.

Alur Kerja Analisis

--------------------------------------------------

1. Definisikan Hipotesis

$H_0$: Campaign tidak memberikan pengaruh purchase behaviour customer

$H_1$: Campaign memberikan pengaruh purchase behaviour customer



2. Assumption Check (Uji Asumsi)
Sebelum menentukan jenis uji hipotesis, dilakukan serangkaian pengujian asumsi dasar:

Uji Normalitas (Shapiro-Wilk Test): Hasil pengujian menunjukkan bahwa salah satu variabel tidak berdistribusi normal (p < 0.05). Hal ini disebabkan oleh distribusi yang miring (skewed) akibat respon kampanye yang tidak merata.

Uji Homogenitas (Levene's Test): Dilakukan untuk memverifikasi kesamaan varians antar kelompok. Hasil menunjukkan data bersifat homogen.

3. Statistical Method: Mann-Whitney U Test
Mengingat asumsi normalitas tidak terpenuhi, analisis ini beralih dari statistik parametrik ke statistik non-parametrik.

Jenis Uji: Mann-Whitney U Test (Two-Sided).

--------------------------------------------------

## **Kesimpulan**

Penggunaan uji Mann-Whitney U menghasilakn kesimpulan bahwa adanya ***Campaign tidak memberikan purchase behaviour customer.***
