# 01 · Data Lapangan

**Minggu:** PTS−4 · **Dinilai di:** PTS, kriteria *Pattern & data lapangan* (15 poin, bersama bagian pola di `03`)

> [!TIP]
> **Pilar CT yang dilatih: Pattern Recognition.** Pola hanya bisa ditemukan dari data yang nyata. Minggu ini kamu mengumpulkan bahan mentahnya: kejadian, angka, dan kutipan. Kamu belum menyimpulkan apa-apa; menghitung pola dilakukan di `03`.

## 1. Yang harus ada

Pilih **satu jalur**. Minimum terpenuhi kalau satu jalur lengkap. Dua jalur yang sama-sama setengah jadi (misalnya 2 narasumber dan 10 transaksi) **tidak** memenuhi minimum.

**Jalur A: minimal 3 narasumber**

- [ ] 3 orang berbeda (kode `N1`, `N2`, `N3`) yang benar-benar terlibat dengan jenis UMKM kasusmu: pemilik, karyawan, atau pelanggan tetap.
- [ ] Setiap narasumber menjawab **minimal 5 pertanyaan** tentang kejadian yang sudah terjadi (bukan pendapat atau rencana).
- [ ] Setiap narasumber punya **minimal 1 kutipan langsung**.

**Jalur B: minimal 20 data transaksi**

- [ ] **20 baris** transaksi nyata (kode `T01` sampai `T20`), dari catatan pemilik (dengan izin) atau dari pengamatanmu langsung.
- [ ] Setiap baris punya **minimal 5 kolom** terisi.

**Kedua jalur**

- [ ] Bagian "Sumber dan izin" terisi: dari mana data didapat, bagaimana caranya, dan izin yang diberikan.
- [ ] **Minimal 3 temuan awal**, masing-masing menyebut kode buktinya (misalnya `N2`, `T05`).
- [ ] Tidak ada data pribadi (lihat 2.3).

Data yang dikarang, oleh kamu sendiri atau oleh AI, tidak dihitung. Nilai plus: minimal satu narasumber (Jalur A) adalah **pemilik** UMKM nyata yang sejenis dengan kasusmu, dan izinnya tercatat. Plus ini menaikkan nilai satu tingkat, hanya kalau hitungan polamu di `03` cocok dengan data di file ini.

## 2. Cara mengerjakan

### 2.1 Wawancara singkat: tanya kejadian, bukan pendapat

Pakai tiga aturan dari Rob Fitzpatrick, *The Mom Test* (2013):

1. Bicarakan hidup dan pekerjaan mereka, bukan ide aplikasimu.
2. Tanyakan kejadian spesifik yang sudah terjadi, bukan pendapat atau rencana ke depan.
3. Lebih banyak mendengar daripada bicara.

Orang cenderung menjawab "iya, bagus" kalau ditanya pendapat, supaya sopan. Kejadian nyata lebih sulit dikarang. Bandingkan:

| Pertanyaan buruk (pendapat atau masa depan) | Pertanyaan baik (kejadian nyata) |
|---|---|
| "Bapak butuh aplikasi tiket servis?" | "Kapan terakhir ada jam pelanggan yang tertukar? Ceritakan dari awal." |
| "Janji ambil sering meleset, ya?" | "Minggu lalu, berapa pelanggan yang datang tapi jamnya belum jadi?" |
| "Berapa lama biasanya servis mesin?" | "Jam terakhir yang diservis mesinnya, masuk hari apa dan selesai hari apa?" |
| "Kalau ada aplikasinya, Bapak mau pakai?" | "Sekarang titipan jam dicatat di mana? Boleh saya lihat?" |

Tips praktis:

- 10 sampai 15 menit per narasumber cukup. Siapkan 6 sampai 8 pertanyaan, pakai minimal 5.
- Setiap jawaban yang menarik, susul dengan "Lalu apa yang Bapak/Ibu lakukan?" atau "Itu terjadi berapa kali bulan ini?"
- Catat angka, nama hari, dan kejadian. Jangan mencatat kesimpulanmu sendiri sebagai jawaban.
- Jangan menceritakan ide aplikasimu sampai wawancara selesai.

