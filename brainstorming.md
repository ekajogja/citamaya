# Brainstorming CitaMaya - belajar dan meniti karir di dunia virtual cerdas

Saya mau bangun sebuah text based game semacam Torn, Politics & War, NationStates, dsb. Avatar pemain ini bisa memilih dia mau belajar dan berkarir apa saja, anggap saja dia bisa memilih di antara 99 study path dan 99 career path. Dia bisa memilih belajar di antara 9 kampus dan bekerja di antara 9 lembaga default. Nantinya, bisa mendirikan kampus atau lembaga sendiri jika levelnya sudah cukup tinggi. Dia bisa mendirikan atau bergabung di asosiasi mahasiswa dan asosiasi profesional.
Secara umum, mestinya avatar belajar dulu hingga memperoleh level kompetensi tertentu, baru bisa melamar pekerjaan, tetapi ia bisa memilih untuk langsung bekerja dan kemudian belajar sambil bekerja sesuai kesempatan yang diberikan lembaga.
Yang menjadi value sesungguhnya dari game ini adalah, ketika avatar belajar, maka pemain diminta untuk menyelesaikan sebuah bacaan sekitar 1200 kata atau video pendek yang setara, dan kemudian ada ujian yang harus pemain kerjakan untuk memperoleh nilai. Jadi game ini sesungguhnya adalah open course yang terselubung. Sebisa mungkin pemain tidak merasa bahwa ia sedang mengikuti open course, sehingga ia merasa sangat fun karena sedang bermain game, padahal sebetulnya dia belajar materi-materi nyata. Saya seorang programmer python yang paham git, paham deployment, paham cukup lumayan mengenai software development  dan digital product management untuk produk-produk terkait pendidikan dan profesional, tetapi di dunia game saya hanya seorang pemain saja, jadi saya relatif buta mengenai dunia game product management. Bantu saya menyusun semua dokumen yang dibutuhkan. Oiya, saya tidak suka bekerja dengan tim yang terlalu besar, anggap saja tim development game ini cuma 5 - 10 orang saja.

Sebelumnya, silakan jika ada pertanyaan2 yang ingin kamu ajukan
---

Proyek yang sangat menarik! Konsep "gamifikasi pendidikan" dengan pendekatan stealth learning ini punya potensi besar. Sebelum saya bantu menyusun dokumen-dokumennya, ada beberapa pertanyaan krusial yang perlu dijawab dulu:
Target Audience & Content:

Siapa target utamanya? Mahasiswa, fresh graduate, profesional yang ingin upskill, atau campuran?
Untuk 99 study path dan 99 career path - apakah sudah ada gambaran kategori besarnya? (misal: teknologi, bisnis, seni, sains, dll)
Konten pembelajaran 1200 kata/video pendek - siapa yang akan membuat? Tim internal atau kerjasama dengan institusi pendidikan?

Game Mechanics & Progression:
4. Sistem level/XP-nya bagaimana? Apakah mirip RPG tradisional atau lebih ke skill-based progression?
5. Monetization model yang diinginkan apa? Freemium, subscription, atau full free?
6. Social features seberapa penting? (ranking, kompetisi antar pemain, kolaborasi)
Technical & Resource:
7. Platform target: web-based, mobile app, atau keduanya?
8. Berapa lama timeline development yang realistis menurutmu?
9. Budget range untuk development (tidak perlu exact, tapi ballpark figure)?
Content Management:
10. Bagaimana sistem update konten pembelajaran? Apakah perlu CMS khusus?
11. Sistem penilaian ujian - otomatis atau ada review manual?
Jawaban ini akan sangat mempengaruhi struktur dokumen dan roadmap yang akan saya susun.

---

