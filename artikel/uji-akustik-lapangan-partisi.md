---
article_id: PAR-14-04
title: "Merencanakan Uji Akustik Lapangan untuk Partisi Terpasang"
slug: "uji-akustik-lapangan-partisi"
description: "Panduan menyiapkan rencana uji akustik lapangan partisi: tujuan, kondisi ruang, sumber-penerima, jalur samping, laporan, dan keputusan tindak lanjut."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-04-12"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: PAR-14
primary_intent: "Define a defensible field-test brief"
reader_community: "Partisi.co.id"
reader_address: "Sobat Partisi.co.id"
final_route: "/artikel/uji-akustik-lapangan-partisi.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/5954-sni03-6386-2000"
  - "https://www.iso.org/standard/79487.html"
  - "https://store.astm.org/e0336-24.html"
  - "https://store.astm.org/e0557-12r26.html"
  - "https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf"
  - "https://knauf.com/de-DE/systeme/trockenbausysteme/w11-de-metallstaenderwaende"
---

# Merencanakan Uji Akustik Lapangan untuk Partisi Terpasang

Halo, Sobat Partisi.co.id!

Meminta angka “kedap suara” setelah partisi terpasang terdengar sederhana, tetapi angka dari brosur atau uji laboratorium belum menjawab apakah dua ruang di proyek Anda benar-benar terpisah. Jalan suara bisa melewati sambungan, pintu, plafon, saluran udara (ducting), atau struktur di samping partisi. Karena itu, keputusan yang aman bukan langsung memilih alat atau mengejar satu angka, melainkan menyusun ringkasan rencana uji (brief) yang mengunci tujuan, pasangan ruang, kondisi ruang, dan cara membaca hasil.

Jawaban singkatnya adalah: tetapkan kriteria proyek dan pihak akustik yang berwenang menafsirkan, dokumentasikan kondisi ruang sebelum pengukuran, kendalikan sumber gangguan, lalu minta laporan yang memisahkan transmisi langsung dari jalur samping. Nilai lapangan tidak boleh diperlakukan sebagai padanan otomatis nilai laboratorium. [NEEDS PROJECT ACOUSTIC CRITERIA, ROOM PAIR, AND QUALIFIED ACOUSTICIAN TEST PLAN]

Artikel ini membantu pemilik menulis brief yang dapat dibandingkan dan diaudit. Anda akan menentukan apa yang diuji, bukti apa yang dikumpulkan, urutan koordinasi, titik berhenti, serta keputusan setelah laporan keluar. Pelaksanaan dan interpretasi tetap milik akustisi yang kompeten; panduan ini tidak menjanjikan kesetaraan laboratorium atau kelulusan sistem tertentu.

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

![Ilustrasi Pintu LIpat Semi Peredam 1](/wp-content/uploads/2021/12/Pintu-LIpat-Semi-Peredam-1.png)

Ilustrasi umum dari aset lokal; bukan dokumentasi proyek tertentu.

Sebelum masuk ke langkah, sepakati dulu bentuk hasil yang akan diterima. Jembatan ini penting agar “tes akustik” tidak berubah menjadi pengukuran tanpa keputusan atau perdebatan angka setelah pekerjaan selesai.

## Hasil uji akustik lapangan yang harus disepakati sejak awal

Hasil yang berguna bukan sekadar satu nilai. Brief harus meminta identitas ruang pengirim dan penerima, tanggal serta kondisi pengukuran, metode yang disetujui, data mentah atau ringkasan yang dapat ditelusuri, penyimpangan dari rencana, dan rekomendasi tindak lanjut (disposisi). Dengan format itu, pemilik dapat membedakan “data belum cukup”, “jalur samping dominan”, dan “kriteria tercapai”.

Istilah **isolasi bunyi udara** berarti kemampuan pemisah mengurangi suara yang merambat melalui udara dari satu ruang ke ruang lain. Mekanismenya dinilai dari perbedaan tingkat suara antara ruang pengirim dan penerima setelah faktor ruang diperhitungkan; konsekuensinya, kebocoran kecil di pintu atau sambungan dapat menurunkan hasil keseluruhan. Minta akustisi menjelaskan besaran lapangan yang dipakai dan batas interpretasinya, bukan hanya menyalin STC (kelas transmisi suara) atau Rw (indeks pengurangan bunyi berbobot) dari katalog.

