---
article_id: PAR-17-04
title: "Mesin, Listrik, dan Kontrol pada Partisi Otomatis"
slug: "keselamatan-partisi-otomatis"
description: "Cover guarding, sensing, emergency stop, isolation, manual override, failure state, competence, inspection and records"
status: draft
writing_contract_version: native-id-v2
publication_date: "2026-06-24"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: PAR-17
primary_intent: "Identify automation hazards and controls"
reader_community: "Partisi.co.id"
reader_address: "Kawan Partisi.co.id"
final_route: "/artikel/keselamatan-partisi-otomatis.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/2092-sni03-1746-2000"
  - "https://pesta.bsn.go.id/produk/detail/130-sni03-6766-2002"
  - "https://www.assaabloy.com/au/en/resources/general-information/warranties-and-guarantees/lorient-maintenance-guide"
  - "https://www.modernfold.com/en-US/products/operable-partitions"
  - "https://store.astm.org/e0557-12r26.html"
  - "https://www.modernfold.com/document/e85561c0-9020-11ec-a109-d7329673ffbe?open=true"
  - "https://www.dormakaba.com/id-en/offering/products/movable-walls/dorma-huppe/moveo--do_9478"
  - "https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021"
  - "https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf"
  - "https://knauf.com/de-DE/systeme/trockenbausysteme/w11-de-metallstaenderwaende"
  - "https://my.dormakaba.com/medias/059291-170724-fsw-easy-safe-c-c-plus-instr-use-en-web-pdf.pdf?context=bWFzdGVyfHJvb3R8NjA1NDA1MHxhcHBsaWNhdGlvbi9wZGY="
  - "https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021"
  - "https://www.fema.gov/sites/default/files/2020-07/fema_earthquakes_reducing-the-risks-of-nonstructural-earthquake-damage-a-practical-guide-fema-e-74.pdf"
  - "https://pesta.bsn.go.id/produk/by_ics/126"
  - "https://www.bobrick.com/resource-center-2/literature/cleaning-maintenance/"
  - "https://www.epa.gov/indoor-air-quality-iaq/moisture-control-guidance-building-design-construction-and-maintenance-0"
  - "https://pesta.bsn.go.id/produk/detail/12927-sni17272020"
  - "https://pesta.bsn.go.id/produk/detail/12762-sni17262019"
---

# Mesin, Listrik, dan Kontrol pada Partisi Otomatis

Halo, Kawan Partisi.co.id! Partisi otomatis tidak aman hanya karena motor dapat menggerakkan panel. Keputusan yang benar adalah memastikan gerakan dibatasi, orang terdeteksi, energi dapat diisolasi, dan sistem punya keadaan gagal yang tidak menciptakan bahaya baru. Mesin, listrik, dan kontrol harus diperlakukan sebagai satu sistem bersama struktur, track, panel, pintu, dan jalur keluar.

Jawaban singkatnya: minta rancangan dan pemeriksaan kompeten untuk guarding (pelindung area jepit), sensor, tombol berhenti darurat, isolator listrik, pelepasan manual, serta prosedur pengujian sebelum dipakai. Saya tidak menetapkan rangkaian, ukuran kabel, rating, atau jarak sensor di artikel ini. Data produk dan kondisi proyeklah yang menentukan; untuk titik yang belum tersedia, tandai **[NEEDS PROJECT CONTROL DESIGN AND PROFESSIONAL REVIEW: G-01, G-03, G-05, G-09]**.

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

## Definisi dan batas objek

