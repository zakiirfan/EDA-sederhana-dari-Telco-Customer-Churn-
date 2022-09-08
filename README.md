# EDA-sederhana-dari-Telco-Customer-Churn-
Repositori ini berisi EDA sederhana yang menggambarkan dataset Telco Customer Churn menggunakan python, sehingga cukup untuk menjadi dasar pertimbangan sebelum melakukan analisa ML lebih jauh
## Steps
1. Missing value handling
2. Duplicated value handling
3. Statistical Summary
4. Univariate Analysis
5. Multivariate Analysis
## EDA Summary
1. Dataset sudah bagus karena tidak ditemukan missing value dan duplicated value
2. Tidak ada yang janggal pada nilai minimum maupun nilai maksimum pada masing2 kolom
3. tenure mempunyai korelasi kuat dengan TotalCharges
4. MonthlyCharges mempunyai korelasi dengan TotalCharges namun tidak sekuat korelasi antara tenure dengan TotalCharges
5. Adanya hubungan linier antara tenure dengan TotalCharges untuk Customer Churn
6. Customer Churn memiliki tenure, MonthlyCharges dan TotalCharges yang lebih rendah
## EDA Question
1. Top 10 Jumlah TotalCharges tertinggi berdasarkan tenure dan Contract? 
Customer dengan jangka waktu 72 dan durasi kontrak per 2 tahun menghasilkan pendapatan tertinggi dan
Target marketing bisa fokus kepada Customer dengan durasi kontrak per 2 tahun karena lebih menguntungkan
2. Berapa persentase Customer churn dan MonthlyCharges churn?
Persentase customer churn sebesar 31% dan MonthlyCharges Churn sebesar 27%
dan Butuh tindaklanjut agar presentase tersebut dapat turun (contoh: pemberian diskon/promo)
