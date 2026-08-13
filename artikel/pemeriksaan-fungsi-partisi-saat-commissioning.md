---
article_id: PAR-14-02
title: "Memeriksa Alignment, Gerak, Lock, dan Seal saat Commissioning"
slug: "pemeriksaan-fungsi-partisi-saat-commissioning"
description: "Panduan praktis untuk tim QA memeriksa keselarasan, gerak panel, penguncian, dan seal saat commissioning partisi."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-04-03"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: PAR-14
primary_intent: "Verify functional behavior consistently"
reader_community: "Partisi.co.id"
reader_address: "Kawan Partisi.co.id"
final_route: "/artikel/pemeriksaan-fungsi-partisi-saat-commissioning.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021"
  - "https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf"
  - "https://my.dormakaba.com/medias/059291-170724-fsw-easy-safe-c-c-plus-instr-use-en-web-pdf.pdf?context=bWFzdGVyfHJvb3R8NjA1NDA1MHxhcHBsaWNhdGlvbi9wZGZ8aGUyL2g0OC84OTYxMzc3NTAxMjE0LnBkZnxkMjExN2YyNzQyZTBkZWZkY2FmNDAzN2MyYTZjMzUzNzgxZDMxYTcwMTMyYjUzNjRhMTYyZTllNDEwZWY1MzJi"
  - "https://www.modernfold.com/document/e85561c0-9020-11ec-a109-d7329673ffbe?open=true"
  - "https://www.assaabloy.com/au/en/resources/general-information/warranties-and-guarantees/lorient-maintenance-guide"
---

# Memeriksa Alignment, Gerak, Lock, dan Seal saat Commissioning

Halo, Kawan Partisi.co.id! Panel terlihat rapi belum berarti sistem partisi siap dipakai. Saat commissioning (uji fungsi sebelum serah terima), tim QA (quality assurance atau penjaminan mutu) perlu membuktikan bahwa panel berada pada posisi yang benar, bergerak sesuai urutan, mengunci tanpa dipaksa, dan seal menutup pada titik yang memang dirancang. Kesalahan umum adalah hanya melihat hasil akhir; padahal panel dapat tampak sejajar ketika diam tetapi mengikat saat digerakkan atau tidak menutup rapat di sambungan.

Cara paling aman adalah membuat urutan uji yang disetujui proyek, mencatat kondisi awal, menjalankan setiap panel dalam konfigurasi operasi normal, lalu mengulanginya dan menutup temuan dengan bukti. Nilai celah, gaya, beban, atau jumlah siklus bukan angka universal di artikel ini. Gunakan gambar kerja, manual sistem yang terpasang, dan kriteria penerimaan yang disetujui. Jika dokumen itu belum ada, tandai **[NEEDS PROJECT ACCEPTANCE CRITERIA AND APPROVED METHOD]** sebelum menyatakan lulus.

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

## Hasil akhir dan prasyarat pemeriksaan fungsi

Sebelum memilih alat, sepakati dulu arti “lulus”. Bagian ini mencegah pemeriksaan berubah menjadi pendapat visual dan menjelaskan siapa yang memutuskan, data apa yang dibawa, serta kondisi area yang harus siap.

Hasil commissioning adalah catatan yang dapat ditelusuri: identitas panel atau bentang, konfigurasi saat diuji, pengamatan alignment (keselarasan posisi), gerak, lock (penguncian), dan seal (perapat), pengulangan uji, temuan, serta keputusan buka-koreksi-uji ulang. Alignment berarti hubungan panel terhadap jalur, jamb (tiang atau penutup ujung panel), dan panel tetangga tetap sesuai gambar; mekanismenya terlihat dari celah dan pertemuan yang konsisten ketika panel bergerak; konsekuensinya adalah gerak tidak mengikat dan penutupan dapat diperiksa. Cara mengukurnya dan batas lulus tetap mengikuti dokumen proyek.

