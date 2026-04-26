# bbm-calculator
Aplikasi bbm untuk bantu akuh

## Update Harga BBM

Harga BBM disimpan di file [`prices.json`](prices.json). Untuk mengubah harga:

1. Buka file `prices.json` di GitHub (klik edit ✏️)
2. Ubah nilai `"price"` sesuai harga terbaru
3. Perbarui field `"updated"` dengan tanggal hari ini (format `YYYY-MM-DD`)
4. Commit langsung — perubahan otomatis live di GitHub Pages tanpa setup apapun

Contoh isi `prices.json`:
```json
{
  "updated": "2025-04-26",
  "source": "Pertamina",
  "prices": [
    { "name": "Solar",     "price": 6800  },
    { "name": "Pertalite", "price": 10000 },
    { "name": "Dexlite",   "price": 23600 },
    { "name": "Pertamax",  "price": 12600 }
  ]
}
```
