# LAPORAN UTS PEMROGRAMAN BERGERAK | SISTEM GerasiKomputer.ID | MeyloindasariW.W_2205101117

Aplikasi edukasi generasi komputer berbasis **Android Native (XML + Kotlin)**. Dibuat sebagai tugas **UAS Mata Kuliah Pemrograman Bergerak**.

**Fitur Unggulan**  
Aplikasi menerapkan arsitektur **minimalis 3-layer** dengan **Loading Screen otomatis** dan navigasi **List → Detail** yang smooth.

**Flow Aplikasi:**
- **Loading Screen**: Splash screen 2 detik dengan Material Design
- **List Generasi**: 5 generasi komputer dengan ikon representatif  
- **Detail Generasi**: Informasi lengkap (tahun, teknologi, contoh komputer)

**Role: Mahasiswa/Pengguna Edukasi**
- **Daftar Generasi**: Gen 1 Vakum → Gen 5 AI secara kronologis
- **Detail Teknis**: Tahun, teknologi utama, contoh komputer ikonik
- **Visualisasi**: Ikon generasi + Glide image loading optimized
- **Navigasi Aman**: Back button + Intent extras dengan null-safety

**Teknologi yang Digunakan**

**Bahasa**: Kotlin  
**UI Framework**: XML Layout + Material Components  
**Image Loading**: Glide (dengan error handling)  
**Architecture**: Activity-based + Safe Intent Extras  
**Navigation**: Explicit Intent + onBackPressedDispatcher  
**Build Tools**: Gradle Kotlin DSL + Android Studio  

**Screenshot** 

![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/landingpage.jpeg)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/mainmenu.jpeg)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/deskripsi1.jpeg)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/deskripsi2.jpeg)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/deskripsi3.jpeg)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/deskripsi4.jpeg)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/deskripsi5.jpeg)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/sc1.png)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/sc2.png)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/sc3.png)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/sc4.png)
![Loading Screen](https://raw.githubusercontent.com/Meylinda-git/2205101117_Meylindasari-W.W_UTS/main/PublishAssets/sc5.png)

## Cara Menjalankan

1. Clone repository ini.
2. Buka di Android Studio otter.
3. Sync Gradle.
4. Run di Emulator/Device Fisik (Min SDK 24).
