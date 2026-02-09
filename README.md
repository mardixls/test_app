# README

Ini adalah panduan untuk menjalankan aplikasi API sederhana (FastAPI) di local environment.

## Prasyarat
- Python 3.7+ sudah terinstall.

## Langkah-langkah

1. **Cek apakah Python sudah terinstall**
   - **Windows**: Buka Command Prompt atau PowerShell.
   - **macOS**: Buka Terminal.

   Jalankan perintah:
   ```bash
   python --version
   ```
   > **Note untuk macOS**: Jika `python` tidak dikenal, coba ketik `python3 --version`.
   
   - Jika muncul tulisan seperti `Python 3.x.x` (misal 3.10.1), berarti aman. Lanjut ke step berikutnya.
   - Jika error atau perintah tidak dikenali, download dan install Python dulu dari [python.org](https://www.python.org/downloads/). 
     > **PENTING (Windows):** Saat install, jangan lupa centang opsi **"Add Python to PATH"**.

2. **Buat Virtual Environment (Opsional tapi direkomendasikan)**
   ```bash
   python -m venv venv
   ```

3. **Aktifkan Virtual Environment**
   - Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   
   > **Jika gagal mengaktifkan virtual environment**: Tidak masalah, skip langkah 2 dan 3, lanjut langsung ke step 4. Dependencies akan terinstall secara global di sistem Python Anda.

4. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Jalankan Aplikasi**
   ```bash
   python main.py
   ```

6. **Cek Aplikasi**
   Buka browser dan akses:
   - Root: [http://localhost:8000](http://localhost:8000) -> Output: `{"message": "Hello World"}`
   - Documentation: [http://localhost:8000/docs](http://localhost:8000/docs)
