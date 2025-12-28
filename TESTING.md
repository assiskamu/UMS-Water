# Ujian Manual Disyorkan

## Quick Start Stepper
1. Muatkan `index.html` dan pastikan bar “Quick Start Stepper” melekat di bahagian atas dengan 8 langkah bernombor.
2. Klik setiap butang **Pergi ke langkah ini** – halaman tatal ke seksyen sasaran dan sorotan sementara dipaparkan.
3. Cuba butang **Seterusnya** pada setiap kad tanpa mengisi input wajib (contoh langkah 3 atau 4) – mesej ralat sebaris muncul dan tatal tidak berlaku.
4. Isi input minimum (mod Quick, demand/puncak, bekalan JANS) dan tekan **Seterusnya** – tatal berlaku ke langkah berikutnya.
5. Uji butang **Seterusnya** dalam seksyen (bawah kad) – mesti membawa ke langkah seterusnya jika validasi lulus.

## Quick Estimate (1–2 min)
1. Kekalkan mod **Quick Estimate** (lalai) dan klik **⚡ Auto-fill nilai contoh** – medan populasi/per kapita/peak/bekalan asas terisi.
2. Klik **Kira permintaan & banding dengan bekalan** – ringkasan dan graf dikemas kini tanpa ralat konsol.
3. Klik **👀 Papar input terperinci** – seksyen mod lain muncul; klik sekali lagi untuk sembunyi.
4. Isi sumber alternatif pantas (kapasiti + utiliti + CAPEX/OPEX) dan kira semula – jadual CBA memaparkan NPV/BCR/Payback.

## Operational Planning (10–15 min)
1. Pilih mod **Operational Planning** – jadual kategori/alternatif terperinci kelihatan.
2. Isi sekurang-kurangnya satu baris kategori (populasi + per kapita) dan bekalan JANS >0, tekan **Kira** – ringkasan permintaan/bekalan terisi.
3. Tambah dua sumber alternatif dengan utiliti + kebolehpercayaan + CAPEX/OPEX, kira – jadual CBA serta graf NPV/Payback terisi.
4. Gandakan senario A → B melalui **📑 Gandakan**, kira, dan sahkan jadual Perbandingan Senario menunjukkan angka berbeza.

## Full CBA (Advanced)
1. Pilih mod **Full CBA (Advanced)** – jadual CAPEX/OPEX itemised kekal kelihatan.
2. Tambah item CAPEX/OPEX baharu; sahkan jumlah CAPEX/OPEX di kaki jadual berubah.
3. Isi beberapa sumber alternatif lengkap dengan tempoh hayat/discount rate dan kira – NPV/BCR/IRR/Payback dipaparkan.
4. Semak **Analisis Sensitiviti (+/−10%)** – label NPV/BCR untuk asas, CAPEX+10%, OPEX+10%, manfaat+10% dikemas kini selepas kiraan.

## Pengurus Senario & Preset
1. Pastikan hanya senario A wujud pada muat naik awal; klik **🌟 Muatkan contoh (preset)** dan **🔄 Reset senario** untuk melihat kesan pada input.
2. Cipta senario B/C melalui tambah atau gandakan; simpan setiap satu dan muat semula halaman – senario kekal (localStorage).
3. Jadual **Perbandingan Senario A/B/C** memaparkan nilai mengikut kiraan terakhir setiap senario.

## Eksport
1. Klik **📤 Eksport Excel (.xlsx)** selepas kiraan – fail mengandungi helaian Mod_Senario, Kategori, Ringkasan, CBA, CAPEX_OPEX dengan angka terkini.
2. Pilih skop PDF (Senario terpilih/ Semua senario) dan tahap **Ringkas/Penuh**, isi “Disediakan oleh” opsyenal, tekan **Jana Laporan** – PDF dimuat turun tanpa pie chart terpotong.
3. Semak PDF: muka depan, Table of Contents dengan nombor halaman, header kecil dengan tarikh/senario/nombor halaman, graf dengan blok interpretasi (Apa ditunjukkan/Implikasi/Tindakan), dan lampiran sensitiviti + CAPEX/OPEX bagi tahap **Penuh**.
4. Cuba jana PDF tanpa CAPEX/OPEX – seksyen kewangan memaparkan mesej “Analisis kewangan tidak dijana…” tetapi laporan tetap terhasil.

## Regressi pantas
1. Pastikan tiada ralat konsol ketika menukar mod, menambah baris kategori/alternatif, atau memuat semula senario.
2. Uji butang **🛠️ Baiki input** selepas meninggalkan medan wajib kosong – fokus bergerak ke input yang ditanda invalid.
