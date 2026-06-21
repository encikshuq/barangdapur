# DapurList Family v1.0

Webapp mobile-first untuk keluarga urus senarai barang dapur, status belian, resit dan claim duit.

## Cara cuba sekarang
1. Buka `index.html` di browser.
2. Masuk nama keluarga, nama pengguna dan PIN.
3. Buat senarai baru.
4. Tick barang dan assign pembeli.
5. Update status barang: perlu beli, dah beli, tiada stok atau diganti.
6. Upload resit dan set claim.

## Nota penting
Versi ini berjalan dengan localStorage untuk demo cepat. Data tersimpan dalam telefon/browser yang sama sahaja.
Untuk sync suami-isteri secara live, deploy ke hosting dan sambung Supabase menggunakan `sql/supabase_schema.sql`.

## Fail utama
- `index.html` - app utama
- `assets/style.css` - design smartphone
- `assets/app.js` - logic app demo
- `manifest.json` dan `sw.js` - PWA asas
- `sql/supabase_schema.sql` - database Supabase

## Cadangan domain
- dapurlist.restuharmoni.com
