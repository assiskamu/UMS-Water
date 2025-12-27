# Kalkulator Permintaan & Bekalan Air UMS – Laporan Profesional

Repositori ini menyokong kalkulator permintaan–bekalan air UMS (GitHub Pages) dengan penjanaan PDF profesional terus daripada data terkini pengguna.

## Cara Menggunakan Laporan Profesional

1. Isi input permintaan, bekalan (JANS), sumber alternatif serta jadual CAPEX/OPEX (jika perlu).
2. Tekan **“Kira permintaan & banding dengan bekalan”** supaya semua jadual/graf dikemas kini.
3. Klik **“Jana Laporan”** untuk menghasilkan PDF A4 ~10 halaman menggunakan jsPDF (fail `Laporan_UMS_Water_Profesional_YYYY-MM-DD.pdf`). Cover bertema air, isi kandungan automatik, header/footer serta nombor halaman disertakan secara konsisten.

Nota:
- Semua perenggan naratif diratakan (justify) dengan margin kemas (±25 mm).
- Graf diambil terus daripada kanvas kalkulator menggunakan `toDataURL()` supaya tidak pecah ketika dicetak.
- Penafian automatik dipaparkan di bahagian akhir laporan.
