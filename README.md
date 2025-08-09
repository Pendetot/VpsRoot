# LazyDev - VPS Root Access Setup

Script untuk mengaktifkan akses root di VPS yang ga dikasih akses root langsung (AWS, GCP, dll).

## Cara Pakai

### 1. Login ke VPS
```bash
ssh username@ip_vps
```

### 2. Jadi Root Dulu
```bash
sudo su
cd
```

### 3. Download & Jalankan Script
```bash
wget -qO- -O vpsroot.sh https://raw.githubusercontent.com/BangsNgek/JualanSSH/main/vpsroot.sh && bash vpsroot.sh
```

### 4. Masukin Password Baru
- Script bakal minta password baru buat root
- Bikin password yang kuat tapi gampang diingat
- Simpen info login yang muncul

## Yang Didukung
- AWS EC2
- Google Cloud Platform  
- DigitalOcean
- Vultr, Linode, Azure
- Provider cloud lainnya