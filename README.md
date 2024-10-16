# Android Architecture Samples

Dokumen ini menjelaskan berbagai contoh pendekatan arsitektur dalam pengembangan aplikasi Android,
dengan fokus pada aplikasi "To-Do" yang diimplementasikan dengan variasi kecil di setiap cabangnya.

Contoh ini menggunakan Jetpack Compose untuk antarmuka pengguna, arsitektur aktivitas tunggal dengan Navigation Compose,
dan layer presentasi yang menggabungkan ViewModel untuk setiap fitur.

Arsitektur ini juga mendukung operasi asinkron dengan Flow dan coroutines,
mengimplementasikan data layer menggunakan Room (untuk sumber lokal) dan data palsu untuk sumber remote.

Penggunaan Hilt memfasilitasi dependency injection,
serta adanya berbagai pengujian seperti unit, integrasi, dan e2e.

Proyek ini ditujukan untuk pengembang dengan tingkat keahlian menengah hingga lanjut,
yang ingin mempelajari struktur aplikasi yang mudah diuji dan dikelola.