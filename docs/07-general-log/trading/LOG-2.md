---
id: LOG-2
title: DEEFV itu alat menghitung
aliases:
  - DEEFV itu alat menghitung
date: 2026-07-18
element:
  - Tools
category:
  - trading
sub:
  - chart
status: Research Framework (Observation)
parent:
source: []
tags:
  - movement
  - distance
  - efficiency
  - friction
  - velocity
---

> **Date:** 18 July 2026
# Log 2 — DEEFV itu cara menghitung

# Konsep Dasar

Tidak semua movement memiliki kualitas yang sama.

Dua movement dapat menghasilkan jarak yang identik, tetapi membutuhkan usaha yang berbeda.

DEEFV dibuat untuk mengukur hubungan tersebut.

Bukan bertanya:

> "Harga naik atau turun?"

Tetapi bertanya:

> "Seberapa efisien harga berpindah?"

![[Pasted image 20260718185814.png]]
H4 sample

![[Pasted image 20260718185903.png]]
H30 dari sample H4

---

# Komponen

## D — Distance

Besarnya perpindahan harga.

Contoh:

- Pip
- Point
- ATR Distance
- Harga awal → harga akhir

Semakin besar D, semakin jauh movement tersebut.

---

## E — Effort

Besarnya usaha yang dibutuhkan agar Distance terjadi.

Belum ditetapkan secara final.

Kandidat pengukuran:

- jumlah candle
- volume
- volume cluster
- waktu
- liquidity consumption

Prinsipnya:

Semakin besar effort,  
semakin banyak energi yang dibutuhkan pasar.

---

## Ef — Efficiency

```
Ef = D / E
```

Mengukur seberapa efisien movement.

Interpretasi sederhana:

Distance besar  
+  
Effort kecil

=

Movement efisien.

Sedangkan

Distance kecil  
+  
Effort besar

=

Movement tidak efisien.

---

## Vel — Velocity

```
Velocity = Distance / Candle
```

Mengukur kecepatan perpindahan.

Movement:

100 pip

dalam

5 candle

lebih cepat daripada

100 pip

dalam

20 candle.

Velocity tidak berbicara mengenai arah.

Velocity hanya berbicara mengenai laju perpindahan.

---

## Fr — Friction

```
Fr = E − D
```

Mengukur hambatan selama movement.

Semakin tinggi friction,  
semakin besar energi yang hilang.

Movement dengan friction tinggi biasanya menunjukkan:

- banyak tarik-ulur
- banyak penolakan
- momentum melemah
- perpindahan kurang efisien

---

# Hubungan Antar Komponen

```
Effort
     │
     ▼
Distance
     │
     ▼
Efficiency
     │
     ▼
Velocity
     │
     ▼
Friction
```

Distance tidak pernah berdiri sendiri.

Selalu dibandingkan terhadap effort yang diperlukan.

---

# Filosofi

Harga hanyalah hasil.

Yang ingin diamati adalah proses perpindahan.

DEEFV berusaha mengukur kualitas proses tersebut.

Karena itu DEEFV bukan indikator arah.

DEEFV adalah framework pengukuran movement.

---

# Tujuan

DEEFV tidak dirancang untuk:

- mencari entry
- mencari exit
- menentukan buy atau sell

DEEFV dirancang untuk:

- mengukur kualitas movement
- membandingkan dua movement
- mengukur efisiensi perpindahan harga
- menjadi dasar observasi lanjutan

---

# Catatan Research

Masih terdapat beberapa komponen yang belum difinalisasi.

**Effort (E)**

Belum ditentukan apakah diukur menggunakan:

- jumlah candle
- volume
- volume profile
- volume cluster
- liquidity
- kombinasi beberapa variabel

**Boundary Movement**

Belum ada aturan universal mengenai:

- kapan movement dimulai
- kapan movement dianggap selesai

**Normalisasi**

Masih perlu ditentukan apakah Distance menggunakan:

- Pip
- ATR
- Persentase
- Normalized Distance

---

# Kesimpulan tentang DEEFV hari ini

**DEEFV memiliki boundary yang jelas sebagai sebuah metode pengukuran. Framework ini tidak dirancang untuk menjelaskan niat (intent) pasar, kekuatan (strength), maupun alasan di balik suatu pergerakan harga.**
**Tujuan utama DEEFV adalah membandingkan dua movement yang memiliki jarak (distance) yang sama, tetapi terbentuk melalui karakteristik pergerakan yang berbeda pada timeframe yang lebih rendah.**
**Dengan demikian, DEEFV berfungsi sebagai alat observasi kuantitatif untuk mengidentifikasi perbedaan kualitas suatu movement, sehingga hasilnya dapat digunakan sebagai dasar observasi dan analisis lanjutan, bukan sebagai kesimpulan akhir.**

# Hipotesis

DEEFV diasumsikan mampu mengukur karakteristik suatu movement secara konsisten berdasarkan hubungan antara Distance, Effort, Efficiency, Velocity, dan Friction.

DEEFV tidak diasumsikan mampu memprediksi arah harga maupun menjelaskan intent pasar.

Kemampuan tersebut, apabila ada, harus dibuktikan melalui observasi dan pengujian.

# Question
1. Apakah karakteristik movement tertentu memiliki korelasi terhadap kemungkinan adanya suatu intent pasar?
2. Apakah model tersebut cukup representatif untuk menggambarkan movement pasar?
3. Apakah suatu nilai dari perhitungan DEEFV terhadap chart dapat memberikan bobot tertentu untuk menilai expektasi pergerakan selanjutnya?
4. Apakah DEEFV mampu membedakan kualitas dua movement yang memiliki distance sama?
5. Apakah nilai DEEFV konsisten pada sampel yang berbeda?
6. Apakah terdapat korelasi antara nilai DEEFV dan perilaku harga setelah movement tersebut selesai?
7. Apakah korelasi tersebut cukup signifikan untuk dijadikan bobot dalam framework observasi?