Kontraktor atau pemasok yang memahami sistem menjalankan operasi, QA mencatat, dan wakil perancang atau pemilik menyetujui hasil sesuai matriks tanggung jawab. Siapkan gambar terbitan terakhir, daftar panel, manual operasi, berita perubahan, alat ukur yang statusnya masih berlaku, serta formulir temuan. Petunjuk pemasangan pabrikan menekankan pentingnya dukungan, urutan, dan komponen yang sesuai; lihat contoh instruksi partisi Bobrick untuk pola dokumentasinya ([instruksi pemasangan Bobrick](https://www.bobrick.com/wp-content/uploads/2040-69_ii.pdf)).

Jika lantai, rel, saku parkir, pintu, atau area aman belum siap, jangan memaksa uji parsial lalu menyebut sistem lulus. Commissioning harus mewakili konfigurasi pemakaian yang akan diserahkan.

## Langkah 1 — Tetapkan ruang lingkup alignment, gerak, lock, dan seal

Scope yang jelas mencegah tim mencampur uji fungsi dengan klaim struktur, akustik, kebakaran, atau garansi. Setelah objek dan antarmuka ditentukan, bagian ini membantu Anda memutuskan apa yang diamati dan apa yang harus dirujuk ke disiplin lain.

Daftarkan setiap lintasan panel, titik awal dan akhir, arah gerak, posisi tumpuk, pass door bila ada, jamb, ambang, rel atas, dan pertemuan dengan dinding atau plafon. Tandai antarmuka yang bukan bagian paket—misalnya struktur penyangga atau lantai—tetapi dapat membuat panel miring. Sistem dinding bergerak dipengaruhi dukungan rel, berat panel, saku tumpuk, kerataan lantai, seal, dan penutupan jamb; dokumen teknis Modernfold menjelaskan mengapa semua item itu perlu berada dalam paket pemeriksaan ([contoh spesifikasi teknis Modernfold](https://www.modernfold.com/document/e85561c0-9020-11ec-a109-d7329673ffbe?open=true)).

Nyatakan juga yang tidak diuji. Pemeriksaan ini tidak menetapkan rating akustik, ketahanan api, kapasitas rel, atau nilai proprietary. Penambahan pintu dapat mengubah rangka, beban, jarak bebas, dan fungsi keluar; bukti untuk aspek tersebut perlu paket uji dan persetujuan tersendiri. Untuk sistem bergerak, manual operasi dormakaba dapat menjadi rujukan urutan produk yang dinamai, bukan toleransi bagi sistem lain ([petunjuk operasi dormakaba](https://my.dormakaba.com/medias/059291-170724-fsw-easy-safe-c-c-plus-instr-use-en-web-pdf.pdf?context=bWFzdGVyfHJvb3R8NjA1NDA1MHxhcHBsaWNhdGlvbi9wZGZ8aGUyL2g0OC84OTYxMzc3NTAxMjE0LnBkZnxkMjExN2YyNzQyZTBkZWZkY2FmNDAzN2MyYTZjMzUzNzgxZDMxYTcwMTMyYjUzNjRhMTYyZTllNDEwZWY1MzJi).

## Langkah 2 — Kumpulkan dan cocokkan bukti sebelum panel digerakkan

Urutan dokumen menentukan apakah observasi dapat dipercaya. Jembatan ini penting karena panel yang sudah ditutup atau diubah sulit diverifikasi tanpa rekaman, sementara penggantian komponen dapat mengubah bukti fungsi.

Cocokkan nomor revisi gambar dengan kondisi terpasang. Periksa jenis panel, arah operasi, perangkat lock, profil seal, hardware pintu, dan detail rel terhadap submittal (dokumen pengajuan teknis) yang disetujui. Catat substitusi atau deviasi sebagai temuan, bukan asumsi bahwa komponennya setara. Permen PUPR tentang sistem manajemen keselamatan konstruksi menempatkan perencanaan, pelaksanaan, dan pengendalian sebagai hal yang perlu dikelola dalam pekerjaan konstruksi ([Permen PUPR No. 10 Tahun 2021](https://peraturan.bpk.go.id/Details/216875/permen-pupr-no-10-tahun-2021)).

Buat lembar observasi dengan kolom: identitas panel, posisi, kondisi awal, tindakan operator, hasil alignment, rasa gerak (ringan/seret menurut kriteria proyek), status lock, kontinuitas seal, foto atau video, saksi, tanggal, dan nomor NCR bila ada. Jangan menulis “rapi” saja; tulis lokasi dan keadaan yang dapat diperiksa ulang. Jika ada alat ukur, catat titik ukur, satuan, kondisi, dan identitas alat. Nilai yang belum memiliki batas persetujuan diberi status “data untuk review”, bukan “lulus”.

## Langkah 3 — Jalankan urutan kerja dan ulangi secara konsisten

Dengan bukti awal cocok, uji dilakukan dari kondisi aman ke konfigurasi penuh. Bagian ini mencegah operator mengubah urutan untuk menghindari titik seret dan membantu tim membedakan masalah satu panel dari masalah antarmuka.

Mulai dengan area steril dan komunikasi satu komando. Amati panel saat diam: garis pertemuan, posisi terhadap jamb, rel, lantai, dan panel tetangga. Lanjutkan satu urutan operasi sesuai manual sistem: lepaskan pengunci yang memang harus dilepas, gerakkan panel melalui lintasan, parkir atau tumpuk pada posisi yang ditentukan, lalu kembalikan ke posisi tutup. Jangan menambah gaya, alat bantu, atau langkah yang tidak tertulis untuk “membantu” panel.

Pada setiap tahap, pisahkan observasi dari makna. Observasi dapat berupa panel berhenti di titik tertentu, celah berubah, handle tidak kembali, atau seal terlipat. Maknanya baru ditetapkan setelah dibandingkan dengan gambar dan kriteria penerimaan. Untuk lock, catat apakah perangkat mengunci penuh pada posisi yang benar dan dapat dilepas dengan cara normal. Untuk seal, periksa kehadiran, kontinuitas, kerusakan, dan kontak pada titik penutupan yang disyaratkan; jangan menyimpulkan performa akustik atau api dari sentuhan visual.

Ulangi urutan sesuai jumlah siklus yang disetujui proyek. Bila dokumen hanya meminta demonstrasi fungsi tanpa jumlah siklus, tulis kondisi itu dan minta keputusan, bukan menetapkan angka sendiri. Kawan Partisi.co.id, satu demonstrasi yang berhasil tidak menghapus temuan pada pengulangan berikutnya; rekaman berurutan membuat pola masalah terlihat.

## Titik berhenti dan kondisi sebelum dinyatakan lulus

Hold point berarti pekerjaan berhenti sementara sampai pihak berwenang meninjau bukti. Penjelasan ini mencegah dorongan untuk mengakali gejala dan menunjukkan kapan operator harus mengembalikan keputusan kepada perancang, pemasok, QA, atau HSE.

Hentikan uji bila panel mengikat keras, keluar jalur, jatuh, menghasilkan bunyi atau kerusakan baru, lock tidak dapat dilepas secara normal, seal terjepit, atau orang dan aset berada di jalur bahaya. Hentikan pula bila konfigurasi terpasang berbeda dari submittal, rel atau penyangga belum diverifikasi, pintu mengganggu fungsi keluar, atau ada keraguan bahwa komponen bukan produk yang disetujui.

Buka NCR (non-conformance report atau catatan ketidaksesuaian) atau catatan deviasi dengan lokasi, kondisi saat kejadian, urutan terakhir yang berhasil, dan bukti foto/video. Jangan menggerinda, menambah ganjal, memindah hardware, atau mengganti seal sebelum metode koreksi disetujui. [NEEDS PROFESSIONAL REVIEW FOR STRUCTURE, EGRESS, FIRE, ACOUSTIC, OR PRODUCT-SPECIFIC ACCEPTANCE.]

## Verifikasi hasil dan serah terima yang dapat ditelusuri

Serah terima (handover) bukan sekadar tanda tangan; penerima perlu dapat mengulangi operasi dan memahami batasnya. Bagian ini mengubah catatan lapangan menjadi keputusan yang bisa diaudit tanpa mengklaim hasil di luar uji yang benar-benar dilakukan.

Gunakan checklist penutupan berikut:

- konfigurasi dan revisi dokumen cocok dengan kondisi terpasang;
- setiap panel memiliki identitas, arah gerak, dan hasil alignment;
- urutan gerak, posisi parkir, lock, dan seal dicatat pada kondisi normal;
- pengulangan uji, temuan, koreksi, dan uji ulang memiliki referensi yang sama;
- manual operasi, batas penggunaan, daftar suku cadang, dan kontak servis diserahkan;
- item terbuka diberi penanggung jawab dan status, bukan dihapus dari daftar.

Untuk seal, serahkan juga aturan pembersihan dan pemeriksaan yang berlaku hanya pada produk yang benar-benar terpasang. Panduan pemeliharaan Lorient, misalnya, adalah instruksi produk tertentu dan tidak dapat dijadikan interval universal ([panduan pemeliharaan ASSA ABLOY Lorient](https://www.assaabloy.com/au/en/resources/general-information/warranties-and-guarantees/lorient-maintenance-guide)).

Tautkan tindak lanjut ke halaman [contoh partisi lipat di Yogyakarta](/partisi-lipat-yogyakarta.html) atau [contoh partisi lipat di Tuban](/partisi-lipat-tuban.html) hanya bila pembaca membutuhkan konteks jenis sistem; halaman tersebut bukan bukti bahwa proyek Anda memiliki konfigurasi yang sama.

## Mengapa “sudah dicoba sekali” bukan bukti commissioning selesai

Shortcut yang sering dipilih adalah menggerakkan satu panel sekali, melihatnya menutup, lalu menandai semua panel lulus. Cara ini gagal ketika urutan, arah, titik tumpuk, atau gaya operator berbeda dari pemakaian normal. Gejala seperti seret atau lock yang hanya muncul pada pengulangan tidak akan tercatat.

Alternatif yang lebih andal adalah uji per konfigurasi, gunakan operator yang ditunjuk, rekam setiap penyimpangan, dan minta persetujuan ketika batas penerimaan belum tersedia. Teman Partisi.co.id, bukti yang jujur tentang item tertunda lebih berguna daripada tanda lulus yang tidak dapat dipertanggungjawabkan.

## Kesimpulan: putuskan berdasarkan urutan dan bukti, bukan tampilan

Pemeriksaan alignment, gerak, lock, dan seal saat commissioning selesai ketika setiap konfigurasi yang disyaratkan telah dijalankan, diamati, diulang, dan dibandingkan dengan kriteria proyek yang disetujui. Catat titik ukur dan penyimpangan, hentikan pekerjaan pada kondisi berbahaya atau tidak cocok, lalu minta review profesional untuk aspek struktur, egress, kebakaran, akustik, dan kriteria produk.

Langkah berikutnya adalah meminta dokumen penerimaan dan manual sistem yang terpasang, mengisi lembar uji bersama pemasok serta QA, dan menutup setiap NCR dengan uji ulang. Aturan operasinya sederhana: tidak ada angka atau klaim “lulus” tanpa dasar dokumen yang berlaku untuk sistem dan proyek tersebut.
