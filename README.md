# JARVIS AI TERMUX V3.0.0 BETA

![Screenshot](Screenshot_2025-05-10-19-20-29-440_com.termux.jpg)

---

## Fitur

- Mode panel Termux menggunakan **tmux** untuk manajemen jendela dan pane yang fleksibel  
- Informasi **cuaca** terkini  
- **Track IP** untuk pelacakan alamat IP  
- **Kontrol Termux lewat AI** dengan perintah suara dan teks  

---

## Instalasi

Jalankan perintah berikut di Termux secara berurutan:
pkg udpate && pkg upgrade
pkg install neofetch curl jq git ossp-uuid -y
pkg install ncurses-utils xz-utils nodejs -y
pkg install nodejs-lts python python3 -y
pkg install openssl openssl-tool -y
npm -g i bash-obfuscate
pip install rich rich-cli
git clone https://github.com/Lubebansokhekel/JARVISV3
cd JARVISV3
bash JARVISV3.sh

text

---

## Cara Menggunakan Tmux di Termux

- Jalankan tmux dengan perintah:

tmux

text

- Membagi pane vertikal: `Ctrl + b` lalu `%`  
- Membagi pane horizontal: `Ctrl + b` lalu `"`  
- Navigasi antar pane dengan klik pada pane yang diinginkan  
- Keluar dari pane dengan mengetik `exit`  
- Membuat jendela baru: `Ctrl + b` lalu `c`  
- Detach session: `Ctrl + b` lalu `d`  
- Reattach session: `tmux attach`

Tmux membantu mengorganisasi tugas dengan banyak jendela dan pane, meningkatkan produktivitas di Termux.

---

## Donasi

Dukung pengembangan Jarvis AI Termux dengan donasi melalui Saweria:

[https://saweria.co/Galirus](https://saweria.co/Galirus)

Atau beli tool versi 5 seharga 15.000 IDR di:

[https://lynk.id/galirusofficial](https://lynk.id/galirusofficial)

---

Jarvis AI Termux mengubah Termux menjadi asisten cerdas dengan perintah suara dan teks, membantu otomatisasi dan interaksi yang lebih mudah di terminal.
