# oxygen_ladang

**oxygen_ladang** adalah skrip ladang interaktif untuk _FiveM QBCore Framework_, memungkinkan pemain mengambil tanaman seperti **ganja (weed)** dan **kokain (cocaine)** dari lokasi yang telah ditentukan di map. Sistem ini dilengkapi dengan anti-exploit, sistem prop dinamis, serta integrasi dengan `ox_target` dan `ox_lib`.

---

## 📦 Fitur

- ✅ Interaksi dengan tanaman menggunakan `ox_target`
- 🔄 Respawn otomatis prop ketika jumlahnya sedikit
- 🧠 Skill check sebelum bisa mengambil tanaman
- 🧼 Otomatis hapus prop ketika pemain menjauh
- 🚔 Cek jumlah polisi online sebelum memperbolehkan farming
- 🛡️ Perlindungan anti-exploit untuk mencegah abuse event dari luar zona

---

## 🗺️ Lokasi Ladang

Didefinisikan dalam `config.lua` melalui `Config.CircleZones`:

| Nama Zona | Koordinat                 | Objek Prop                  | Item yang Diberikan  |
| --------- | ------------------------- | --------------------------- | -------------------- |
| WeedField | `294.19, 4302.28, 45.29`  | `prop_weed_02`              | `weedplant_branch`   |
| CokeField | `2272.58, 4963.41, 41.53` | `bkr_prop_coke_tablepowder` | `cocainplant_cocain` |

---

## ⚙️ Item
- Untuk item anda bisa sesuaikan dengan item anda sendiri di Config.CircleZones >> item

## ⚙️ Instalasi

1. **Salin folder** `oxygen_ladang` ke dalam folder `resources/[qb]`.
2. Tambahkan ke `server.cfg`:

   ```cfg
   ensure oxygen_ladang
   ```
## GAMBAR

## Cocain
<img width="1919" height="1079" alt="Screenshot 2025-08-07 150900" src="https://github.com/user-attachments/assets/b60c10ec-d285-4f9b-91a8-268880ad439b" />
<img width="1919" height="1079" alt="Screenshot 2025-08-07 150819" src="https://github.com/user-attachments/assets/f06b8fe9-b8ae-4004-ae74-9e2571ea615c" />
## Weed
<img width="1919" height="1079" alt="Screenshot 2025-08-07 150939" src="https://github.com/user-attachments/assets/5d0635a2-5374-42b9-8545-6c9769749b7f" />
<img width="1916" height="1079" alt="Screenshot 2025-08-07 150952" src="https://github.com/user-attachments/assets/50c7c5c6-9cd5-49f5-9d35-2e071556c333" />
