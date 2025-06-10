# Rainfall-Prediction-with-ARIMA-and-SARIMA-Modelling
Dataset diambil dari situs situs resmi open-source data online milik BMKG dengan mengambil parameter curah hujan (RR) pada tahun 2020 hingga 2024 pada Kabupaten Sidoarjo Stasiun Metereologi Juanda. 

Dilakukan prepocessing untung set data time agar dapat dilakukan plotting grafik, kemudian handle missing value dengan mengambil rata-rata 1 hari sebelum dan 1 hari sesudah data NAN. Data memiliki banyak outliers sehingga dilakukan winsorization agar mengurangi efek outliers. 

Dilakukan differencing agar data mencapai stasioner kemudian dilanjut dengan analisis ACF-PACF guna menentukan parameter (p, d, q) untuk pemodelan ARIMA dan SARIMA.