### 2.2 Mengumpulkan 20 transaksi

1. Tentukan kolom dulu (minimal 5), misalnya waktu, barang atau jasa, jumlah, harga, dan catatan masalah.
2. Ambil 20 transaksi **berturut-turut**, bukan memilih yang menarik saja. Pilihan yang disaring membuat pola palsu.
3. Tulis sumbernya: buku nota pemilik, rekap kasir, atau pengamatan langsung di jam tertentu.

### 2.3 Izin dan privasi

Repo kamu **public**. Siapa pun bisa membacanya.

- Minta izin lisan, jelaskan bahwa data dipakai untuk tugas kuliah dan akan tampil di internet tanpa nama. Tulis hasilnya: `Izin: ya (lisan)`.
- Pakai kode: narasumber `N1`, pelanggan `P-01`, transaksi `T01`.
- **Jangan** menulis nama lengkap, nomor HP, alamat rumah, plat nomor, atau foto wajah. Jangan mengunggah foto nota yang memuat nama atau nomor pelanggan.
- Nama usaha hanya ditulis kalau pemiliknya mengizinkan. Kalau tidak, tulis jenis dan wilayahnya, misalnya "laundry kiloan dekat kampus".

Dasar hukumnya: UU No. 27 Tahun 2022 tentang Pelindungan Data Pribadi.

> [!CAUTION]
> **Data pribadi nyata di repo menurunkan nilai.** Kalau nama lengkap, nomor HP, alamat rumah, plat nomor, atau foto wajah narasumber atau pelanggan ada di file mana pun di repo, kriteria *Pattern & data lapangan* di PTS langsung bernilai Kurang. Di PAS, data pribadi nyata di repo atau di video membuat kriteria *Prototipe* langsung Kurang.

### 2.4 Peran AI minggu ini

AI boleh membantu menyusun daftar pertanyaan atau memeriksa apakah pertanyaanmu menanyakan pendapat. AI **tidak boleh** mengarang jawaban atau transaksi. Catat pemakaiannya di `prompt-journal.md`.

## 3. Contoh pengisian

> [!NOTE]
> Kasus netral **Servis Jam Tangan Pak Darto** (kios servis jam kecil; masalahnya: jam pelanggan tertukar dan janji ambil sering meleset). Kasus ini tidak ada di bank kasus. **Data fiktif untuk keperluan pembelajaran.** Contoh ini memakai Jalur B.

**Jalur:** B (transaksi)

**Sumber dan izin:** buku nota Pak Darto, 20 tiket berturut-turut sejak Senin pekan pertama pengamatan. Disalin di kios dengan izin lisan Pak Darto (`Izin: ya (lisan)`). Nama dan nomor HP pelanggan tidak disalin. Hari ditulis sebagai "hari ke-": hari ke-1 = Senin, hari ke-7 = Minggu (kios tutup).

<details>
<summary><b>Lihat 20 baris transaksi contoh</b></summary>

