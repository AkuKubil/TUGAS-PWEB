# Laporan Tugas PWEB  
## Membuat Website Profil Diri  

### Identitas  
- **Nama** : Brilian Kurniawan Prasisto  
- **NRP**  : 5025241213  
- **Mata Kuliah** : Pemrograman Web  

---

## Tujuan  
Tugas ini bertujuan untuk membuat halaman web sederhana menggunakan **HTML** yang menampilkan informasi profil diri. Halaman ini mencakup deskripsi diri, hobi, riwayat pendidikan, form kontak, serta tautan sosial media.  

---

## Hasil Implementasi  

### 1. Tampilan Halaman  
Berikut hasil tampilan website yang sudah dibuat:  

![Tampilan Website](assets/screenshot-profil.png)  

---

### 2. Struktur Halaman  
Website terdiri dari beberapa bagian utama:  
1. **Judul & Identitas**  
   - Menampilkan judul "Welcome To" dan identitas berupa nama serta NRP.  

2. **Foto Profil**  
   - Menggunakan tag `<img>` untuk menampilkan foto dengan ukuran 400px.  

3. **Deskripsi Diri**  
   - Paragraf yang menjelaskan pengalaman kepemimpinan, kemampuan komunikasi, serta motivasi untuk berkembang.  

4. **Hobi**  
   - Ditampilkan dalam bentuk **list** (`<ul>` dan `<li>`).  

5. **Riwayat Pendidikan**  
   - Ditampilkan dalam bentuk **tabel** (`<table>` dengan border).  

6. **Form Kontak**  
   - Form sederhana dengan input nama, email, dan pesan.  

7. **Sosial Media**  
   - Link ke Instagram dan LinkedIn menggunakan tag `<a>` dengan `target="_blank"`.  

---

### 3. Potongan Kode Penting  

**Contoh Tabel Riwayat Pendidikan:**
```html
<table border="1">
  <tr>
    <th>Jenjang Pendidikan</th>
    <th>Keterangan</th>
    <th>Tahun</th>
  </tr>
  <tr>
    <td>Sekolah Dasar</td>
    <td>SDIT Al-Mubarak</td>
    <td>2012 s.d 2018</td>
  </tr>
  ...
</table>
