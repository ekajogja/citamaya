# Rencana Mockup UI CitaMaya

## Daftar Mockup

1. Main Game Dashboard
2. Learning Path Selection
3. Lesson Interface
4. Assessment Screen
5. Career Progression
6. Community/Guild View

---

## 1. Main Game Dashboard

- **Fitur**:
  - Statistik pemain (Level, XP, Cita Coin)
  - **Log Aktivitas/Narasi Pusat**: Area utama yang menampilkan *feed* aktivitas terbaru pemain (misalnya, "Anda menyelesaikan quest 'Dasar Navigasi', +150 XP", "Anda berinteraksi dengan NPC 'Kapten Ahab' di Pelabuhan", "Pengumuman Guild: Event 'Pembersihan Sampah Laut' dimulai").
  - Quick access ke 3 menu utama (Belajar, Karir, Komunitas)
  - Notifikasi dan *progress tracker*.
  - Tombol aksi utama (Profile, Settings, Help).
  - **Indikator Status Vital**: Bar untuk status belajar/energi yang digunakan untuk melakukan aksi atau belajar.
- **Komponen**:
  - Sidebar navigasi.
  - Progress bar circular.
  - Badge display.
  - Notification bell.
  - **Activity Feed Panel**: Area *scrollable* untuk log narasi/aktivitas.
  - **Game Status Bar**: Representasi visual untuk status belajar/energi (misalnya, bar).
- **Flow**:
  - Landing page setelah login.
  - Pengguna melihat *update* status dan narasi saat masuk.
  - Opsi untuk melakukan "aksi harian" atau "melanjutkan *quest* belajar".
  - Navigasi ke semua fitur utama.

---

## 2. Learning Path Selection

- **Fitur**:
  - Grid 9 kategori utama dengan *expandable list*.
  - Daftar 99 jalur belajar dengan status *unlock*.
  - Filter berdasarkan level/status/kategori.
  - Preview jalur belajar.
  - **"Skill Tree" Visualisasi**: Representasi *skill tree* sederhana yang menunjukkan keterkaitan antar jalur dan progres.
  - **"Quest Giver" Analogi**: Setiap jalur belajar dapat dianalogikan sebagai "NPC Quest Giver" yang menawarkan serangkaian "Quest" (modul).
- **Komponen**:
  - Category cards.
  - Path list dengan *lock/unlock indicator*.
  - Search/filter bar.
  - Path preview modal.
  - **Skill Tree/Node Display**: Visualisasi progres antar jalur belajar.
  - **"Quest Log" for Learning Paths**: Menunjukkan jalur yang sedang berjalan dan yang telah selesai.
- **Flow**:
  - Pilih kategori → *expand list paths*.
  - Klik *path* untuk preview → mulai belajar.

---

## 3. Lesson Interface

- **Fitur**:
  - Tampilan materi *text-based*.
  - *Embed video/referensi eksternal*.
  - Navigasi modul dan progress.
  - Tombol diskusi/help.
  - **"Lore" Pembelajaran**: Materi teks disajikan seolah-olah bagian dari "lore" atau "pengetahuan" di dunia CitaMaya.
  - **Progress "Quest" yang Jelas**: Indikator visual yang lebih *gamified* untuk menunjukkan progres dalam "quest" (modul) saat ini.
  - **Pilihan Interaktif**: Opsi seperti "telusuri lebih dalam" atau "minta penjelasan lebih lanjut" yang mengarah ke referensi eksternal atau rangkuman.
