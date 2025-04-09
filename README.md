# 📊 BearBull – Manage your profit in stock and crypto trading easily.
**BearBull** adalah aplikasi Android yang dirancang untuk membantu investor dan trader dalam memantau kinerja portofolio saham maupun crypto secara efisien, praktis, dan terorganisir. Dengan fitur pencatatan transaksi beli, jual, dan dividen, BearBull menyederhanakan proses pelacakan return investasi dari waktu ke waktu. Aplikasi ini dilengkapi dengan grafik performa aset, analisis profit/loss mingguan hingga tahunan, serta notifikasi yang menjaga pengguna tetap update terhadap pencapaian target keuangan mereka. Dibangun menggunakan arsitektur **MVVM** dan **Clean Architecture**, serta memanfaatkan **Room Database** untuk penyimpanan lokal, BearBull dirancang agar ringan, responsif, dan dapat digunakan secara **offline**. Cocok bagi investor ritel maupun trader aktif yang ingin mengambil kontrol penuh atas performa portofolio dan menyusun strategi investasi jangka panjang dengan disiplin berbasis data.

[🎥 Demo Aplikasi BearBull](https://drive.google.com/file/d/1Y28x435cFjyXRwD5bE5F-475lekuMsSd/view?usp=sharing)

## 🔒 Source Code
This project is currently private.  
If you're interested in accessing the source code for review or collaboration, please contact me via [LinkedIn](https://www.linkedin.com/in/dedi-yanto-776b861b4/) or [Email](dediyanto180@gmail.com).

## ⚠️ Keterbatasan Saat Ini

Saat ini, BearBull menggunakan API publik yang hanya menyediakan data harga untuk saham-saham yang terdaftar di Bursa Efek Indonesia (BEI). Oleh karena itu:

- Pengambilan data harga pasar secara otomatis hanya tersedia untuk saham Indonesia.
- Grafik performa aset hanya tersedia untuk saham Indonesia berdasarkan data historis dari API.
- Untuk aset crypto atau saham luar negeri, pengguna tetap dapat mencatat transaksi secara manual, namun fitur pengecekan harga dan grafik performa belum tersedia.

🔧 Rencana ke depan:
Kami berencana untuk menambahkan dukungan multi-sumber API agar aplikasi dapat digunakan secara lebih luas, termasuk untuk aset crypto dan saham luar negeri.

## ✨ Fitur Utama

- Pencatatan transaksi beli, jual, dan dividen
- performa keuntungan/kerugian minggu, bulan, dan tahunan
- Ringkasan nilai investasi, return, dan pencapaian target portofolio
- Update otomatis nilai portfolio dan aset dengan WorkManager
- Notifikasi untuk perkembangan portofolio dan pencapaian target
- Filter histori transaksi berdasarkan kriteria tertentu
- Mode offline dengan penyimpanan lokal (Room Database)
- Grafik perkembangan portfolio investasi
- Grafik keuntungan/kerugian bersih transaksi Jual dan dividen
- Grafik perkembangan aset investasi

## 🛠️ Teknologi yang Digunakan

- **MVVM (Model-View-ViewModel)**
- **Clean Architecture**
- **Dagger-Hilt**
- **Room Database**
- **LiveData,Flow & ViewModel**
- **Paging 3**
- **Retrofit**
- **Gson Converter**
- **OkHttp Logging Interceptor**
- **MPAndroidChart**
- **Bottom Navigation & Bottom Sheet Fragment**
- **WorkManager**

## 📸 Screenshot

### 📊 Dashboard View

#### Section 1
![Dashboard Summary](https://drive.google.com/uc?export=view&id=1ZRJIUEwijL5QsaQRXzPAYcs4fgIY1aPr)

#### Section 2
![Dashboard Chart 1](https://drive.google.com/uc?export=view&id=1vdCfZwbrvb1D3oVcmosKCeap4CTQexhm)

#### Section 3
![Dashboard Chart 2](https://drive.google.com/uc?export=view&id=1IWcOwntMkxDwfAIcdwvM9Y4S6m0ngMYf)

---

### 📜 History Transaction View

#### History List
![Transaction List](https://drive.google.com/uc?export=view&id=1grpg9R8grb7tp_BkQ0Hg2pTzreTny3jO)

#### Filter Transaksi
![Filter Transactions](https://drive.google.com/uc?export=view&id=1JLB-c8ZPo0DYS3s8Psa39T9XBHC-33Gv)

#### Tambah Transaksi
![Add Transaction](https://drive.google.com/uc?export=view&id=1icPYzbSd3qLqh0LsWrv2kmybC5auLubC)

#### Detail Transaksi
![Transaction Detail](https://drive.google.com/uc?export=view&id=1GhZUpXPXKNNDipLSYsCqjpeSVD6PTtBS)

---

### 💼 Portfolio View

#### Asset List
![Asset List](https://drive.google.com/uc?export=view&id=1AjsfKMXUcFpBCDf3_idIB4myCKLjuo6h)

#### Asset Detail
![Asset Detail](https://drive.google.com/uc?export=view&id=165x4TIf6odsHnATKkC50N1ooTeSWahQT)

#### Grafik Trend Aset
![Asset Trend Chart](https://drive.google.com/uc?export=view&id=1EIWLMpyb9uVxdCZf6AcnUIHSiTH42pP1)

---

### ⚙️ Settings View

![Settings View](https://drive.google.com/uc?export=view&id=1vpPN80p1svNoZqr6sMQkFx82yDlk4EBz)
