# Analisis Kebutuhan Transportasi bagi Perempuan: Kasus Layanan Bus Pink TransJakarta

## Gambaran Umum
Proyek ini merupakan bagian dari proyek capstone untuk modul Pembelajaran Mesin, yang berfokus pada analisis aksesibilitas TransJakarta dan efektivitas layanan Bus Pink. Tujuan utamanya adalah meningkatkan layanan transportasi umum bagi perempuan di Jakarta, dengan mempertimbangkan aspek aksesibilitas, keamanan, dan optimalisasi layanan.

## Latar Belakang Proyek
Berdasarkan data Badan Pusat Statistik Indonesia:
- Populasi Jakarta diperkirakan akan mencapai puncaknya pada 11,28 juta jiwa pada tahun 2040.
- Per Januari 2024, pengguna TransJakarta meningkat sebesar 23,76% dibandingkan Januari 2023, menjadikannya pilihan transportasi utama.
- Penumpang perempuan mencakup 53,2% dari total pengguna TransJakarta, dan 40 armada Bus Pink beroperasi di tujuh koridor untuk melayani kebutuhan khusus perempuan.

### Tantangan yang Dibahas
1. Memahami karakteristik penumpang dan pola penggunaan layanan TransJakarta.
2. Membandingkan proporsi penumpang perempuan pada Bus Pink dan layanan umum TransJakarta di rute tertentu.
3. Mengevaluasi kesesuaian rute Bus Pink dengan kebutuhan aksesibilitas penumpang perempuan.

## Temuan Data
### Karakteristik Penumpang dan Pola Penggunaan
- **Berdasarkan Jenis Kelamin**: Penumpang perempuan mendominasi dengan 53,2%, sedangkan laki-laki sebesar 46,7%.
- **Berdasarkan Usia**: Mayoritas penumpang adalah dewasa (79,3%), diikuti remaja (16,5%), dengan representasi anak-anak dan lansia masing-masing 2%.
- **Berdasarkan Moda Transportasi**:
  - TransJakarta: 54%
  - Jaklingko: 37%
  - RoyalTrans: 5%
  - TransJabodetabek: 4%
  - Bus Wisata: 1%

### Pola Penggunaan Berdasarkan Waktu dan Rute
- **Jam Sibuk**:
  - Pagi: 5.00 - 9.00 (puncak pada 6.00)
  - Sore: 16.00 - 21.00 (puncak pada 17.00)
- **Koridor Tersibuk**: Cibubur-Balai Kota (22,44%) karena lokasinya di kawasan bisnis.

### Data Layanan Bus Pink
- **Koridor Teratas untuk Penumpang Perempuan**: Ciledug-Tendean (45,2%)
- **Penggunaan Terendah**: Pinang Ranti-Pluit (1,4%)
- **Ketidaksesuaian Layanan**: Rute dengan jumlah penumpang perempuan tertinggi, seperti Pasar Minggu-Tanah Abang (21,3%), tidak dilayani oleh Bus Pink.

## Kesimpulan
Proyek ini memberikan beberapa temuan utama terkait aksesibilitas TransJakarta dan layanan Bus Pink:
1. **Dominasi Pengguna Perempuan**:
   - Perempuan mencakup 53,2% dari total penumpang TransJakarta, menunjukkan kebutuhan layanan yang lebih terfokus pada kenyamanan dan keamanan perempuan.
2. **Ketidaksesuaian Rute Bus Pink**:
   - Terdapat ketidaksesuaian antara rute layanan Bus Pink dan rute dengan jumlah penumpang perempuan tertinggi, seperti rute Pasar Minggu-Tanah Abang yang tidak dilayani oleh Bus Pink.
3. **Kemacetan pada Jam Sibuk**:
   - Beberapa koridor mengalami lonjakan penumpang pada jam sibuk pagi dan sore, terutama di kawasan bisnis.

## Rekomendasi
1. **Evaluasi Ulang Rute Bus Pink**:
   - Masukkan rute dengan permintaan tinggi seperti Pasar Minggu-Tanah Abang ke dalam jaringan Bus Pink untuk meningkatkan aksesibilitas.
2. **Tingkatkan Penelitian dan Mekanisme Umpan Balik**:
   - Lakukan studi rutin untuk memahami pola mobilitas perempuan dan menyesuaikan layanan berdasarkan data terkini.
3. **Tingkatkan Fasilitas dan Kesadaran**:
   - Sediakan fasilitas yang lebih baik di halte-halte strategis, termasuk langkah-langkah keamanan tambahan.
   - Tingkatkan kesadaran masyarakat tentang manfaat dan ketersediaan layanan Bus Pink.
4. **Perluas Layanan Bus Pink**:
   - Tambahkan armada bus ke rute-rute dengan permintaan tinggi dan pertimbangkan pembukaan rute baru di area yang kurang terlayani.
5. **Optimalkan Jam Operasional**:
   - Sesuaikan jadwal layanan dengan jam sibuk untuk memaksimalkan cakupan dan meminimalkan kemacetan.

Dengan mengimplementasikan rekomendasi ini, TransJakarta dapat meningkatkan kualitas layanan secara signifikan, memastikan aksesibilitas yang lebih baik, dan memenuhi kebutuhan spesifik penumpang perempuan.

## Sumber Data
- Data demografis penumpang dan pola penggunaan layanan dari TransJakarta (April 2023).
- Data statistik dari Badan Pusat Statistik Indonesia.

## Tools dan Teknologi
- Python (pandas, numpy, matplotlib, seaborn, scipy.stats, folium)
- Jupyter Notebook

## Implementasi Teknis
Proyek ini memanfaatkan analisis deskriptif, visualisasi data, dan pembelajaran mesin untuk:
- Memahami demografi penumpang dan tren penggunaan.
- Mengidentifikasi ketidaksesuaian antara penempatan layanan dan permintaan.
- Merekomendasikan perbaikan berbasis wawasan data.

Proyek ini bertujuan untuk memastikan layanan TransJakarta lebih inklusif, nyaman, dan aman bagi semua penumpang, khususnya perempuan.
