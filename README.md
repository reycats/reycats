<div align="center">

<img src="assets/yomiru-labs-logo.svg" alt="Yomiru Labs" width="560" />

<br />

# Yomiru Labs

**Building Yomiru** A Better Way to Read Comics.**

[![Developer](https://img.shields.io/badge/Developer-Yomiru%20Labs-06b6d4?style=flat-square&logo=android&logoColor=white)](https://github.com/reycats)
[![Application](https://img.shields.io/badge/Application-Yomiru%20v1.0.0-0284c7?style=flat-square&logo=book&logoColor=white)](https://github.com/reycats)
[![Platform](https://img.shields.io/badge/Platform-Android-38bdf8?style=flat-square&logo=android&logoColor=060913)](https://github.com/reycats)
[![Profile](https://img.shields.io/badge/GitHub-@reycats-0f172a?style=flat-square&logo=github&logoColor=white)](https://github.com/reycats)
[![Contact](https://img.shields.io/badge/Contact-Email%20Developer-090d16?style=flat-square&logo=gmail&logoColor=white)](mailto:reynotdeveloper@gmail.com)

---

</div>

## Pengantar

Halo, selamat datang di profil GitHub saya (**@reycats**). Saya adalah seorang pengembang independen di balik merek **Yomiru Labs**, yang mendedikasikan waktu dan fokus teknis untuk merancang, mengembangkan, dan terus menyempurnakan **Yomiru** aplikasi pembaca komik dan manga modern untuk platform Android.

Prinsip rekayasa perangkat lunak yang saya terapkan adalah kesederhanaan, performa responsif, dan privasi penuh bagi pengguna. Yomiru dibangun dengan pendekatan *local-first*, memastikan seluruh koleksi bacaan, penanda buku, serta catatan riwayat tersimpan langsung di dalam penyimpanan privat perangkat pengguna tanpa keharusan mendaftarkan akun.

---

## Proyek Utama: Yomiru

<table>
  <tr>
    <td>
      <h3>Yomiru Android Comic &amp; Manga Reader</h3>
      <p>
        Aplikasi pembaca komik dan manga berbasis Android yang dirancang khusus untuk menghadirkan pengalaman membaca yang nyaman, cepat, dan bebas distraksi.
      </p>
      <ul>
        <li><strong>Nama Aplikasi:</strong> Yomiru</li>
        <li><strong>Pengembang:</strong> Yomiru Labs (<code>@reycats</code>)</li>
        <li><strong>Platform:</strong> Android</li>
        <li><strong>Package Name:</strong> <code>com.yomirulabs.yomiru</code></li>
        <li><strong>Versi Aktif:</strong> <code>1.0.0</code></li>
        <li><strong>Pendekatan Data:</strong> Penyimpanan lokal privat (<em>local-first</em>)</li>
      </ul>
    </td>
  </tr>
</table>

### Fitur &amp; Fungsionalitas yang Tersedia

- **Membaca Komik &amp; Manga:** Antarmuka pembaca yang dirancang untuk kenyamanan visual dengan dukungan berbagai orientasi arah baca (kanan-ke-kiri, kiri-ke-kanan, dan *vertical continuous scroll*).
- **Pustaka &amp; Koleksi Favorit:** Mengelola daftar judul komik favorit dan penanda bacaan (*bookmarks*) langsung di perangkat tanpa membutuhkan akun terpusat.
- **Riwayat Membaca:** Pencatatan kronologis bab yang telah dibuka beserta waktu akses terakhir untuk memudahkan melanjutkan bacaan.
- **Pelacakan Progres Membaca:** Penyimpanan otomatis posisi bab aktif dan indeks nomor halaman terakhir yang sedang dibaca.
- **Ekspor &amp; Impor Data Lokal:** Fitur pencadangan dan pemulihan data mandiri memanfaatkan *Storage Access Framework* (SAF) Android, memberikan keleluasaan penuh bagi pengguna untuk memindahkan arsip data mereka.
- **Privasi Terjaga:** Seluruh preferensi konfigurasi dan pustaka tersimpan secara lokal pada ruang penyimpanan terisolasi (*sandbox*) aplikasi di perangkat.

---

## Fokus Pengembangan

Dalam membangun dan memelihara Yomiru, prioritas rekayasa perangkat lunak saya terpusat pada aspek-aspek berikut:

- **Pengembangan Native Android:** Mengutamakan arsitektur Android modern yang efisien dalam manajemen siklus hidup aplikasi serta pengelolaan konsumsi memori saat memproses gambar halaman beresolusi tinggi.
- **Kenyamanan &amp; Usabilitas Pengalaman Membaca:** Mengoptimalkan alur *rendering* halaman dan transisi antarmuka agar tetap responsif pada berbagai ukuran layar ponsel Android.
- **Persistensi Progres yang Andal:** Memastikan status progres bacaan tersimpan secara konsisten dan akurat ke dalam basis data lokal.
- **Arsitektur Kode yang Terawat:** Menerapkan struktur kode yang bersih, modular, dan terpisah antar-lapisan (*separation of concerns*) agar mudah diuji serta dikembangkan secara berkelanjutan.
- **Otomasi Pengujian &amp; Build:** Menerapkan alur kerja otomasi melalui GitHub Actions untuk verifikasi kualitas kode, *linting*, dan pembuatan berkas rilis secara terstandar.

---

## Tumpukan Teknologi

Teknologi dan pustaka yang digunakan dalam pengembangan Yomiru:

| Kategori | Teknologi &amp; Pustaka |
|---|---|
| **Bahasa Pemrograman** | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |
| **Antarmuka Pengguna (UI)** | ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Android SDK](https://img.shields.io/badge/Android%20SDK-3DDC84?style=flat-square&logo=android&logoColor=white) |
| **Penyimpanan Lokal** | ![Room DB](https://img.shields.io/badge/Room%20DB-0284c7?style=flat-square&logo=sqlite&logoColor=white) |
| **Pemuatan Gambar** | ![Coil](https://img.shields.io/badge/Coil-Image%20Loading-06b6d4?style=flat-square) |
| **Jaringan &amp; Serialisasi** | ![Retrofit](https://img.shields.io/badge/Retrofit-Networking-0284c7?style=flat-square) ![Moshi](https://img.shields.io/badge/Moshi-JSON-38bdf8?style=flat-square&logoColor=060913) |
| **Build &amp; Automasi CI/CD** | ![Gradle](https://img.shields.io/badge/Gradle-Build%20Tool-02303A?style=flat-square&logo=gradle&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

---

## Statistik GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=reycats&show_icons=true&theme=tokyonight&bg_color=0c1424&title_color=38bdf8&text_color=cbd5e1&icon_color=06b6d4&border_color=1e293b&hide_border=false" alt="Statistik GitHub @reycats" height="150" />
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=reycats&layout=compact&theme=tokyonight&bg_color=0c1424&title_color=38bdf8&text_color=cbd5e1&border_color=1e293b&hide_border=false" alt="Bahasa Pemrograman @reycats" height="150" />

</div>

---

## Kontak &amp; Informasi Pengembang

Untuk pertanyaan teknis, saran, atau diskusi seputar pengembangan aplikasi, silakan menghubungi:

- **Pengembang:** Yomiru Labs
- **Profil GitHub:** [https://github.com/reycats](https://github.com/reycats)
- **Email:** [reynotdeveloper@gmail.com](mailto:reynotdeveloper@gmail.com)

---

<div align="center">
  <sub>&copy; 2026 Yomiru Labs &bull; Dikembangkan secara mandiri untuk ekosistem Android.</sub>
</div>