| Kode | Masuk (hari ke-) | Pekerjaan | Ciri jam | Janji ambil (hari ke-) | Selesai (hari ke-) | Biaya (Rp) | Catatan |
|---|---|---|---|---|---|---|---|
| T01 | 1 | Baterai | analog perak, rantai | 1 | 1 | 25.000 | |
| T02 | 1 | Mesin | analog hitam, kulit | 3 | 4 | 150.000 | pelanggan datang hari ke-3, belum jadi |
| T03 | 2 | Tali | digital hitam, karet | 2 | 2 | 35.000 | |
| T04 | 2 | Kaca | analog emas, rantai | 4 | 3 | 60.000 | |
| T05 | 2 | Baterai | digital biru, karet | 2 | 2 | 25.000 | |
| T06 | 3 | Mesin | analog hitam, kulit | 5 | 8 | 150.000 | tertukar dengan T02 |
| T07 | 3 | Baterai | analog putih, kulit | 3 | 3 | 25.000 | |
| T08 | 4 | Kaca | digital hitam, karet | 6 | 5 | 60.000 | |
| T09 | 4 | Baterai | analog perak, rantai | 4 | 4 | 25.000 | |
| T10 | 4 | Tali | analog cokelat, kulit | 4 | 4 | 40.000 | |
| T11 | 5 | Mesin + Kaca | analog perak, rantai | 8 | 10 | 200.000 | pelanggan tanya lewat WA 2 kali |
| T12 | 5 | Baterai | digital hitam, karet | 5 | 5 | 25.000 | |
| T13 | 6 | Kaca | analog emas, kulit | 8 | 8 | 60.000 | |
| T14 | 6 | Baterai | analog hitam, kulit | 6 | 6 | 25.000 | |
| T15 | 8 | Mesin | analog hitam, kulit | 10 | 11 | 150.000 | hampir tertukar dengan T16 |
| T16 | 8 | Kaca | analog hitam, kulit | 10 | 9 | 60.000 | hampir tertukar dengan T15 |
| T17 | 9 | Tali | digital putih, karet | 9 | 9 | 35.000 | |
| T18 | 9 | Baterai | analog emas, rantai | 9 | 9 | 25.000 | |
| T19 | 10 | Mesin | digital hitam, karet | 12 | 13 | 150.000 | |
| T20 | 11 | Baterai | analog perak, kulit | 11 | 11 | 25.000 | |

</details>

**Temuan awal**

| Kode | Temuan | Bukti |
|---|---|---|
| TA1 | Ganti baterai dan ganti tali selalu selesai di hari yang sama dengan hari masuk. | T01, T03, T05, T07, T09, T10, T12, T14, T17, T18, T20 |
| TA2 | Janji ambil yang meleset selalu pekerjaan mesin. | T02, T06, T11, T15, T19 |
| TA3 | Jam yang tertukar atau hampir tertukar sama-sama analog hitam bertali kulit, dan semuanya menginap. | T02, T06, T15, T16 |

Perhatikan: temuan awal hanya menyebut apa yang terlihat. Menghitung dan menyimpulkan baru dilakukan di `03`.

## 4. Cek sebelum commit

- [ ] Satu jalur sudah lengkap: 3 narasumber dengan masing-masing 5 pertanyaan dan 1 kutipan, **atau** 20 baris transaksi dengan 5 kolom.
- [ ] Setiap pertanyaan menanyakan kejadian yang sudah terjadi, bukan pendapat atau rencana.
- [ ] Ada 3 temuan awal dan setiap temuan menyebut kode buktinya.
- [ ] Tidak ada nama lengkap, nomor HP, alamat, plat nomor, atau foto wajah di file ini.
- [ ] Bagian jalur yang tidak dipakai (5.3A atau 5.3B) sudah dihapus.

## 5. Isianmu

Semua yang ada di bawah judul ini adalah isianmu, dan hanya bagian ini yang diperiksa dosen. Jangan menghapus judul ini dan jangan menambah bagian baru sesudahnya.

### 5.1 Jalur yang dipilih

`A (narasumber)`

### 5.2 Sumber dan izin

`data didapat dari satu depot air isi ulang di area Jakarta Timur, wawancara dilakukan pada minggu PTS, saya melakukan wawancarra kepada tiga narasumber berbeda, ketiga narasumber setuju jawabannya dipakai untuk tugas kuliah dan dicatat
tanpa nama dan tanpa nomor konta`

### 5.3A Narasumber (hapus bagian ini kalau memakai Jalur B)

#### N1

| | |
|---|---|
| Peran | `Pemilik depot air isi ulang` |
| Hubungan dengan kasus | `Pemilik usaha depot air isi ulang yang melayani antar galon ke pelanggan langganan dan warung, sehingga mengalami langsung pencatatan pesanan lewat chat, antrean antar, dan batas muatan motor` |
| Cara dan lama | `Tatap muka, 20 menit>` |
| Izin | `ya (lisan)` |