SNI 03-6386-2000 dapat menjadi rujukan rekomendasi desain, sedangkan ISO 10140-2 menjelaskan metode laboratorium untuk spesimen. ASTM E336-24 secara khusus membahas pengukuran lapangan antarruang. Perbedaan ruang lingkup itu adalah alasan mengapa brief perlu menuliskan metode yang dipilih dan tidak menyamakan hasil laboratorium dengan kondisi terpasang ([SNI 03-6386-2000](https://pesta.bsn.go.id/produk/detail/5954-sni03-6386-2000), [ISO 10140-2:2021](https://www.iso.org/standard/79487.html), [ASTM E336-24](https://store.astm.org/e0336-24.html)).

Kawan Partisi.co.id, tetapkan pertanyaan keputusan sebelum memanggil penguji: apakah hasil dipakai untuk penerimaan pekerjaan, diagnosis keluhan, pembandingan desain, atau penentuan perbaikan? Satu tujuan dapat memerlukan kondisi ruang dan kedalaman laporan yang berbeda.

Jembatan berikut mengubah tujuan tadi menjadi batas pekerjaan. Tanpa batas yang tegas, tim mudah mengira uji satu bidang partisi sekaligus membuktikan pintu, plafon, dan seluruh lantai.

## Langkah 1 — tetapkan ruang lingkup, pasangan ruang, dan batas jalur suara

Tuliskan identitas ruang pengirim serta penerima, bidang partisi yang menjadi objek, arah pengukuran, dan bagian yang berbagi struktur. Sertakan pintu, pintu akses di dalam panel (pass door), kaca, rongga di atas kepala partisi (head void), plafon, lantai, kolom, saluran udara (ducting), kabel, dan penetrasi yang berpotensi menjadi antarmuka. Jika ada partisi lipat atau dinding bergerak, catat posisi operasi, rel penuntun (track), kantong penyimpanan (pocket), karet penutup (seal), dan sisi kusen (jamb); sistem tersebut adalah kesatuan mekanis, bukan panel lepas ([ASTM E557-12(2026)](https://store.astm.org/e0557-12r26.html)).

**Jalur samping (flanking)** adalah lintasan suara yang mengelilingi bidang pemisah utama melalui sambungan atau elemen bangunan lain. Mekanismenya membuat partisi tampak utuh tetapi suara tetap menyeberang lewat plafon, lantai, dinding tegak lurus, atau penetrasi; akibatnya, menambal permukaan partisi saja bisa gagal. Minta brief memetakan antarmuka yang terlihat dan menyatakan elemen mana yang tidak termasuk pengujian.

Tentukan juga hal yang sengaja tidak dikerjakan: misalnya uji laboratorium, pembuktian rating kebakaran, audit jalur keluar darurat (egress), pembongkaran lapisan tertutup, atau penetapan solusi perbaikan. Jika klaim akustik bergantung pada sistem pintu atau seal tertentu, bukti produk dan konfigurasi aktual harus dicocokkan; angka panel saja tidak membuktikan kinerja ruang.

Sediakan sketsa berpenanda dan daftar asumsi. Bila gambar as-built belum menunjukkan sambungan atas atau penetrasi, tulis sebagai ketidakpastian, bukan sebagai kondisi “pasti tertutup”.

Untuk mengumpulkan pertanyaan awal, Anda dapat meninjau [halaman partisi lipat Yogyakarta](/partisi-lipat-yogyakarta.html) dan [halaman partisi lipat Tuban](/partisi-lipat-tuban.html) sebagai titik kontak konfigurasi. Keduanya bukan bukti hasil uji ruang; cocokkan selalu nama sistem, sambungan, dan kondisi aktual di proyek.

Sebelum alat datang, fokus berpindah dari “apa yang diuji” ke “bukti apa yang membuat hasil dapat dipercaya”. Jembatan ini mencegah pengukuran di ruang yang belum siap lalu diulang tanpa tahu penyebab perbedaannya.

## Langkah 2 — kumpulkan dan cocokkan bukti desain, pemasangan, dan kondisi ruang

Kumpulkan gambar kondisi terbangun (as-built), spesifikasi sistem, dokumen pengajuan teknis (submittal), perubahan lapangan, foto sebelum penutupan, catatan penetrasi, serta identitas pintu dan perangkat keras (hardware). Instruksi pemasangan Bobrick dan sistem rangka logam (metal-stud) Knauf menunjukkan mengapa komponen tersembunyi perlu direkam sebelum tertutup; dokumen tersebut bukan izin untuk memindahkan toleransi atau langkahnya ke sistem lain ([Bobrick installation instructions](https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf), [Knauf W11 system hub](https://knauf.com/de-DE/systeme/trockenbausysteme/w11-de-metallstaenderwaende)).

Periksa kecocokan antara dokumen dan kondisi aktual: tipe panel, rangka, sambungan, pintu, seal, plafon, dan penetrasi. Catat setiap substitusi atau deviasi bersama lokasinya. Perbedaan itu dapat mengubah jalur suara dan membatasi arti laporan, sehingga harus terlihat oleh penguji dan pemilik sebelum pengukuran.

Kondisikan ruang sesuai keadaan yang hendak dinilai. Catat apakah pintu tertutup dan terkunci, apakah partisi bergerak sudah pada posisi operasi yang ditetapkan, apakah furnitur atau peralatan tetap berada di ruang, serta pekerjaan lain yang masih menimbulkan debu, getaran, atau suara. Jangan mengubah keadaan hanya untuk mengejar angka tanpa menuliskan perubahan tersebut.

Buat lembar kesiapan dengan kolom “tersedia”, “belum tersedia”, dan “perlu keputusan”. Isinya sekurang-kurangnya kriteria proyek, pasangan ruang, denah, riwayat perubahan, kondisi operasi partisi, sumber gangguan, dan kontak penanggung jawab. Bila satu item utama belum ada, tahan penjadwalan dan tandai [NEEDS DOCUMENT REVIEW] pada brief.

Jembatan ini membawa bukti menjadi urutan kerja. Urutan yang jelas mengurangi risiko sumber suara dipasang sebelum ruang siap atau penerima terganggu oleh aktivitas yang tidak dicatat.

## Langkah 3 — susun urutan sumber, penerima, latar belakang, dan observasi

Mulai dengan rapat singkat antara pemilik, kontraktor, pengelola gedung, dan akustisi untuk mengesahkan metode. **Sumber** adalah sisi atau perangkat yang menghasilkan sinyal uji; **penerima** adalah ruang dan titik tempat respons diukur. **Latar belakang** berarti suara yang sudah ada tanpa sinyal uji, misalnya aktivitas gedung atau mesin. Mekanismenya sederhana: bila latar belakang terlalu berubah, selisih antara pengirim dan penerima tidak lagi mewakili partisi; konsekuensinya, hasil bisa tidak stabil. Akustisi harus menentukan cara mengendalikan dan melaporkannya.

Urutan konseptual yang aman adalah: dokumentasikan ruang, ukur atau catat latar belakang, siapkan sumber dan posisi penerima sesuai metode yang disetujui, lakukan pengukuran berulang yang diwajibkan penguji, lalu simpan kondisi serta penyimpangannya. Detail posisi mikrofon, sinyal, kalibrasi, dan jumlah pengulangan bukan angka yang boleh ditebak dari artikel ini; semuanya harus berasal dari metode dan rencana penguji.

Jadwalkan waktu ketika operasi gedung dapat diidentifikasi. Catat hujan, pekerjaan mekanikal, lalu lintas, alarm, atau percakapan yang masuk selama sesi. Jika gangguan mengubah kondisi secara material, minta akustisi menyatakan apakah sesi dilanjutkan, diulang, atau diberi status terbatas.

Untuk partisi operabel, dokumentasikan siapa yang mengoperasikan, posisi panel, kondisi seal, dan apakah pintu atau pass door berfungsi sebagaimana desain. Catatan operasi dan pelatihan pengguna membantu memisahkan masalah pengoperasian dari masalah pemisah ruang. Jika catatan itu tidak tersedia, nyatakan keterbatasannya dalam laporan.

Sebelum menyatakan sesi selesai, cocokkan catatan operator, waktu, konfigurasi, dan gangguan dengan lembar kesiapan. Inilah titik untuk meminta klarifikasi, bukan menunggu sampai angka diperdebatkan.

Setelah urutan lapangan jelas, pembaca membutuhkan aturan berhenti. Jembatan ini menjadikan ketidakpastian sebagai keputusan formal, bukan catatan kaki yang hilang.

## Titik berhenti: kapan uji harus berhenti dan meminta peninjauan

Hentikan atau tunda sesi bila pasangan ruang berubah, partisi belum pada konfigurasi yang disepakati, pintu atau seal tidak dapat ditutup normal, pekerjaan bising tidak terkendali, atau identitas sistem berbeda dari dokumen. Jangan membuka lapisan tertutup atau mengubah penetrasi untuk “mencari kebocoran” tanpa otorisasi desain, keselamatan, dan penjaminan mutu (QA).

Minta review akustisi bila hasil menunjukkan penyimpangan besar, jalur samping diduga dominan, atau data tidak memenuhi kondisi metode. Minta pula review teknis bila ada klaim rating, kebakaran, jalur keluar darurat (egress), atau garansi (warranty) yang hendak ditarik dari hasil akustik; bidang-bidang itu membutuhkan bukti dan penanggung jawab yang berbeda.

Tandai [NEEDS QUALIFIED ACOUSTICIAN INTERPRETATION] apabila kriteria penerimaan, koreksi ruang, atau disposisi belum disahkan. Penanda ini menjaga agar angka sementara tidak berubah menjadi instruksi perbaikan atau keputusan serah terima.

Jembatan terakhir berfokus pada cara laporan dipakai. Laporan yang rapi membantu tim memilih tindakan; laporan yang hanya memberi angka mendorong tebakan penyebab.

## Verifikasi hasil, laporan, dan keputusan serah terima

Minta laporan memuat tujuan, identitas ruang, konfigurasi partisi, tanggal dan kondisi, metode serta batasannya, peralatan dan jejak kalibrasi yang dinyatakan penguji, data latar belakang, hasil, penyimpangan, dan interpretasi. Mintalah denah atau sketsa yang menandai sumber, penerima, pintu, penetrasi, dan jalur samping yang diamati. Jangan meminta format atau ambang yang tidak ada di kriteria proyek.

Gunakan matriks disposisi sederhana:

| Temuan | Keputusan sementara | Tindak lanjut |
|---|---|---|
| Data lengkap dan kondisi sesuai brief | Kirim untuk penerimaan sesuai kriteria proyek | Simpan laporan dan bukti konfigurasi |
| Data terganggu atau kondisi berubah | Tahan keputusan | Klarifikasi atau jadwalkan ulang dengan akustisi |
| Jalur samping atau deviasi terindikasi | Jangan menyalahkan panel secara otomatis | Inspeksi antarmuka dan review desain |
| Kriteria belum disahkan | Tidak ada keputusan lulus/gagal | Sahkan kriteria dan penanggung jawab |

Simpan bersama laporan: brief yang disetujui, denah, foto kondisi, daftar perubahan, log gangguan, dan catatan siapa yang menyetujui disposisi. Serah terima (handover) yang baik menunjukkan apa yang benar-benar diuji dan apa yang masih menjadi pekerjaan terbuka.

Shortcut yang sering dipilih adalah menerima angka STC atau Rw dari brosur sebagai bukti partisi terpasang sudah memenuhi target. Angka tersebut dapat berasal dari spesimen laboratorium dengan sambungan dan kondisi yang tidak sama; ASTM E336 membahas pengukuran lapangan, sedangkan ISO 10140-2 membahas metode laboratorium. Kebocoran pada pintu, head void, atau struktur sekitar dapat mendominasi hasil, sehingga angka katalog tidak menjawab kondisi ruangan Anda. Alternatif yang lebih dapat dipertanggungjawabkan adalah mencantumkan angka katalog hanya sebagai data desain, lalu memesan uji lapangan dengan konfigurasi, kriteria, dan interpretasi yang disahkan.

Teman Partisi.co.id, tindakan berikutnya adalah mengirim brief satu halaman beserta denah, kriteria proyek, riwayat perubahan, dan daftar kondisi ruang kepada akustisi yang akan menguji. Minta ia mengonfirmasi metode, kesiapan, data yang akan dilaporkan, serta batas kesimpulan sebelum jadwal dikunci. Dengan cara itu, Anda merencanakan uji akustik lapangan untuk partisi terpasang sebagai keputusan berbasis bukti—bukan janji kesetaraan laboratorium atau pengganti review profesional.
