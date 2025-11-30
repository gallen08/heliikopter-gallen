# Avoid The Block — Pygame Game

Avoid The Block adalah game sederhana berbasis Python + Pygame.
Pemain mengendalikan karakter di bagian bawah layar dan harus menghindari blok-blok jatuh sambil mencoba mengumpulkan skor sebanyak mungkin.

# Gameplay Singkat

Pemain bergerak menggunakan ← →

Blok jatuh secara acak dari atas layar

Jika pemain tertabrak, game over

Jika blok jatuh melewati pemain, itu menambah "miss"

Pemain menang jika skor mencapai 15

Pemain kalah jika jumlah miss mencapai 5

# Fitur Game

Kontrol sederhana dan responsif

Sistem skor & missed counter

Efek deteksi tabrakan (collision)

Opsi fallback apabila gambar tidak ditemukan (diganti warna)

Tampilan kemenangan & kekalahan

# Assets yang Dibutuhkan

Pastikan file berikut ada di direktori Anda:

space.jpg
player.png
block.png


Jika tidak ditemukan, game tetap berjalan dengan gambar pengganti (solid color).

# Persyaratan Sistem

Python 3.8+

Library pygame

Install pygame:

pip install pygame

▶️ Cara Menjalankan

Clone repo:

git clone https://github.com/username/repo-name.git


Masuk ke folder:

cd repo-name


Jalankan game:

python main.py

📁 Struktur Folder
📁 Avoid-The-Block
│── main.py
│── player.png
│── block.png
│── space.jpg
└── README.md

# Kode Utama

Berisi fitur:

Player → bergerak kiri/kanan

Block → turun dari atas, reset posisi bila lewat batas layar

GameSprite → parent class semua sprite

Sistem reset setelah kalah/menang

📝 To Do (Pengembangan selanjutnya)

Menambah efek suara (SFX)

Particle explosion saat kena blok

Menu utama (Start / Exit)

Highscore system

Skin player / warna blok berbeda

Level difficulty naik tiap 5 poin

#Kontribusi

Kontribusi sangat terbuka!
Silahkan buat Issue atau Pull Request jika ingin membantu mengembangkan game ini.

#Lisensi

Proyek ini bebas Anda lisensikan.
Jika butuh rekomendasi (MIT, Apache), beri tahu saya.
