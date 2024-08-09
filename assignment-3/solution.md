## Better Database Environment Clasification
1. Memiliki environment terpisah antara development dan production dengan jelas
2. **TIDAK** memberikan akses database production ke developer, hanya ke DBA (Database Administrator)
3. Pastikan kode migrasi yang dijalankan berjalan dengan baik di env development

## Better Backup System
1. Backup database secara berkala
2. **Uji Coba** hasil backup apakah bisa direstore atau tidak secara berkala
3. Memiliki logs payload dari setiap request yang dibuat, agar dapat di repopulate data" yang mungkin perlu dikembalikan
