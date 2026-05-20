# Laporan Hasil Praktikum: Final Project Aplikasi Berbasis Container

## Identitas Mahasiswa

- **Nama:** Tito Putra Bamulo
- **NIM:** 2415354011
- **Kelas/Rombel:** TRPL C
- **Tanggal Praktikum:** 20 Mei 2026

---

## Teknologi & Tools yang Digunakan

- **Sistem Operasi:** Linux (Pop os)
- **Containerization:** Docker & Docker Hub
- **Bahasa Pemrograman / Framework:** Node.js
- **Tools Lain:** VS Code, Git, Postman

---

## Langkah 1: Run docker compose

```bash
# Contoh perintah terminal yang dijalankan
sudo docker compose up -d -- build (untuk compose file docker-compose.yml yang sudah di configurasi)
sudo docker ps (untuk melihat apakah container yang di buat sudah berjalan)
```

**Dokumentasi/Screenshot:**
![Check container](img/check.png)
![Check backend run](img/run.png)

---

### Langkah 2: CRUD using postman

![Create: ](img/post.png.png)
![Read: ](img/read.png)
![Update: ](img/update.png.png)
![Delate: ](img/delate.png.png)

---

### Langkah 3: Check Docker images and volume

![volume and images: ](img/images&volume.png.png)

## Kesimpulan

Docker sangat berguna dalam pembuatan software terutama dalam pembuatan bersama tim untuk meyamakan dependency
