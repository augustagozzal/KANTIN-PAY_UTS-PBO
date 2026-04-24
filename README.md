cat <<EOF > README.md
# KantinPay ITK - Sistem E-Wallet Kantin

## Identitas Mahasiswa
* **Nama:** Rizky Augusta Gozzal
* **NIM:** 04231078
* **Email:** 04231078@student.itk.ac.id

---

## Tahap 1: Analisis Paradigma OOP
Sistem **KantinPay ITK** dirancang menggunakan paradigma **Berorientasi Objek (OOP)**. Paradigma ini dipilih karena faktor keamanan yang lebih unggul dibandingkan paradigma Prosedural/Terstruktur. 

Dengan menerapkan prinsip **Enkapsulasi**, data sensitif seperti *Saldo* dan *PIN Mahasiswa* dapat dilindungi menggunakan modifier \`private\`. Hal ini mencegah pihak luar memanipulasi data secara langsung. Dalam paradigma terstruktur, variabel global sangat berisiko diubah tanpa verifikasi, yang dapat menyebabkan kerugian pada sistem transaksi.

---

## Tahap 2: Pemodelan Sistem
### Business Rules (Aturan Bisnis):
1. **Verifikasi PIN:** Transaksi hanya dapat diproses jika PIN yang dimasukkan sesuai dengan data Mahasiswa.
2. **Cukup Saldo:** Sistem akan menolak transaksi jika saldo Mahasiswa lebih kecil dari total harga menu.
3. **Ketersediaan Stok:** Transaksi hanya bisa dilakukan jika stok menu masih tersedia (Stok > 0).

### Entitas Utama:
* **Mahasiswa:** Mengelola data user (Nama, PIN, Saldo).
* **Menu:** Mengelola informasi produk (Nama Menu, Harga, Stok).
* **StandMakanan:** Logika utama untuk memproses transaksi dan validasi.
EOF
