# Spesifikasi Teknis CitaMaya

## Arsitektur
- **Frontend**: HTML5 + Tailwind CSS + Vanilla JS
- **Backend**: Python Flask
- **Database**: SQLite (MVP), PostgreSQL (production)
- **Hosting**: Vercel/Railway (free tier)

## Struktur Data
```json
{
  "study_paths": {
    "maritim": {
      "levels": [
        {
          "title": "Dasar Navigasi",
          "content": "text...",
          "video_id": "YOUTUBE_ID",
          "questions": ["q1", "q2", "q3"]
        }
      ]
    }
  }
}
```

## API Endpoints
- `GET /paths` - List semua jalur belajar
- `POST /assessment` - Submit jawaban kuis
- `GET /progress` - Dapatkan progres pemain

## Development Setup
1. Install Python 3.10+
2. `pip install -r requirements.txt`
3. `flask run`
