# Kalkulator Permintaan & Bekalan Air UMS – Laporan Profesional

Repositori ini menyokong kalkulator permintaan–bekalan air UMS (GitHub Pages) dengan dua mod laporan:

1. **Jana Laporan PDF (ringkas)** – butang sedia ada yang menggunakan jsPDF.
2. **Laporan Profesional (HTML → PDF)** – laporan A4 ~10 halaman dengan muka depan profesional, isi kandungan, header/footer, teks rata (justify), jadual dan graf beresolusi tinggi.

## Cara Menggunakan Laporan Profesional

1. Isi input permintaan, bekalan (JANS), sumber alternatif serta jadual CAPEX/OPEX (jika perlu).
2. Tekan **“Kira permintaan & banding dengan bekalan”** supaya semua jadual/graf dikemas kini.
3. Pilih salah satu:
   - **Preview Laporan Profesional**: buka modal pratonton A4. Anda boleh skrol seluruh laporan sebelum memuat turun.
   - **Muat Turun Laporan Profesional (PDF)**: menjana PDF menggunakan html2pdf (fail `Laporan_UMS_Water_Profesional_YYYY-MM-DD.pdf`). Header/footer, tarikh jana dan nombor muka surat ditambah secara automatik (muka surat 2 dan seterusnya).
4. Pastikan pelayar memuatkan CDN `html2pdf.js` (disertakan dalam `index.html`). Jika pustaka gagal dimuat, amaran akan dipaparkan.

Nota:
- Semua perenggan naratif diratakan (justify) dengan margin 25 mm dan fon gaya laporan (Georgia/Times).
- Graf diambil terus daripada kanvas kalkulator menggunakan `toDataURL()` supaya tidak pecah ketika dicetak.
- Penafian automatik dipaparkan di bahagian akhir laporan.