- **Komponen**:
  - Lesson content area.
  - Video/*embed container*.
  - Progress stepper.
  - Action buttons.
  - **"Lore" / Materi Panel**: Area teks utama dengan gaya yang mendukung nuansa game.
  - **"Objective Tracker" (Mini)**: Menunjukkan tujuan belajar saat ini.
- **Flow**:
  - Baca materi → lanjut ke *assessment*.
  - Bisa *save progress/skip*.

---

## 4. Assessment Screen

- **Fitur**:
  - Kuis 5-10 soal pilihan ganda.
  - *Instant feedback system*.
  - *Passing grade indicator* (70%).
  - *Retry mechanism* (maksimal 3x).
  - **"Ujian Boss" atau "Challenge"**: Presentasikan *assessment* sebagai "tantangan" atau "ujian" untuk menguji pemahaman, bukan sekadar kuis.
  - **Visual Feedback yang Lebih Dramatis**: *Feedback* visual yang kuat (misalnya, ledakan cahaya hijau untuk benar, tanda silang merah yang menonjol untuk salah).
- **Komponen**:
  - Question card.
  - Answer options.
  - Progress tracker.
  - Result modal.
  - **Challenge Title**: Judul yang lebih menarik dari "Kuis".
  - **Result Screen yang Gamified**: Layar hasil yang menunjukkan "Anda berhasil melewati tantangan!" atau "Anda perlu berlatih lebih keras!" dengan statistik yang jelas.
- **Flow**:
  - Jawab soal → dapat *feedback*.
  - Lulus → *unlock next level*.
  - Gagal → *retry/ulangi materi*.

---

## 5. Career Progression

- **Fitur**:
  - Hierarki karir 3 level (Pemula-Menengah-Ahli).
  - Persyaratan promosi (*study path*, reputasi, proyek).
  - Benefit virtual dan dunia nyata.
  - **"Faksi" atau "Guild Karir"**: Lembaga-lembaga karir direpresentasikan sebagai faksi yang berbeda dengan tujuan dan benefit unik.
  - **"Reputation Bar"**: Visualisasi reputasi sebagai bar progres yang meningkat.
- **Komponen**:
  - Career level diagram.
  - Requirement checklist.
  - Benefit cards.
  - Apply/*upgrade button*.
  - **Faction/Guild Cards**: Representasi visual untuk lembaga karir.
  - **Reputation Tracker**: Bar progres atau angka yang jelas.
- **Flow**:
  - Lihat persyaratan karir.
  - Penuhi syarat → *apply* promosi.
  - Dapat benefit baru.

---

## 6. Community/Guild View

- **Fitur**:
  - Daftar guild berdasarkan institusi.
  - Forum diskusi tematik.
  - Fitur kolaborasi proyek.
  - Mentor/*mentee system*.
  - **"Markas" Guild/Institusi**: Setiap guild bisa memiliki "markas" virtual yang menampilkan statistik, papan pengumuman, dan anggota.
  - **Chat Log/Forum yang Dinamis**: Tampilan *chat/forum* yang lebih mirip log percakapan dalam game, bukan forum web tradisional.
- **Komponen**:
  - Guild cards.
  - Discussion threads.
  - Project collaboration board.
  - Mentor directory.
  - **Guild Hall Dashboard**: Tampilan umum guild.
  - **Real-time Chat/Discussion Feed**: Area *chat* yang lebih interaktif.
- **Flow**:
  - *Join guild* → akses forum.
  - Buat/*join* proyek.
  - Cari mentor/*mentee*.

---

## Panduan Styling

- **Pendekatan**: Mobile First (90% akses via smartphone/tablet).
- **Framework**:
  - Gunakan Bootswatch Vapor theme (<https://bootswatch.com/vapor/>).
  - CDN Bootstrap 5 + Vapor theme.
- **Pendekatan Visual MMORPG Text-based**:
  - **Simulasi Terminal/Konsol**: Masukkan elemen desain yang menyerupai antarmuka terminal atau konsol lawas (misalnya, *background* gelap, *font monospace* untuk teks-teks penting, *highlight* dengan warna terang).
  - **Minimalis dengan Aksen Game**: Setiap elemen (tombol, *card*, *progress*) harus memiliki aksen yang membuatnya terasa seperti bagian dari *interface* game. Pertimbangkan ikon-ikon kecil yang relevan dengan MMORPG (misalnya, ikon pedang untuk "aksi", ikon buku untuk "belajar").
- **Header Persisten**:
  - Navigation bar tetap di atas.
  - Tombol profil/user stats.
  - Quick access ke menu utama.
- **Warna**:
  - Gunakan warna *default* dari Bootswatch Vapor theme.
  - Utamakan variabel CSS yang disediakan theme.
  - Pastikan kontras tinggi untuk keterbacaan *text-based*.
- **Typografi**:
  - Gunakan *default typography* dari Bootswatch Vapor.
  - Utamakan variabel CSS yang disediakan theme.
  - Gunakan *font* yang lebih *game-like* atau *monospace* untuk bagian-bagian tertentu yang menunjukkan narasi/log game.
- **Layout**:
  - Full-width untuk mobile.
  - Card-based design.
  - Consistent spacing (rem units).

---

## Prioritas Pengembangan

1. Main Dashboard
2. Learning Path Selection
3. Lesson Interface
4. Assessment Screen
5. Career Progression
6. Community View

---

## Catatan Tambahan

- **Persyaratan Khusus**:
  - Header persisten dengan:
    - Navigasi utama.
    - Tombol profil (*modal user stats*).
    - Notifikasi.
  - Modal profil berisi:
    - Statistik pemain lengkap.
    - Progress belajar.
    - Achievement badges.
  - **Visualisasi Karakter Mini**: Di header atau sidebar, mungkin ada ikon sederhana atau *avatar* kecil yang merepresentasikan karakter pemain, yang *statusnya* berubah berdasarkan aksi atau progress.
  - **"Aksi" Utama yang Lebih Menarik**: Tombol-tombol utama (Belajar, Karir, Komunitas) perlu diberi label yang lebih "gamified" (misalnya, "Quest Log", "Ascension Path", "Social Hub").
- **Technical**:
  - Gunakan CDN Bootswatch Vapor.
  - Implementasi *mobile-first*.
  - Optimalkan untuk PWA (*Progressive Web App*).
- **UX**:
  - Pertahankan nuansa *text-based MMORPG*.
  - Integrasi elemen edukasi di semua screen.
  - Sertakan tombol bantuan/FAQ di header.
  - **Audio Feedback (opsional)**: Pertimbangkan *sound effect* kecil untuk aksi, *progress*, atau *feedback*.
  - **Animasi Mikro**: Animasi kecil untuk *progress bar*, *button hover*, atau *feedback* pada kuis akan membuat UI terasa lebih hidup dan responsif.
  - **Naratif "Dunia" Konsisten**: Setiap elemen teks, mulai dari judul hingga *tooltip*, harus mempertahankan nuansa *text-based MMORPG* CitaMaya.

---

## Shared/Reusable Components (Disarankan di file terpisah: `components.md` atau `shared-ui.md`)

Untuk memudahkan pengembangan dan pemeliharaan, elemen-elemen UI yang muncul berulang kali di berbagai *screen* dapat didefinisikan sebagai komponen terpisah. Contohnya:

1. **Header Navigasi**:
    - Logo/Nama Game.
    - Tombol Navigasi Utama (Dashboard, Belajar, Karir, Komunitas).
    - Area Status Pengguna (Level, XP, Cita Coin - bisa di *modal* atau *popover*).
    - Tombol Notifikasi.
    - Tombol Profil (memanggil *modal* profil).
    - Tombol Bantuan/Settings.

2. **Modal Profil Pengguna**:
    - Avatar/Ikon Karakter.
    - Statistik Pemain Lengkap.
    - Progress Belajar (Jalur aktif, persentase).
    - *Achievement Badges*.

3. **Progress Bar Gamified**:
    - Visualisasi progres (circular/linear) dengan label XP atau persentase.
    - Bisa digunakan untuk progres level karakter, progres jalur belajar, atau progres quest.

4. **Badge/Achievement Display**:
    - Komponen untuk menampilkan *badge* atau pencapaian yang telah diraih pemain, dengan ikon dan teks.

5. **Card Konten Game/Edukasi**:
    - *Card* dasar untuk menampilkan informasi (misalnya, detail jalur belajar, ringkasan quest, atau informasi karir).
    - Memiliki header, body, dan *action buttons* yang konsisten.

Mendefinisikan komponen-komponen ini di file terpisah akan memungkinkan pengembang untuk merakit *mockup* dengan lebih cepat dan memastikan konsistensi UI di seluruh platform.
