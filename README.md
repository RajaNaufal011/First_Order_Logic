# First-Order Logic in Prolog

## 2306020 Raja_Naufal_Fadhil Ns

Repositori ini berisi implementasi **First-Order Logic (FOL)** menggunakan **Prolog** untuk merepresentasikan hubungan keluarga berdasarkan diagram pohon keluarga.

## Struktur Program
Program ini dirancang dengan mendefinisikan sejumlah **fakta** dan **aturan** dalam Prolog, meliputi:

- **Fakta**: Informasi mengenai pernikahan, hubungan orang tua-anak, serta jenis kelamin.
- **Aturan**: Definisi relasi seperti saudara, kakek-nenek, cucu, paman, dan tante.

## Instalasi & Penggunaan
### 1. Instalasi SWI-Prolog
Pastikan **SWI-Prolog** telah terinstal di perangkat Anda. Jika belum, silakan unduh dan instal melalui tautan berikut:
🔗 **[SWI-Prolog Download](https://www.swi-prolog.org/Download.html)**

### 2. Mengunduh Repositori
Jalankan perintah berikut untuk mengunduh dan masuk ke direktori repositori:
```bash
git clone https://github.com/SalmaAulia29/First_Order_Logic.git
cd First_Order_Logic
```

## Menjalankan Program
1. Buka **SWI-Prolog**.
2. Masuk ke direktori tempat file program berada.
3. Jalankan perintah berikut di terminal **SWI-Prolog**:
   ```prolog
   [family].
   ```
4. Setelah program dimuat, Anda dapat menjalankan berbagai query untuk menelusuri hubungan keluarga, misalnya:
   ```prolog
   ?- grandparent(X, Y).
   ```
   Perintah di atas akan menampilkan semua **X** yang merupakan kakek atau nenek dari **Y**.