| No | Pertanyaan | Jawaban ringkas |
|---|---|---|
| 1 | `Ceritakan sistem antar galon terakhir yang memakan waktu.` | `Antar ke warung paling boros waktu karena memakai motor yang hanya muat sekitar 6 galon, sedangkan pesanan warung biasanya sekitar 15 galon.` |
| 2 | `Bagaimana sistem transaksi pelanggan langganan dicatat sekarang?` | `Transaksi dicatat manual di buku. Pelanggan langganan memesan lewat WhatsApp pemilik, lalu pemilik meneruskannya ke karyawan untuk diantar.` |
| 3 | `Kapan terakhir ada pesanan terlewat atau tertukar, dan apa yang terjadi?` | `Pesanan terlewat terakhir terjadi hari ini karena pemilik lupa meneruskannya ke karyawan, dan pelanggan menghubungi pemilik lagi untuk konfirmasi. Kalau pesanan tertukar, karyawan menanyakan jumlah pesanan ke pemilik lebih dulu.` |
| 4 | `Berapa pelanggan diantar pada hari tersibuk minggu ini?` | `Sekitar 25 transaksi per hari` |
| 5 | `Siapa yang menentukan urutan antar, dan bagaimana caranya?` | `Urutan antar mengikuti siapa yang memesan lebih dulu, dengan sistem pesan langsung antar.` |

Kutipan langsung: "`Biasanya urutan antar pesanan adalah siapa yang duluan memesan. jadi sistem pengantarannya adalah pesan langsung antar`"

#### N2

| | |
|---|---|
| Peran | `Karyawan pengantar galon depot` |
| Hubungan dengan kasus | `Pelaksana langsung pengantaran galon dengan motor, sehingga menjalani sendiri trip bolak-balik, urutan antar, dan pesanan yang terlewat` |
| Cara dan lama | `Tatap muka, 30 menit` |
| Izin | `ya (lisan)` |

| No | Pertanyaan | Jawaban ringkas |
|---|---|---|
| 1 | `Ceritakan rute antar kemarin dari awal sampai selesai.` | `Kemarin pagi pesanan pertama dari rumah, 2 galon, langsung diantar karena urutannya siapa yang memesan lebih dulu. Lalu ada pesanan warung 15 galon, yang harus diantar bolak-balik karena motor hanya muat 6 galon. Siangnya mengantar ke beberapa rumah langganan di blok berbeda, dan sore menutup pesanan terakhir di komplek sebelah sebelum depot tutup.` |
| 2 | `Pernah bolak-balik ke area yang sama? Kapan dan kenapa?` | `Sering terjadi. Kemarin pesanan warung 15 galon diantar 3 kali bolak-balik ke warung yang sama (6, 6, dan 3 galon). Pernah juga baru kembali dari Blok A lalu ada pesanan dari rumah sebelahnya, sehingga harus berangkat lagi ke area yang sama karena pesanan tidak dikumpulkan dulu.` |
| 3 | `Apa yang Anda lakukan kalau ada pesanan mendadak di tengah jalan?` | `Kalau ada pesan baru dari pemilik saat di jalan, ia mengecek sisa muatan dan arahnya. Kalau searah dan masih muat (misalnya bawa 4 galon, pesanan baru 2 galon), ia kembali ke depot untuk mengambil galonnya sekalian. Kalau beda arah, ia menyelesaikan antaran yang dibawa dulu, lalu kembali mengambil pesanan baru.` |
| 4 | `Berapa lama satu putaran antar, dan bagian mana yang paling lama?` | `Antar ke rumah dekat dengan 2 sampai 4 galon memakan sekitar 15 sampai 20 menit satu putaran. Pesanan besar warung bisa hampir 1 jam karena 2 sampai 3 kali bolak-balik. Waktu juga habis saat menurunkan galon, menunggu penghuni keluar, dan mencari kembalian kalau pelanggan membayar dengan uang besar.` |
| 5 | `Kejadian terakhir pelanggan menelepon menanyakan galonnya?` | `Baru terjadi hari ini: pelanggan langganan komplain karena galon yang dipesan sejak pagi belum diantar. Ternyata chat pesanannya tertumpuk dan lupa diteruskan oleh pemilik. Setelah diberi tahu, pesanan itu langsung diprioritaskan dan karyawan meminta maaf ke pelanggan.` |

