# 🦇 BatCoin Game

**Tugas pembuatan game 2D adaptasi dari Flappy Bird untuk mata kuliah Grafika Komputer**

## 📖 Deskripsi

BatCoin adalah game 2D yang dikembangkan menggunakan Greenfoot IDE. Game ini merupakan adaptasi dari Flappy Bird dengan tema kelelawar (bat) yang harus terbang melewati pipa-pipa sambil mengumpulkan koin emas. Game ini memiliki sistem level dengan peningkatan kesulitan dan efek suara yang menarik.

## 🎮 Cara Bermain

### Kontrol
- **Arrow Up**: Terbang ke atas
- **Arrow Down**: Terbang ke bawah  
- **Arrow Left**: Bergerak ke kiri
- **Arrow Right**: Bergerak ke kanan

### Tujuan
- Hindari pipa-pipa yang menghalangi
- Kumpulkan koin emas untuk mendapatkan poin tambahan
- Bertahan hidup selama mungkin
- Capai skor tinggi untuk naik level

### Sistem Poin
- Melewati pipa: +1 poin
- Mengumpulkan koin: +5 poin
- Level 2 dimulai setelah mencapai 30 poin

## 🚀 Fitur Game

### 🎯 Gameplay
- **Kontrol Responsif**: Kontrol kelelawar yang smooth dan responsif
- **Sistem Level**: 2 level dengan peningkatan kesulitan
- **Animasi**: Animasi terbang kelelawar yang fluid
- **Sistem Skor**: Penghitungan poin real-time

### 🎨 Visual & Audio
- **Background Dinamis**: Background berubah saat naik level
- **Efek Suara**: 
  - Suara latar siang (Day.mp3) untuk Level 1
  - Suara latar malam (Night.mp3) untuk Level 2
  - Efek suara saat mengumpulkan koin (Points.mp3)
- **Grafik Berkualitas**: Sprite kelelawar dan koin yang menarik

### ⚡ Level System
- **Level 1**: Kecepatan normal, background siang
- **Level 2**: Kecepatan meningkat, background malam (hell theme)

## 🛠️ Teknologi

- **IDE**: Greenfoot
- **Bahasa Pemrograman**: Java
- **Framework**: Greenfoot API
- **Grafik**: PNG sprites dengan animasi
- **Audio**: MP3 format

## 📁 Struktur File

```
BatCoin/
├── Java Files/
│   ├── FlappyWorld.java    # World utama game
│   ├── Player.java         # Karakter kelelawar
│   ├── Pipe.java          # Pipa penghalang
│   ├── Coin.java          # Koin yang bisa dikumpulkan
│   ├── Score.java         # Sistem skor
│   └── GameOver.java      # Layar game over
├── Images/
│   ├── Blue_Flying 1-6.png # Sprite animasi kelelawar
│   ├── goldCoin.png        # Sprite koin
│   ├── pipe.png           # Sprite pipa
│   ├── background2.png    # Background level 1
│   ├── HELL.gif          # Background level 2
│   └── game-over.png     # Sprite game over
└── Sounds/
    ├── Day.mp3           # Background music level 1
    ├── Night.mp3         # Background music level 2
    └── Points.mp3        # Sound effect koin
```

## 🎯 Cara Menjalankan Game

### Prasyarat
1. Install Greenfoot IDE
2. Download Java Development Kit (JDK)

### Langkah Menjalankan
1. Buka Greenfoot IDE
2. Import project BatCoin
3. Klik tombol "Run" di Greenfoot
4. Game akan dimulai otomatis

### Alternatif (Jika ada executable)
1. Double click file `.jar` jika tersedia
2. Atau jalankan melalui command line: `java -jar BatCoin.jar`

## 🎮 Game Mechanics

### Player (Kelelawar)
- Memiliki animasi terbang 6 frame
- Kontrol 4 arah (atas, bawah, kiri, kanan)
- Collision detection dengan pipa
- Sistem hidup/mati

### Pipa
- Bergerak dari kanan ke kiri
- Kecepatan meningkat di level 2
- Spawn otomatis dengan posisi random
- Collision detection dengan player

### Koin
- Spawn setiap 500 frame
- Bergerak dari kanan ke kiri
- Memberikan +5 poin saat dikumpulkan
- Efek suara saat dikumpulkan

### Sistem Skor
- +1 poin per pipa yang dilewati
- +5 poin per koin yang dikumpulkan
- Level 2 dimulai di 30 poin

## 🎨 Asset Credits

### Sprites
- Kelelawar animasi: Blue Flying sprites
- Koin: goldCoin.png
- Pipa: pipe.png
- Background: background2.png, HELL.gif

### Audio
- Background music: Day.mp3, Night.mp3
- Sound effects: Points.mp3

## 👨‍💻 Developer

Game ini dikembangkan sebagai tugas mata kuliah Grafika Komputer menggunakan Greenfoot IDE.

## 📄 Lisensi

Project ini dibuat untuk tujuan edukasi dalam mata kuliah Grafika Komputer.

## 🔗 Dokumentasi

Untuk dokumentasi lengkap, silakan lihat [BatCoin Documentation.pdf](./BatCoin%20Documentation.pdf).

---

**Selamat bermain BatCoin! 🦇💰**

