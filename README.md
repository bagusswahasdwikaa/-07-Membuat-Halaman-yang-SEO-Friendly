# **Laporan Praktikum**

|  | Pemrograman Berbasis Framework 2025 |
|--|--|
| NIM |  2241720223|
| Nama |  Sukma Bagus Wahasdwika |
| Kelas | TI - 3D | 

## **Langkah-langkah Praktikum**
### Praktikum 1 : Memahami Pentingnya SEO
SEO (Search Engine Optimization) adalah praktik mengoptimalkan website agar mudah ditemukan oleh mesin pencari seperti Google. Dengan SEO yang baik, website Anda akan lebih mudah muncul di hasil pencarian, sehingga meningkatkan traffic pengunjung. Beberapa elemen penting dalam SEO: 
 * Title Tag: Judul halaman yang muncul di hasil pencarian.
 * Meta Description: Deskripsi singkat tentang halaman.
 * Heading Tags (H1, H2, dll.): Struktur konten yang membantu mesin pencari memahami isi halaman.
 * URL Structure: URL yang deskriptif dan mudah dibaca.
 * Open Graph Tags: Metadata untuk media sosial seperti Facebook dan Twitter.
 *  Favicon: Ikon kecil yang muncul di tab browser. 

### Praktikum 2 : Menambahkan Favicon
1. Siapkan file favicon (format .ico) dan letakkan di folder public/.

   ![alt text](<img/favicon.ico.png>)

2. Hapus faveicon.ico yang ada di folder **src/app**

   ![alt text](<img/hapusFavicon.png>)

3. Update file src/components/layout.tsx untuk menambahkan favicon:

   ![alt text](<img/components.png>)

4. Simpan dan jalankan proyek. Favicon akan muncul di tab browser.

   ![alt text](<img/camelicon.png>)
   
### Praktikum 3 : Menambahkan Metadata untuk SEO 
1. Buat file src/utils/metadata.ts untuk menyimpan metadata default:

   ![alt text](<img/metadata.png>)

2. Update file src/components/layout.tsx untuk menggunakan metadata default jika tidak ada metadata yang di-pass:

   ![alt text](<img/updateComp.png>)

3. Update Setiap Halaman untuk dapat mem-pass definisi metadata Contoh Halaman “Tentang Saya”

   ![alt text](<img/metadatasaya.png>)

4. Lanjutkan untuk halaman Proyek dan Esai 

   * Halaman Proyek
     
      ![alt text](<img/metadataproject.png>)

   * Halaman Esai
     
      ![alt text](<img/metadataesai.png>)

### Praktikum 4 : Open Graph Tags untuk Media Sosial 
1. Pastikan Anda telah menambahkan Open Graph Tags di layout.tsx seperti yang telah dijelaskan sebelumnya.
2. Update metadata di setiap halaman untuk menyertakan Open Graph Tags.
   
### Praktikum 5 : Menguji SEO
Setelah menambahkan metadata, favicon, dan Open Graph Tags, Anda dapat menguji SEO dengan Membuka halaman di browser dan memeriksa elemen HTML menggunakan Developer Tools (Ctrl + Shift + I atau F12). 

### Tugas 

Lakukan pengujian SEO dengan 
1. Gunakan tools seperti Google Search Console untuk memeriksa performa SEO dari suatu website. 

### Kesimpulan

Dalam praktikum ini, Anda telah mempelajari cara membuat halaman Next.js yang SEO-friendly dengan menambahkan metadata, favicon, dan Open Graph Tags. Dengan teknik ini, website Anda akan lebih mudah ditemukan oleh mesin pencari dan menarik lebih banyak pengunjung. 
