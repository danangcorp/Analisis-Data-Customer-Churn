# Analisis-Data-Customer-Churn
Tujuan utama dari proyek analisis ini adalah mengidentifikasi faktor-faktor pemicu churn pelanggan dan menghasilkan rekomendasi aksi nyata (actionable insights) untuk meningkatkan kesetiaan pelanggan (customer retention).

# Tahapan Analisis Data E-Commerce
Berikut adalah bagian awal dari tahapan analisis data pelanggan e-commerce:

## 1. Pendahuluan
Industri e-commerce tumbuh sangat pesat, memicu persaingan yang ketat dalam mempertahankan pelanggan. Mengakuisisi pelanggan baru membutuhkan biaya yang jauh lebih besar daripada mempertahankan pelanggan yang sudah ada. Oleh karena itu, kemampuan untuk memprediksi dan mencegah pelanggan melakukan churn (pindah ke kompetitor) menjadi kunci keberlanjutan bisnis.

Perusahaan e-commerce ini merekam data profil, transaksi, dan status keaktifan pelanggan. Namun, data mentah tersebut belum diolah secara optimal untuk memberikan wawasan strategis. Melalui proyek ini, data akan dibersihkan, dieksplorasi, dan dianalisis untuk menemukan pola tersembunyi di balik keputusan pelanggan untuk bertahan atau pergi.

## 2. Tujuan Proyek
Tujuan utama dari proyek analisis ini adalah mengidentifikasi faktor-faktor pemicu churn pelanggan dan menghasilkan rekomendasi aksi nyata (actionable insights) untuk meningkatkan kesetiaan pelanggan (customer retention).

## 3. Rumusan Masalah / Pertanyaan Bisnis Utama (Menggunakan Metode SMART)
Untuk mencapai tujuan tersebut, analisis ini difokuskan untuk menjawab 4 pertanyaan bisnis utama yang dirumuskan secara SMART (Specific, Measurable, Actionable, Relevant, Time-bound):

## BQ-1: Tren Finansial & Churn

Pertanyaan: Apakah pelanggan yang berhenti berlangganan (churn) adalah mereka yang pengeluarannya sedikit?

Jawaban & Penjelasan: Tidak. Justru sebaliknya, pelanggan yang pergi rata-rata memiliki pengeluaran yang sedikit lebih tinggi daripada pelanggan yang bertahan. Artinya, kita tidak sedang kehilangan pelanggan berbudget rendah, melainkan kehilangan pelanggan bernilai tinggi (VIP).

## BQ-2: Karakteristik Demografi

Pertanyaan: Kelompok usia dan jenis kelamin mana yang paling banyak meninggalkan aplikasi?

Jawaban & Penjelasan: Pelanggan Wanita dan kelompok usia Senior (55 tahun ke atas) adalah yang paling banyak berhenti berlangganan. Selain itu, perlu diwaspadai kelompok anak muda (di bawah 25 tahun) karena mereka mencatat rekor tertinggi untuk status "menjeda/menonaktifkan sementara" (paused) langganan mereka.

## BQ-3: Loyalitas & Perilaku

Pertanyaan: Apakah pelanggan yang sudah lama bergabung dan sering belanja dijamin lebih setia?

Jawaban & Penjelasan: Sangat tidak. Ini adalah temuan paling mengejutkan. Sekitar 94% pelanggan yang pergi justru adalah "veteran" yang sudah berlangganan lebih dari 3 tahun dan masuk dalam kategori sangat sering belanja. Kesetiaan di masa lalu tidak mencegah mereka untuk pergi, kemungkinan besar karena mereka sudah merasa jenuh atau bosan.

## BQ-4: Pembatalan & Churn

Pertanyaan: Apakah riwayat membatalkan pesanan memengaruhi keputusan pelanggan untuk berhenti langganan?

Jawaban & Penjelasan: Ya, sangat berpengaruh. Begitu seorang pelanggan mengalami kendala hingga harus membatalkan pesanannya (walaupun cuma 1 kali), risiko mereka untuk kecewa dan akhirnya pergi (churn) langsung melonjak drastis dibandingkan pelanggan yang belanjaannya selalu mulus tanpa pembatalan.

# 💡 Rekomendasi Strategi Bisnis
## 1. Strategi Berdasarkan BQ-1 (Fokus Layanan, Bukan Perang Harga)

Masalah: Kita kehilangan pelanggan yang punya daya beli tinggi.

Rekomendasi: Karena mereka bukan pelanggan yang sensitif terhadap harga, jangan buang budget untuk memberi mereka diskon murah. Fokuskan perbaikan pada kualitas pelayanan (Customer Experience), seperti mempercepat waktu pengiriman, meningkatkan kualitas packaging, dan memastikan Customer Service merespon keluhan dengan cepat.

## 2. Strategi Berdasarkan BQ-2 (Pendekatan Khusus Usia)

Masalah: Banyak pelanggan lansia (55+) yang pergi, dan anak muda (<25) yang menjeda langganan.

Rekomendasi: * Untuk usia 55+: Buat tampilan aplikasi (UI/UX) lebih ramah lansia. Misalnya: tombol yang lebih besar, tulisan yang lebih jelas, dan proses pembayaran yang tidak rumit.

Untuk usia <25: Tawarkan "Paket Langganan Pelajar" yang lebih murah atau opsi berlangganan yang bisa di-jeda (pause) dan diaktifkan lagi kapan saja tanpa penalti, agar mereka tidak benar-benar pergi.

## 3. Strategi Berdasarkan BQ-3 (Apresiasi Pelanggan Lama / VIP)

Masalah: Pelanggan yang sudah setia lebih dari 3 tahun dan sering belanja malah pergi karena jenuh.

Rekomendasi: Buat Program Loyalitas VIP Khusus Veteran. Jangan hanya mengejar pelanggan baru. Berikan pelanggan lama ini reward eksklusif, seperti: akses membeli produk baru lebih awal, layanan komplain prioritas, atau hadiah kejutan (surprise gift) di ulang tahun langganan mereka. Tujuannya mengembalikan rasa "spesial" mereka.

## 4. Strategi Berdasarkan BQ-4 (Penyelamatan Pesanan Batal)

Masalah: Pelanggan yang pernah membatalkan pesanan sangat rentan untuk pergi.

Rekomendasi: Buat sistem "Penyelamatan Otomatis" (Recovery System). Ketika pelanggan mengklik tombol "Batal Transaksi", sistem harus langsung memunculkan pesan otomatis. Tanyakan apa masalahnya, dan tawarkan bantuan langsung (misal: "Ongkir kemahalan ya? Ini ada voucher gratis ongkir khusus untukmu hari ini!"). Jangan biarkan mereka membatalkan pesanan dengan perasaan kecewa.
