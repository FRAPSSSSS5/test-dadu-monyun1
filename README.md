# 🎲 DADU MONYUN — Deploy Guide

## Cara Deploy ke Railway (HTTPS untuk TikTok Live Studio)

---

## Langkah 1 — Upload ke GitHub

1. Buka [github.com](https://github.com) → Login / Daftar
2. Klik tombol **+** (pojok kanan atas) → **New repository**
3. Nama repo: `dadu-monyun`
4. Pilih **Public**
5. Klik **Create repository**
6. Upload semua file ini ke repo (drag & drop atau pakai GitHub Desktop)

---

## Langkah 2 — Deploy ke Railway

1. Buka [railway.app](https://railway.app)
2. Klik **Login** → pilih **Login with GitHub**
3. Klik **New Project** → **Deploy from GitHub repo**
4. Pilih repo `dadu-monyun`
5. Railway otomatis deploy — tunggu 1-2 menit
6. Klik **Settings** → **Networking** → **Generate Domain**
7. Dapat URL seperti: `https://dadu-monyun-production.up.railway.app` ✅

---

## Langkah 3 — Gunakan di TikTok Live Studio

- **URL Utama (untuk overlay):** `https://dadu-monyun-xxx.up.railway.app`
- **URL Admin (untuk kontrol):** `https://dadu-monyun-xxx.up.railway.app/admin`
- **Password Admin default:** `monyun123`

Di TikTok Live Studio → tambahkan Browser Source → masukkan URL di atas.

---

## Environment Variables (Opsional)

Di Railway → Settings → Variables, bisa tambahkan:
- `ADMIN_PASSWORD` = password_kamu (ganti dari default monyun123)
