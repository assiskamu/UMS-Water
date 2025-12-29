# Perubahan Terbaru

## 2025-12-30 (P1–P6 Kegunaan & Kebolehpercayaan)
- Butang utama dikemas kini: “Lompat ke Kira” di header (skrol sahaja) dan “KIRA SEKARANG” dipindah ke akhir input wajib (atau selepas CAPEX/OPEX untuk Mod Full); pipeline dikira disatukan di `runCalculation()` dengan validasi berwarna/auto-skrol dan mesej ralat jelas.
- Senario: status “Belum disimpan/Disimpan HH:MM” berhampiran pengurus senario, butang “SIMPAN SENARIO” baharu berdekatan blok KIRA, simpanan menyertakan `schemaVersion` dan `lastSavedAt` dalam localStorage.
- Input kategori: pilihan “Isi terus (manual)” vs “Muat naik Excel”, butang muat turun templat, import .xlsx menggunakan SheetJS dengan sorotan baris ralat, ringkasan import, dan jadual dipraisi dengan data sah.
- Paparan lanjutan dikurangkan kekusutan: Sensitiviti & Perbandingan A/B/C dipendam sehingga kiraan sah; placeholder “Akan dipaparkan selepas kiraan lengkap.” dipaparkan apabila disembunyikan; carta diberi had tinggi maksimum dan `maintainAspectRatio=false`.

## 2025-12-29 (Input → Kira → Output)
- Tata atur baharu: header dengan butang utama “KIRA SEKARANG”, status dikira, preset/reset pantas, dan blok INPUT (5 langkah WAJIB/Pilihan) sebelum sebarang output; output hanya muncul selepas kiraan dan auto-skrol ke ringkasan.
- Gating paparan lanjutan: perbandingan senario hanya bila ≥2 senario dikira, sensitiviti hanya untuk Mod Full + input kewangan lengkap, eksport PDF digesa untuk kira dahulu; status chip dan mesej kosong mesra pengguna.
- Laporan PDF disusun semula: INPUT didahulukan (kaedah permintaan, bekalan, kewangan, alt supply, CAPEX/OPEX), diikuti OUTPUT, cadangan, dan lampiran; amaran jelas jika input kewangan tidak lengkap, sensitiviti ditunjukkan mengikut syarat.

## 2025-02-04 (Usability Overhaul & Laporan Profesional)
- Quick Start “8 Langkah” kekal di atas (sticky) dengan status badge (Belum lengkap/Lengkap/Sudah dikira), butang “Pergi ke langkah ini”, sorotan seksyen, dan butang “Seterusnya” pada hujung setiap seksyen.
- Togol permintaan “Quick vs Kategori” yang saling eksklusif; input yang tidak dipilih dikunci/kelabu. Senario aktif kini memaparkan status Disimpan/Sudah dikira dengan masa, B/C hanya muncul selepas ditambah, dan perbandingan/sensitiviti disembunyikan sehingga syarat data dipenuhi.
- Penambahbaikan carta & penjelasan: tinggi tetap responsif, legend di bawah, blok “Apa ditunjukkan/Implikasi/Tindakan” di web dan PDF.
- Penjana PDF baharu: pilihan skop (senario aktif/all), tahap (Ringkas/Penuh), pilihan sertakan carta, tajuk kandungan automatik, header dalaman kecil, rajah luar skrin resolusi tinggi, interpretasi rajah, lampiran sensitiviti & CAPEX/OPEX, serta pengendalian data hilang yang mesra.

## 2025-XX-XX
- Tambah pemilih mod 3-lapisan (Quick Estimate, Operational Planning, Full CBA) dengan penyimpanan mod di localStorage.
- Perkenal pengurus senario A/B/C (tambah, gandakan, namakan semula, padam, simpan) serta jadual perbandingan metrik utama.
- Sokong input pantas (populasi/permintaan harian + sumber alternatif ringkas), validasi input, butang “Auto-fill” dan “Baiki input”.
- Tingkatkan analisis kewangan: sensitiviti ±10%, eksport Excel yang menyertakan mod/andaian/senario, laporan PDF boleh merangkumi semua senario.
- Kekalkan jadual CAPEX/OPEX itemised, eksport PDF/Excel, serta laporan profesional dengan ringkasan eksekutif dan lampiran sensitiviti.