Yang dibahas adalah partisi lipat atau geser yang panelnya dipindahkan motor, aktuator, atau sistem listrik, termasuk track, pocket penumpukan, jamb, seal, pintu pass door, dan antarmuka ke bangunan. Sumber sistem operable-partition menempatkan dukungan track, panel, penutupan jamb, dan pengoperasian sebagai bagian dari sistem, bukan aksesori terpisah ([Modernfold](https://www.modernfold.com/en-US/products/operable-partitions), [ASTM E557-12(2026)](https://store.astm.org/e0557-12r26.html), [dormakaba MOVEO](https://www.dormakaba.com/id-en/offering/products/movable-walls/dorma-huppe/moveo--do_9478)).

Artikel ini mengidentifikasi bahaya dan bukti kontrol. Ia tidak mendesain panel kontrol, proteksi arus, sistem keselamatan mesin, struktur penyangga, atau jalur evakuasi. Menambahkan pintu mengubah rangka lokal, jarak bebas (clearance), seal, dan fungsi jalur keluar (egress); status dinding berperingkat tidak otomatis berlaku untuk pintu, frame, hardware, penetrasi, atau sealnya ([SNI 03-1746-2000](https://pesta.bsn.go.id/produk/detail/2092-sni03-1746-2000), [SNI 03-6766-2002](https://pesta.bsn.go.id/produk/detail/130-sni03-6766-2002), [panduan seal Lorient](https://www.assaabloy.com/au/en/resources/general-information/warranties-and-guarantees/lorient-maintenance-guide)). Untuk persyaratan dukungan, installer, dan laporan sistem tertentu, baca [spesifikasi teknis Modernfold](https://www.modernfold.com/document/e85561c0-9020-11ec-a109-d7329673ffbe?open=true).

## Cara kerjanya

Urutan aman dimulai dari perintah yang sah, verifikasi bahwa zona gerak kosong, lalu motor menggerakkan panel pada batas yang telah ditentukan. Guarding fisik atau jarak aman mengurangi akses ke titik crush dan pinch. Sensor mendeteksi orang atau penghalang; logika kontrol harus menghentikan atau mencegah gerak sesuai rancangan yang disetujui. Tombol emergency stop (berhenti darurat) menghentikan proses ketika kondisi tidak terkendali, tetapi tombol itu bukan pengganti isolator energi dan bukan bukti bahwa semua bahaya mekanis hilang.

Isolator harus memungkinkan teknisi memutus sumber energi sebelum pembersihan, pemeriksaan, atau perbaikan. Setelah energi diisolasi, manual override atau pelepasan mekanis yang ditetapkan pemasok memberi jalan keluar ketika listrik gagal. Instruksi pengoperasian pabrikan perlu menjadi rujukan, bukan diganti kebiasaan lapangan ([instruksi folding/sliding wall dormakaba](https://my.dormakaba.com/medias/059291-170724-fsw-easy-safe-c-c-plus-instr-use-en-web-pdf.pdf?context=bWFzdGVyfHJvb3R8NjA1NDA1MHxhcHBsaWNhdGlvbi9wZGY=)).

Keadaan gagal harus diputuskan sebelumnya: listrik padam, sensor kotor, panel tidak sejajar, track terhalang, komunikasi kontrol putus, atau pintu belum terkunci. “Berhenti” belum tentu cukup bila panel dapat meluncur karena energi tersimpan. Karena itu, pembuat sistem dan profesional terkait perlu mendefinisikan posisi aman, cara pelepasan, dan siapa yang boleh mengembalikan sistem ke mode otomatis.

## Faktor yang mengubah hasil

Pertama, kondisi bangunan. Ceiling grid bukan otomatis penyangga struktural. Beban dan gerakan diteruskan melalui stud, track, anchor, bracing, dan struktur pendukung; bukaan, panel tinggi, atau sistem gantung atas (top-hung) dapat mengubah tuntutan. SNI katalog dan panduan FEMA membantu mengarahkan pemeriksaan, tetapi tidak menyediakan detail universal anchor atau jarak bracing ([SNI 1727:2020](https://pesta.bsn.go.id/produk/detail/12927-sni17272020), [SNI 1726:2019](https://pesta.bsn.go.id/produk/detail/12762-sni17262019), [FEMA E-74](https://www.fema.gov/sites/default/files/2020-07/fema_earthquakes_reducing-the-risks-of-nonstructural-earthquake-damage-a-practical-guide-fema-e-74.pdf)).

Kedua, antarmuka dan lingkungan. Rute listrik, sprinkler, detektor, movement joint, skirting, drainase, dan ruang stacking harus disurvei sebelum penawaran atau pemasangan. Kelembapan, kebocoran, bahan pembersih yang tidak kompatibel, dan korosi dapat memengaruhi seal, panel, sensor, atau track; panduan EPA menekankan pengendalian sumber kelembapan, sementara materi pemeliharaan Bobrick membatasi tindakan pada sistem yang dirujuk ([EPA moisture control](https://www.epa.gov/indoor-air-quality-iaq/moisture-control-guidance-building-design-construction-and-maintenance-0), [Bobrick maintenance](https://www.bobrick.com/resource-center-2/literature/cleaning-maintenance/)).

Ketiga, bukti pelaksanaan. Gambar tersembunyi, sambungan, isolator, dan sensor sulit diverifikasi setelah penutupan. Permen PUPR No. 10 Tahun 2021 dan instruksi pemasangan partisi dapat dijadikan rujukan untuk menelusuri koordinasi serta dokumentasi pekerjaan ([Permen PUPR No. 10/2021](https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021), [Bobrick installation instructions](https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf), [Knauf W11](https://knauf.com/de-DE/systeme/trockenbausysteme/w11-de-metallstaenderwaende)).

## Contoh keputusan praktis

Bayangkan pemilik ingin satu tombol menutup panel saat ruangan dipakai bersama. Sebelum menyetujui, minta matriks sederhana berikut kepada tim berwenang:

| Kondisi | Bukti yang diminta | Keputusan sementara |
|---|---|---|
| Zona gerak dapat dijangkau orang | Layout guard, sensor, dan uji deteksi | Jangan aktifkan otomatis sebelum lulus uji |
| Listrik padam atau kontrol gagal | Prosedur isolasi dan manual override | Tetapkan operator kompeten dan posisi aman |
| Track atau panel seret | Catatan inspeksi, penyebab, dan tindakan | Hentikan pemakaian; jangan menaikkan torsi sembarang |
| Ada pintu atau jalur keluar | Verifikasi egress dan sistem pintu lengkap | Minta review profesional sebelum perubahan |

Kawan Partisi.co.id, checklist ini bukan pengganti desain. Ia membantu Anda menolak keputusan “sudah menyala berarti selesai” dan memaksa setiap asumsi memiliki pemilik serta bukti. Untuk membandingkan konteks partisi lipat secara umum, lihat [contoh halaman partisi lipat Yogyakarta](/partisi-lipat-yogyakarta.html), lalu tetap minta verifikasi sistem yang akan dipasang.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah mengandalkan sensor tunggal tanpa uji skenario. Periksa apakah sensor merespons orang, benda kecil, posisi panel, dan kondisi permukaan yang berubah; catat hasil, tanggal, konfigurasi, serta siapa yang menguji. Kesalahan kedua adalah memasang emergency stop (berhenti darurat) tetapi tidak menyediakan isolasi energi. Pastikan titik isolator diberi identitas, dapat diakses petugas berwenang, dan prosedurnya dipahami.

Kesalahan ketiga adalah mengubah parameter atau mengganti komponen tanpa persetujuan pemasok/desainer. Substitusi dapat mengubah beban, gerak, seal, bukti ketahanan api, atau garansi. Kesalahan keempat adalah menutup pekerjaan tanpa rekaman. Simpan gambar kondisi terpasang (as-built), daftar komponen, manual, hasil commissioning (uji penerimaan), pelatihan, inspeksi, dan riwayat gangguan. SNI 9038-3:2025 hanya menunjukkan adanya katalog inspeksi sistem pasif; interval dan metode spesifik tetap harus berasal dari sistem serta proyek yang disetujui ([SNI 9038-3:2025](https://pesta.bsn.go.id/produk/by_ics/126)).

Teman Partisi.co.id, bila muncul retak, longgar, korosi, seal gagal, panel mengikat, atau pintu tidak sejajar, jangan menutupinya dengan pelumasan atau pengecatan berulang. Gejala yang sama bisa berasal dari gerakan bangunan, anchor, benturan, air, instalasi menyimpang, atau keausan. Isolasi area dan minta diagnosis penyebab sebelum sistem dinyalakan kembali.

## Menjawab jalan pintas yang berisiko

Shortcut yang sering terdengar adalah, “Pasang motor dengan tombol naik-turun; operator akan menjaga jarak.” Cara ini memindahkan seluruh perlindungan ke perilaku manusia dan tidak menjawab listrik padam, pengguna baru, penghalang tak terlihat, atau energi tersimpan. Alternatif yang lebih dapat dipertanggungjawabkan adalah menetapkan fungsi keselamatan, batas tanggung jawab, mode manual, prosedur isolasi, pelatihan, dan uji penerimaan dalam dokumen proyek. Klaim kepatuhan atau kinerja tetap menunggu bukti sistem yang tepat; katalog peraturan seperti [PP No. 16 Tahun 2021](https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021) tidak dengan sendirinya membuktikan instalasi tertentu.

## Langkah berikutnya

Mesin, listrik, dan kontrol pada partisi otomatis aman bila gerakan dibatasi, orang terdeteksi, energi dapat diisolasi, kegagalan punya respons yang jelas, dan pemeriksaan meninggalkan rekaman. Langkah Anda berikutnya: minta paket survei, diagram antarmuka, daftar perangkat keselamatan, prosedur manual/isolasi, matriks uji commissioning (uji penerimaan), serta nama pihak kompeten yang menyetujui. Jangan mengaktifkan mode otomatis sebelum [NEEDS PROJECT CONTROL DESIGN AND PROFESSIONAL REVIEW: G-01, G-03, G-05, G-09] ditutup. Aturan operasinya sederhana: setiap perubahan pada panel, track, pintu, sensor, atau listrik harus dinilai ulang sebelum dipakai.
