# Quickstart

Ini adalah panduan untuk menjalankan aplikasi API sederhana (FastAPI) di local environment.

## Prasyarat
- Python 3.7+ sudah terinstall.

## Langkah-langkah

1. **Buat Virtual Environment (Opsional tapi direkomendasikan)**
   ```bash
   python -m venv venv
   ```

2. **Aktifkan Virtual Environment**
   - Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Jalankan Aplikasi**
   ```bash
   python main.py
   ```

5. **Cek Aplikasi**
   Buka browser dan akses:
   - Root: [http://localhost:8000](http://localhost:8000) -> Output: `{"message": "Hello World"}`
   - Documentation: [http://localhost:8000/docs](http://localhost:8000/docs)
