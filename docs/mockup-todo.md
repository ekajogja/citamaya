# Rencana Mockup UI CitaMaya

## Daftar Mockup
1. Main Game Dashboard
2. Learning Path Selection  
3. Lesson Interface
4. Assessment Screen
5. Career Progression
6. Community/Guild View

## 1. Main Game Dashboard
- **Fitur**:
  - Statistik pemain (Level, XP, Cita Coin)
  - Quick access ke 3 menu utama (Belajar, Karir, Komunitas)
  - Notifikasi dan progress tracker
  - Tombol aksi utama (Profile, Settings, Help)
- **Komponen**:
  - Sidebar navigasi
  - Progress bar circular
  - Badge display
  - Notification bell
- **Flow**:
  - Landing page setelah login
  - Navigasi ke semua fitur utama

## 2. Learning Path Selection  
- **Fitur**:
  - Grid 9 kategori utama dengan expandable list
  - Daftar 99 jalur belajar dengan status unlock
  - Filter berdasarkan level/status/kategori
  - Preview jalur belajar
- **Komponen**:
  - Category cards
  - Path list dengan lock/unlock indicator
  - Search/filter bar
  - Path preview modal
- **Flow**:
  - Pilih kategori → expand list paths
  - Klik path untuk preview → mulai belajar

## 3. Lesson Interface
- **Fitur**:
  - Tampilan materi text-based
  - Embed video/referensi eksternal
  - Navigasi modul dan progress
  - Tombol diskusi/help
- **Komponen**:
  - Lesson content area
  - Video/embed container
  - Progress stepper
  - Action buttons
- **Flow**:
  - Baca materi → lanjut ke assessment
  - Bisa save progress/skip

## 4. Assessment Screen
- **Fitur**:
  - Kuis 5-10 soal pilihan ganda
  - Instant feedback system
  - Passing grade indicator (70%)
  - Retry mechanism (max 3x)
- **Komponen**:
  - Question card
  - Answer options
  - Progress tracker
  - Result modal
- **Flow**:
  - Jawab soal → dapat feedback
  - Lulus → unlock next level
  - Gagal → retry/ulangi materi

## 5. Career Progression
- **Fitur**:
  - Hierarki karir 3 level (Pemula-Menengah-Ahli)
  - Persyaratan promosi (study path, reputasi, proyek)
  - Benefit virtual dan dunia nyata
- **Komponen**:
  - Career level diagram
  - Requirement checklist
  - Benefit cards
  - Apply/upgrade button
- **Flow**:
  - Lihat persyaratan karir
  - Penuhi syarat → apply promosi
  - Dapat benefit baru

## 6. Community/Guild View
- **Fitur**:
  - Daftar guild berdasarkan institusi
  - Forum diskusi tematik
  - Fitur kolaborasi proyek
  - Mentor/mentee system
- **Komponen**:
  - Guild cards
  - Discussion threads
  - Project collaboration board
  - Mentor directory
- **Flow**:
  - Join guild → akses forum
  - Buat/join proyek
  - Cari mentor/mentee

## Panduan Styling
- **Pendekatan**: Mobile First (90% akses via smartphone/tablet)
- **Framework**: 
  - Gunakan Bootswatch Vapor theme (https://bootswatch.com/vapor/)
  - CDN Bootstrap 5 + Vapor theme
- **Header Persisten**:
  - Navigation bar tetap di atas
  - Tombol profil/user stats
  - Quick access ke menu utama
- **Warna**:
  - Gunakan warna default dari Bootswatch Vapor theme
  - Utamakan variabel CSS yang disediakan theme
- **Typografi**:
  - Gunakan default typography dari Bootswatch Vapor
  - Utamakan variabel CSS yang disediakan theme
- **Layout**:
  - Full-width untuk mobile
  - Card-based design
  - Consistent spacing (rem units)

## Prioritas Pengembangan
1. Main Dashboard
2. Learning Path Selection
3. Lesson Interface
4. Assessment Screen  
5. Career Progression
6. Community View

## Catatan Tambahan
- **Persyaratan Khusus**:
  - Header persisten dengan:
    - Navigasi utama
    - Tombol profil (modal user stats)
    - Notifikasi
  - Modal profil berisi:
    - Statistik pemain lengkap
    - Progress belajar
    - Achievement badges
- **Technical**:
  - Gunakan CDN Bootswatch Vapor
  - Implementasi mobile-first
  - Optimalkan untuk PWA (Progressive Web App)
- **UX**:
  - Pertahankan nuansa text-based MMORPG
  - Integrasi elemen edukasi di semua screen
  - Sertakan tombol bantuan/FAQ di header
