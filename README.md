# MySkill-ClusteringModel-Portofolio

## LATAR BELAKANG
FundFusion, sebuah institusi bank di Wakanda, ingin mengembangkan upaya pelayanan marketing-nya terhadap nasabah existing maupun nasabah baru. Salah satu strategi marketing-nya adalah melakukan kampanye berbasis telepon atau telemarketing. Cara kerja strategi tersebut adalah menggunakan media telepon untuk menawarkan kepada nasabah.

Saat ini, FundFusion belum memiliki strategi yang jelas dalam hal penawaran produk ketika menghubungi calon nasabah. Masing-masing account manager memiliki KPI yang berbeda untuk costumer acqusition berdasarkan produk yang ditawarkan oleh FundFusion, seperti tabungan, deposito, kartu kredit, kredit rumah, kredit kendaraan, maupun kredit dana tunai.

Hal ini mengakibatkan calon nasabah sehari dapat dihubungi berulang kali oleh account manager yang berbeda untuk ditawarkan produk yang berbeda pula. Implikasinya, rejection rate yang didapatkan sangat tinggi dan dianggap sebagai spam oleh calon nasabah yang berujung pada pemblokiran nomor.

## PROBLEM STATEMENT
Institusi belum memiliki strategi yang tepat untuk menawarkan jenis produk yang sesuai dengan segmen calon nasabah yang akan direkrut.

## OBJECTIVE
Meningkatkan nasabah baru dengan cara menawarkan produk yang tepat sesuai dengan kriteria calon nasabah yang akan dihubungi.

## VARIABEL YANG TERSEDIA
Dari dataset yang dimiliki terdapat beberapa data yang tersedia:


---
1. **GCIF** : unique identifier nasabah.
2. **Area** : lokasi nasabah (Jakarta, Bogor, Bandung, Surabaya, Jogja, Solo).
3. **Jalur_Pembukaan** : touch points nasabah membuka produk (cabang, telemarketing, aplikasi digital, internet banking).
4. **Vintage**: durasi menjadi nasabah (sejak pembukaan akun).
5. **Usia**: usia nasabah.
6. **Jenis_Kelamin** : Laki-laki (1) dan Perempuan (0).
7. **Status_Perkawinan** : Belum menikah (0), Menikah (1), Cerai (2), Janda/Duda (3).
8. **Jumlah_Anak** : jumlah anak (numerik).
9. **Pendidikan** : status pendidikan terakhir (Tidak memiliki pendidikan formal (0), SD (1), SMP (2), SMA (3), Sarjana (4), Magister (5), Doktor (6)).
10. **Produk_Tabungan** : status kepemilikan produk (yes (1) atau no (0)).
11. **Produk_Deposito** : status kepemilikan produk (yes (1) atau no (0)).
12. **Produk_Kartu_Kredit** : status kepemilikan produk (yes (1) atau no (0)).
13. **Produk_Kredit_Rumah** : status kepemilikan produk (yes (1) atau no (0)).
14. **Produk_Kredit_Kendaraan** : status kepemilikan produk (yes (1) atau no (0)).
15. **Produk_Kredit_Dana_Tunai** : status kepemilikan produk (yes (1) atau no (0)).
16. **Total_Kepemilikan_Produk** : jumlah produk yang dimiliki (penjumlahan dari produk yang dimiliki).
17. **Pendapatan_Tahunan** : rata-rata pendapatan dalam setahun.
18. **Total_Relationship_Balance** : total aset nasabah dalam cutoff bulan observasi.

## EXPERIMENT
Periode Tinjauan:
1. Dikelompokkan berdasarkan demografis untuk dicari pola kepemilikan produk.
2. Dikelompokkan berdasarkan kepemilikan produk untuk dicari pola berdasarkan demografi.

## MODEL YANG DIGUNAKAN
1. K-Means
2. K-Medoid
