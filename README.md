# CitaMaya - Text-based Educational MMORPG

Platform belajar berbasis game dengan inspirasi:
- **Gameplay**: Torn (text-based MMORPG)
- **Pembelajaran**: Duolingo & Codecademy
- **Komunitas**: Discord

## Dokumen Inti

1. **[Visi & Strategi](docs/vision.md)**  
   - Filosofi "Belajar Tanpa Sadar Belajar"  
   - Analisis kompetitif vs platform lain
   - Roadmap pengembangan

2. **[Desain Game](docs/game-design.md)**  
   - 99 jalur belajar & karir  
   - Sistem assessment multimodal  
   - Mekanika text-based MMORPG

3. **[Executive Brief](docs/business/executive-brief.md)**  
   - Model bisnis dan monetisasi  
   - Proyeksi pasar edtech  
   - Strategi partnership

## Struktur Proyek
```
/citamaya
├── docs/
│   ├── vision.md          # Dokumen visi dan strategi
│   ├── game-design.md     # Spesifikasi gameplay
│   ├── mvp-docs.md        # Spesifikasi teknis MVP
│   ├── full-dev/          # [FUTURE] Dokumentasi pengembangan lengkap
│   └── business/          # [FUTURE] Materi bisnis & partnership
│
├── src/                   # Kode sumber utama
│   ├── app/               # Aplikasi Flask
│   ├── static/            # Aset frontend (CSS, JS)
│   └── templates/         # File template HTML
│
├── data/                  # Konten dan konfigurasi game
│   ├── courses/           # Materi pembelajaran
│   ├── assessments/       # Bank soal
│   └── user_data/         # Data pemain (development)
│
├── tests/                 # Skrip testing
├── scripts/               # Skrip utilitas
└── README.md              # Dokumentasi utama
```

**Keterangan Struktur**:
1. `docs/` - Semua dokumentasi proyek
2. `src/` - Kode implementasi utama
3. `data/` - Konten game yang bisa diubah tanpa coding
4. `tests/` - Untuk pengujian otomatis
5. `scripts/` - Skrip bantu development

## Kontribusi
Lihat [Panduan Kontribusi](CONTRIBUTING.md) untuk detail cara berkontribusi pada proyek ini.
