---
article_id: PAR-11-04
title: "Menghitung Kuantitas Panel, Track, dan Area Finish dari Opening"
slug: "menghitung-kuantitas-partisi"
description: "Show assumptions for opening, panelization, stacking, track path, junctions, finish faces and uncertainty"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-01-27"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: PAR-11
primary_intent: "Build an auditable preliminary quantity"
reader_community: "Partisi.co.id"
reader_address: "Kawan Partisi.co.id"
final_route: "/artikel/menghitung-kuantitas-partisi.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021"
  - "https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf"
  - "https://knauf.com/de-DE/systeme/trockenbausysteme/w11-de-metallstaenderwaende"
  - "https://my.dormakaba.com/medias/059291-170724-fsw-easy-safe-c-c-plus-instr-use-en-web-pdf.pdf?context=bWFzdGVyfHJvb3R8NjA1NDA1MHxhcHBsaWNhdGlvbi9wZGZ8aGUyL2g0OC84OTYxMzc3NTAxMjE0LnBkZnxkMjExN2YyNzQyZTBkZWZkY2FmNDAzZ2MyYTZjMzUzNzgxZDMxYTcwMTMyYjUzNjRhMTYyZTllNDEwZWY1MzJi"
  - "https://peraturan.bpk.go.id/Details/37637/uu"
  - "https://peraturan.bpk.go.id/Details/161844/pp-no-14-tahun-2021"
  - "https://www.bobrick.com/resource-center-2/guide-specifications/"
  - "https://www.modernfold.com/document/e85561c0-9020-11ec-a109-d7329673ffbe?open=true"
  - "https://pesta.bsn.go.id/produk/detail/12927-sni17272020"
  - "https://pesta.bsn.go.id/produk/detail/12762-sni17262019"
  - "https://www.fema.gov/sites/default/files/2020-07/fema_earthquakes_reducing-the-risks-of-nonstructural-earthquake-damage-a-practical-guide-fema-e-74.pdf"
  - "https://store.astm.org/e0557-12r26.html"
  - "https://www.dormakaba.com/id-en/offering/products/movable-walls/dorma-huppe/moveo--do_9478"
  - "https://peraturan.bpk.go.id/Details/104477/permen-pupr-no-14prtm2017-tahun-2017"
  - "https://pesta.bsn.go.id/produk/detail/2092-sni03-1746-2000"
  - "https://pesta.bsn.go.id/produk/detail/130-sni03-6766-2002"
  - "https://www.modernfold.com/en-US/products/operable-partitions"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-001`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi Pintu LIpat Semi Peredam 1](/wp-content/uploads/2021/12/Pintu-LIpat-Semi-Peredam-1.png)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `Pintu LIpat Semi Peredam 1` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Menghitung Kuantitas Panel, Track, dan Area Finish dari Opening

Halo, Kawan Partisi.co.id! Kesalahan paling mahal saat menghitung partisi bukan salah perkalian, melainkan memakai satu angka opening untuk semua komponen. Lebar dan tinggi bukaan harus diterjemahkan menjadi pola panel, jalur track, kebutuhan sambungan, serta bidang finish yang benar-benar terlihat.

Jawaban singkatnya: bekukan data ukur dan asumsi sistem, hitung panel berdasarkan modul dan arah operasi, hitung track berdasarkan lintasan nyata termasuk belokan atau pocket, lalu hitung finish per muka. Tambahkan daftar ketidakpastian—bukan cadangan acak—untuk setiap angka yang belum disetujui. Hasil ini adalah kuantitas awal yang dapat diaudit, bukan ukuran fabrikasi.

![Ilustrasi Pintu LIpat Semi Peredam 1](/wp-content/uploads/2021/12/Pintu-LIpat-Semi-Peredam-1.png)

Ilustrasi umum dari aset lokal; bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

“Opening” adalah bukaan hasil survei yang akan diisi atau dilayani partisi: panjang bentang, tinggi bersih, posisi ujung, dan hubungannya dengan dinding, kolom, lantai, serta plafon. Catat apakah ukuran diambil dari muka finish ke muka finish atau dari struktur. Panel adalah unit bidang; track adalah jalur yang menuntun atau menggantung panel; area finish adalah luas permukaan yang dilapisi, termasuk muka balik atau return yang memang disyaratkan.

Artikel ini membantu BOQ, perbandingan penawaran, dan koordinasi survei. Ia tidak membuat detail fabrikasi, ukuran profil final, jarak anchor, atau toleransi. Beban partisi dan pergerakan bangunan diteruskan melalui panel, track, pengaku, anchor, dan struktur pendukung; plafon grid tidak otomatis menjadi tumpuan struktural ([SNI 1727:2020](https://pesta.bsn.go.id/produk/detail/12927-sni17272020), [SNI 1726:2019](https://pesta.bsn.go.id/produk/detail/12762-sni17262019), [FEMA E-74](https://www.fema.gov/sites/default/files/2020-07/fema_earthquakes_reducing-the-risks-of-nonstructural-earthquake-damage-a-practical-guide-fema-e-74.pdf)). Untuk konteks tata kelola pekerjaan konstruksi, baca juga status [Permen PUPR No. 10 Tahun 2021](https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021).

## Cara kerjanya

Mulai dengan lembar asumsi: kode opening, tanggal survei, sumber gambar, ukuran terukur, kondisi lantai dan plafon, posisi junction, serta status data—terukur, dari gambar, asumsi sementara, atau menunggu persetujuan.

1. Bekukan geometri bersih: lebar (W), tinggi (H), dan jumlah bentang. Kelompokkan opening menurut tinggi, arah operasi, dan jenis sistem.
2. Tentukan panelisasi dari modul sistem yang akan disubmittal. Untuk bentang lurus yang dimensinya sudah dibekukan, jumlah awal dapat ditulis sebagai `N = ceil(W / m)`, dengan `m` modul rencana yang disetujui; hasil ini bukan ukuran fabrikasi. Panel pintu, panel ujung, dan panel pocket diberi kode terpisah.
3. Telusuri track aktual: segmen lurus, tikungan, cabang, transisi ke pocket, dan ujung berhenti. Total track adalah penjumlahan semua segmen itu, bukan otomatis (W). Dukungan track, pocket, level lantai, seal, dan jamb memengaruhi sistem movable wall ([ASTM E557-12(2026)](https://store.astm.org/e0557-12r26.html), [dormakaba MOVEO](https://www.dormakaba.com/id-en/offering/products/movable-walls/dorma-huppe/moveo--do_9478)).
4. Pisahkan junction, jamb, seal, backing, dan hardware sebagai item bila sistem memerlukannya.
5. Hitung finish per muka. Untuk bidang persegi panjang tanpa pengurangan, satu sisi adalah `W × H` dan dua sisi adalah `2 × W × H`; lalu kurangi pintu atau area yang memang tidak difinish dan tambahkan return yang disyaratkan secara terpisah. Buat baris berbeda untuk material atau kode finish berbeda.
6. Rekonsiliasi total track dengan sketsa, total panel dengan pembagian modul, dan total finish dengan daftar muka. Setiap selisih harus punya alasan tertulis.

Dokumen seperti [Knauf W11](https://knauf.com/de-DE/systeme/trockenbausysteme/w11-de-metallstaenderwaende) atau [petunjuk Bobrick](https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf) dapat menjelaskan hubungan komponen dan urutan verifikasi, tetapi detailnya tidak boleh dipindahkan ke sistem lain tanpa submittal yang sesuai.

## Faktor yang mengubah hasil

Ukuran opening, ketidaksikuan dinding, lantai bergelombang, dan plafon yang turun mengubah panjang efektif serta trim. Simpan ukuran tiap ujung, bukan hanya rata-rata. Jika belum ada pengukuran ulang, tulis `[NEEDS SURVEY CONFIRMATION: opening, level, and junction dimensions]`.

Pola panel dan cara menumpuk juga penting. Pocket kiri dan kanan dapat menghasilkan track dan clearance berbeda. Pass door menambah framing, hardware, ruang pendekat, serta potensi kebocoran seal; klaim dinding berperingkat tidak otomatis berlaku untuk pintu, kusen, hardware, glazing, atau penetrasinya ([SNI 03-1746-2000](https://pesta.bsn.go.id/produk/detail/2092-sni03-1746-2000), [SNI 03-6766-2002](https://pesta.bsn.go.id/produk/detail/130-sni03-6766-2002)).

Jalur track dapat keluar dari bidang partisi menuju pocket dan membutuhkan dukungan yang diperiksa. Area finish juga berubah menurut muka A, muka B, return kolom, dan penutup pocket. Luas sama tidak berarti lingkup sama; konfigurasi, material, rangka, pintu, akses, perlindungan, testing, warranty, spares, dan handover harus dibandingkan pada basis yang seragam ([Modernfold technical specification](https://www.modernfold.com/document/e85561c0-9020-11ec-a109-d7329673ffbe?open=true), [Bobrick guide specifications](https://www.bobrick.com/resource-center-2/guide-specifications/)).

Fungsi pengguna ikut menentukan layout. Arah ayun, ruang pendekat, privasi, sirkulasi, dan perlengkapan saling berinteraksi; satu ukuran produk tidak membuktikan seluruh rute aksesibel ([Permen PUPR No. 14/PRT/M/2017](https://peraturan.bpk.go.id/Details/104477/permen-pupr-no-14prtm2017-tahun-2017)).

## Contoh keputusan praktis

Jika survei memberi satu opening tetapi belum menetapkan sisi pocket, buat dua skenario dan beri kode berbeda. Jangan memilih yang termurah sebelum ruang servis, arah operasi, dan dukungan track disetujui.

| Item | Skenario A: pocket kiri | Skenario B: pocket kanan |
|---|---|---|
| Panel | (N_A) sesuai modul | (N_B) sesuai modul |
| Track | opening + transisi + pocket | opening + transisi + pocket |
| Finish | muka terlihat dan return disetujui | muka terlihat dan return disetujui |
| Ketidakpastian | posisi pocket, clearance | posisi pocket, clearance |

Kawan Partisi.co.id, tabel ini bukan cara mengarang angka; ini cara membuat perbedaan asumsi terlihat. Setelah vendor mengirim layout, ganti simbol dengan angka terverifikasi dan simpan revisinya. Untuk penawaran, sertakan pengecualian seperti pembongkaran, perlindungan, akses lokasi, pekerjaan struktur, listrik, atau kerja malam bila belum termasuk.

## Kesalahan umum dan cara memeriksanya

- Mengalikan (W\times H) lalu menyebutnya seluruh pekerjaan. Pastikan track, pocket, junction, hardware, dan dua muka finish punya baris sendiri.
- Membulatkan panel ke bawah agar harga turun. Cocokkan pembulatan dengan modul dan ruang ujung.
- Memakai panjang opening sebagai panjang track. Gambar lintasan dengan panah arah gerak dan ukur tiap segmen.
- Menganggap satu muka finish berlaku untuk dua sisi. Tandai muka A, muka B, return, dan area tanpa finish pada elevasi.
- Mengunci ukuran dari gambar lama. Cantumkan tanggal survei dan cocokkan dengan kondisi lapangan.
- Membandingkan penawaran hanya dari luas atau lump sum. Samakan konfigurasi, material, dukungan, pintu, testing, exclusions, warranty, spares, dan handover; aspek hukum dan kontrak tetap perlu ditinjau ([UU No. 2 Tahun 2017](https://peraturan.bpk.go.id/Details/37637/uu), [PP No. 14 Tahun 2021](https://peraturan.bpk.go.id/Details/161844/pp-no-14-tahun-2021)).

Lakukan pemeriksaan empat mata: estimator membaca sketsa, vendor atau pelaksana memeriksa lintasan, dan perancang memeriksa antarmuka struktur, akses, serta fungsi. Item tersembunyi sulit diverifikasi setelah penutupan; substitusi atau deviasi dapat mengubah bukti performa dan warranty. Jika commissioning diwajibkan dalam dokumen proyek atau sistem, pengujiannya perlu memeriksa fungsi yang dimaksud, bukan hanya tampilan selesai ([petunjuk operasi dormakaba](https://my.dormakaba.com/medias/059291-170724-fsw-easy-safe-c-c-plus-instr-use-en-web-pdf.pdf?context=bWFzdGVyfHJvb3R8NjA1NDA1MHxhcHBsaWNhdGlvbi9wZGZ8aGUyL2g0OC84OTYxMzc3NTAxMjE0LnBkZnxkMjExN2YyNzQyZTBkZWZkY2FmNDAzZ2MyYTZjMzUzNzgxZDMxYTcwMTMyYjUzNjRhMTYyZTllNDEwZWY1MzJi).

## Jalan pintas yang tampak hemat

Harga per meter persegi untuk panel, track, dan finish sekaligus tampak praktis, tetapi gagal ketika ada pocket, junction, pintu, atau muka finish berbeda. Alternatif yang lebih aman adalah memecah BOQ menjadi panel, track per segmen, junction, finish per muka, aksesori, asumsi, dan pengecualian. Sobat Partisi.co.id boleh memakai harga satuan, asalkan setiap satuan menunjuk item dan konfigurasi yang jelas. Untuk melihat contoh konteks partisi lipat, Anda dapat menindaklanjuti [halaman partisi lipat Yogyakarta](/partisi-lipat-yogyakarta.html).

## Kesimpulan dan langkah berikutnya

Kunci survei; hitung panel dari modul dan pola penumpukan; ukur track mengikuti lintasan; pisahkan junction; lalu hitung finish per muka dan return yang disyaratkan. Tandai data belum pasti dengan `[NEEDS ...]`, bukan cadangan tanpa dasar.

Terbitkan lembar kuantitas bersama sketsa berkode, tabel asumsi, pengecualian, dan kolom verifikasi vendor/perancang. Minta persetujuan atas opening, pocket, dukungan track, pintu, finish, dan fungsi sebelum pemesanan. Kuantitas ini untuk keputusan awal; ukuran fabrikasi, rating, kepatuhan, dan warranty menunggu dokumen sistem serta review profesional. Informasi produk operable partition dari [Modernfold](https://www.modernfold.com/en-US/products/operable-partitions) dapat dipakai sebagai titik koordinasi, bukan pengganti desain proyek.