1. Target utamanya adalah mereka yang ingin belajar tapi tidak punya akses ke lembaga pendidikan formal di Indonesia karena berbagai alasan, misal karena kapasitas pelajar/mahasiswa terlalu kecil, biaya pendidikan terlalu besar, waktu yang tidak bisa fulltime karena harus bekerja atau merawat keluarga, kualifikasi diri yang tidak cukup sebagai syarat menempuh pendidikan, dsb. Jadi ini adalah lembaga pendidikan alternatif yang adaptif terhadap situasi tiap-tiap orang. Ini mirip dengan open course pada umumnya, bedanya adalah kemasannya game, sehingga orang yang "malas belajar dan lebih suka bermain" juga bisa tertarik.
2. Ambil dari dunia nyata saja, terutama untuk konteks Indonesia dan dengan memprediksi trayektori dunia pendidikan dan karir ke depan. Secara pribadi saya ingin mengutamakan (selain yang basic seperti ekonomi, hukum, politik, pertahanan) bidang-bidang yang ke depan semakin bernilai tinggi seperti: manajemen lingkungan, teknologi maritim, teknologi pertanian, kehutanan, energi terbarukan, bioteknologi, ekonomi digital, dsb. Tentu saja path yang menyenangkan seperti seni, sastra, entertainment, media sosial juga boleh, tetapi sedikit saja.
3. Bisa tim internal, bisa kerjasama, tetapi pada dasarnya akan mengambil yang tersedia di internet, baik di Youtube, open course, dsb. Saya pikir resources yang ada di internet sudah sangat banyak. Materi yang tidak ada di internet akan kita coba minta untuk disediakan oleh para dosen atau mahasiswa atau lembaga yang peduli dengan kemerdekaan akses belajar melalui kerjasama.
4. Menurutmu sebaiknya bagaimana? Ingat juga bahwa di game ini selain study path juga ada career path. Yang jelas pemain harus bebas memilih apakah dia akan fast leveling up atau mau lebih casual.
5. Yang jelas game ini bukan pay to win. Saya lebih suka monetisasi untuk kosmetik, atau untuk antar pemain mengumpulkan modal bersama untuk bikin in game event, mendirikan kampus atau perusahaan in game, dst. Bisa juga membuka peluang bagi lembaga pendidikan yang mau mempromosikan programnya, misalnya di game ini ada study path untuk bikin startup, jika pemain ingin benar2 membuat startup di dunia nyata maka ada iklan untuk program inkubasi atau mentoring atau investasi atau apapun. Perusahaan nyata juga bisa membuka lowongan kerja dan pemain yang melamar bisa dicek kualifikasi berdasarkan capaiannya di game, atau semacamnya. Artinya seorang pemain bisa menjadi seorang legend tanpa mengeluarkan uang sama sekali, tapi tentu gengsinya akan kalah dibanding yang aktif spending. Oiya untuk monetisasi bisa pakai sistem koin saja, tiap koin misalnya seharga 2000 rupiah, minimal pembelian 5 koin. Setiap pekan, tiap pemain maksimal bisa membeli 100 koin saja untuk mencegah penyalahgunaan game ini untuk money laundry.
6. Seperti Politics & War, social features penting untuk menjaga agar pemain merasa memiliki eksistensi di dalam game. Apalagi jika sistem pendidikan dan birokrasi di Indonesia masih seburuk sekarang, pemain merasa sangat nyaman berinteraksi di dalam game dan bisa bersosialisasi dengan like-minded.
7. Web-based saja untuk sementara, untuk mobile pakai PWA saja.
8. Ini awalnya jadi pet project saja, kemudian setelah ada MVP saya akan tawarkan kerjasama dengan developer lain, jadi modelnya benar2 from scratch dan passion project, tidak langsung mengarah ke startup atau game company. Dan jujur, saya tidak punya uang atau modal finansial.
9. Sama seperti poin 8.
10. Sebaiknya gimana ya? Pakai headless cms yang ada atau gimana ya? Apa mungkin pakai sistem Google Workspace?
11. Otomatis dengan AI, saya familiar dengan OpenRouter API. Tentu untuk awal gunakan model-model yang free supaya tidak menjadi beban finansial. Jika kelak ada investor, bisa saja ada tim manual review yang digaji.