Kutipan langsung: "`Karena gk dikumpulin dulu dan sistemnya pesan langsung antar, ya kalau ada pesanan lagi saya harus jalan lagi ke area yang sama`"

#### N3

| | |
|---|---|
| Peran | `Pelanggan langganan depot (pemesan lewat WhatsApp)` |
| Hubungan dengan kasus | `Pengguna layanan antar galon yang merasakan keterlambatan dan ketidakpastian jam tiba` |
| Cara dan lama | `Chat, 20 menit` |
| Izin | `ya (tertulis di chat)` |

| No | Pertanyaan | Jawaban ringkas |
|---|---|---|
| 1 | `Kapan terakhir galon Anda terlambat diantar, dan berapa lama?` | `Terakhir terjadi hari ini. Pelanggan memesan lewat chat sejak pagi, tetapi galon baru tiba lewat jam makan siang, terlambat sekitar 2 sampai 3 jam dari estimasi biasa. Ternyata chat-nya tidak diteruskan pemilik ke bagian antar karena pemilik sedang pergi.` |
| 2 | `Bagaimana Anda memesan galon?` | `Memesan lewat WhatsApp langsung ke nomor pemilik, misalnya dengan chat "kirim galon 1 ke alamat biasa". Tidak ada aplikasi atau formulir khusus, dan pesan dikirim saat galon di rumah mulai menipis atau habis.` |
| 3 | `Pernah kehabisan air karena antar terlambat?` | `Pernah beberapa kali kehabisan air, terutama saat lupa memesan dari awal dan mengira galon akan cepat tiba. Kalau galon sudah kosong sebelum antaran datang, ia memasak air keran atau menumpang memakai air cadangan sementara.` |
| 4 | `Bagaimana Anda tahu galon akan datang jam berapa?` | `Tidak ada jam antar yang pasti, karena sistemnya pesan langsung antar dan bergantung pada antrean serta posisi pengantar. Dari kebiasaan, kalau pesan pagi saat tidak ramai, galon tiba dalam 30 sampai 45 menit. Untuk tahu posisinya, harus chat lagi menanyakan.` |
| 5 | `Hal terakhir yang membuat Anda kesal soal pengantaran?` | `Kejadiannya sama dengan nomor 1: sudah memesan sejak pagi tetapi pesanan tidak diteruskan, sehingga menunggu lama tanpa kepastian. Kadang galon juga tiba saat tidak ada orang di rumah atau saat sedang terburu-buru, karena jam tiba tidak bisa diprediksi.` |

Kutipan langsung: "`Gk ada aplikasi atau form khusus, pokoknya chat manual aja kalau galon di rumah sudah mulai menipis atau habi`"

### 5.3B Transaksi (hapus bagian ini kalau memakai Jalur A)

Ganti judul kolom sesuai kasusmu. Minimal 5 kolom; tambah kolom kalau perlu.

| Kode | `<kolom 1>` | `<kolom 2>` | `<kolom 3>` | `<kolom 4>` | `<kolom 5>` |
|---|---|---|---|---|---|
| T01 | | | | | |
| T02 | | | | | |
| T03 | | | | | |
| T04 | | | | | |
| T05 | | | | | |
| T06 | | | | | |
| T07 | | | | | |
| T08 | | | | | |
| T09 | | | | | |
| T10 | | | | | |
| T11 | | | | | |
| T12 | | | | | |
| T13 | | | | | |
| T14 | | | | | |
| T15 | | | | | |
| T16 | | | | | |
| T17 | | | | | |
| T18 | | | | | |
| T19 | | | | | |
| T20 | | | | | |

### 5.4 Temuan awal

| Kode | Temuan | Bukti |
|---|---|---|
| TA1 | `<isi>` | `<isi: kode N atau T>` |
| TA2 | `<isi>` | `<isi>` |
| TA3 | `<isi>` | `<isi>` |
