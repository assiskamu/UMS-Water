# Ujian Manual Disyorkan

## Persediaan umum
1. Buka `index.html` di pelayar.
2. Pastikan mod dipilih (Quick/Operational/Full) kelihatan dalam kad “Pemilih Mod & Senario”.
3. Sahkan tiada ralat konsol semasa memuat halaman.

## Quick Estimate (1–2 min)
1. Pilih mod **Quick Estimate**.
2. Klik **Auto-fill nilai contoh** (sepatutnya mengisi populasi, per kapita, faktor puncak dan bekalan asas).
3. Tekan **Kira permintaan & banding dengan bekalan** – ringkasan perlu terisi, graf dikemas kini, tiada amaran input.
4. Uji input tidak sah: kosongkan populasi/permintaan, tekan kira – mesej validasi muncul; butang **Baiki input** fokus ke medan bermasalah.
5. Isi CAPEX/OPEX pantas untuk sumber alternatif ringkas, kira semula – NPV/BCR/payback dipaparkan di jadual sumber alternatif.

## Operational Planning (10–15 min)
1. Tukar ke mod **Operational Planning** – jadual kategori dan sumber alternatif terperinci muncul.
2. Masukkan sekurang-kurangnya satu baris kategori (populasi + per kapita) dan bekalan JANS, kira – ringkasan permintaan/bekalan dikira.
3. Tambah beberapa baris sumber alternatif (dengan utiliti dan jangka hayat), kira – jadual CBA, graf NPV & payback terisi.
4. Eksperimen faktor puncak di luar julat 1.2–1.5 – amaran ditunjukkan tetapi pengiraan masih berjalan.
5. Simpan senario melalui **💾 Simpan senario**, kemudian gandakan melalui **📑 Gandakan** dan pastikan jadual perbandingan menunjukkan nilai A/B.

## Full CBA (Advanced) (30–60 min)
1. Tukar ke mod **Full CBA (Advanced)** – jadual CAPEX/OPEX itemised kekal kelihatan.
2. Tambah/ubah item CAPEX/OPEX, pastikan jumlah dikemas kini dan diambil kira dalam CBA.
3. Isi beberapa sumber alternatif dengan CAPEX, OPEX, utiliti; tetapkan tempoh analisis dan kadar diskaun, kira – NPV, BCR, IRR, payback wujud.
4. Semak bahagian **Analisis Sensitiviti** – nilai asas, CAPEX+10%, OPEX+10%, manfaat+10% dikemaskini selepas pengiraan.

## Pengurus senario & eksport
1. Buat tiga senario (A/B/C) dengan input berbeza, simpan setiap satu. Tutup/ buka semula halaman – senario kekal (localStorage).
2. Jadual **Perbandingan Senario A/B/C** memaparkan angka berbeza bagi setiap senario yang telah dikira.
3. Klik **📤 Eksport Excel (.xlsx)** – fail mengandungi helaian Mod_Senario, Kategori, Ringkasan, CBA, CAPEX_OPEX.
4. Pilih skop PDF (senario aktif atau semua senario), tekan **Jana Laporan** – PDF berjaya dimuat turun; jika “Semua senario” dipilih, jadual perbandingan muncul dalam laporan.
