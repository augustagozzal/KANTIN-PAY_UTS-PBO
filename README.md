# UTS PBO - RIZKY AUGUSTA GOZZAL
echo "# KantinPay ITK - Sistem E-Wallet Kantin" > README.md
echo "" >> README.md
echo "## Anggota Kelompok / Identitas" >> README.md
echo "* **Nama:** Rizky Augusta Gozzal" >> README.md
echo "* **NIM:** 04231078" >> README.md
echo "" >> README.md
echo "## Tahap 1: Analisis Paradigma OOP" >> README.md
echo "Sistem KantinPay ITK menggunakan paradigma Berorientasi Objek (OOP) karena lebih aman dibandingkan paradigma Terstruktur. Dengan **Enkapsulasi**, data sensitif seperti Saldo dan PIN Mahasiswa dilindungi menggunakan modifier \`private\`. Jika menggunakan variabel global (Terstruktur), pihak luar bisa langsung mengubah saldo tanpa verifikasi PIN, yang merupakan masalah keamanan fatal." >> README.md
echo "" >> README.md
echo "## Tahap 2: Pemodelan Sistem" >> README.md
echo "### Aturan Bisnis (Business Rules):" >> README.md
echo "1. Pembelian hanya sah jika PIN Mahasiswa benar." >> README.md
echo "2. Saldo Mahasiswa harus cukup untuk membeli menu (tidak boleh minus)." >> README.md
echo "3. Stok Menu harus lebih dari 0 sebelum transaksi diproses." >> README.md
echo "" >> README.md
echo "### Entitas (Classes):" >> README.md
echo "* **Mahasiswa:** Menyimpan data Nama, PIN, dan Saldo." >> README.md
echo "* **Menu:** Menyimpan data Nama Makanan, Harga, dan Stok." >> README.md
echo "* **StandMakanan:** Menangani logika validasi transaksi dan pengurangan stok/saldo." >> README.md
