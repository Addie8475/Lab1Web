# Lab1Web
**Hasil pembuatan dan perubahan web yang telah saya buat**

>**Judul**
: Ini adalah nama judul tab menggunakan tag (head). Elemen ini mewakili kumpulan metadata untuk Dokumen.
<img width="548" height="86" alt="Judul" src="https://github.com/user-attachments/assets/9d69ea87-55dd-45db-b00d-00539d30bf88" />

>**Header Tag**
: Ini adalah bagian judul dari web menggunakan tag h1 dan h2. Elemen-elemen ini mewakili judul bagian.
  <img width="381" height="149" alt="Header" src="https://github.com/user-attachments/assets/847bdc7a-e3fa-48de-8d69-7fbf1a865c91" />

>**Paragraf Kalimat (left, center, right, justify)**

- Left (semua kata-kata diratakan ke kiri)
<img width="851" height="81" alt="Paragraf" src="https://github.com/user-attachments/assets/282bcbce-575e-4769-b6d4-ed74cf64af1b" />


- Center (semua kata-kata diratakan ke tengah)
<img width="849" height="83" alt="Paragraf (Center)" src="https://github.com/user-attachments/assets/76f2d657-68f3-4d3f-9acd-e1b3734a279d" />


- Right (semua kata-kata diratakan ke kanan)
<img width="855" height="84" alt="Paragraf (Right)" src="https://github.com/user-attachments/assets/0ef5e134-d7aa-4e4d-b3c3-24bad68d6195" />

- Justify (semua kata-kata diratakan ke sisi kiri dan kanan margin)
<img width="850" height="79" alt="Paragraf (Justify)" src="https://github.com/user-attachments/assets/1fa54bfd-e6c8-424a-9f05-d34cb7e186bf" />

>**Foto**
: beberapa foto yang telah ditambahkan disini dengan lebar 200 piksel
<img width="349" height="489" alt="Foto" src="https://github.com/user-attachments/assets/ce68b1f8-da1c-4a01-adc7-fea36f71445b" />

>**Hyperlink web**
: Disini menggunakan tag "nav". Elemen ini mewakili bagian halaman yang tertaut ke halaman lain atau ke bagian dalam halaman: bagian dengan tautan navigasi.
<img width="380" height="183" alt="Hyperlink web" src="https://github.com/user-attachments/assets/7522f7e6-b09b-4b35-8b42-e10b68b91226" />

>**Halaman baru**
: Dan ini adalah halaman baru yang telah dibuat dari halaman utama
<img width="262" height="479" alt="Halaman Baru" src="https://github.com/user-attachments/assets/ba9f2dae-8f9f-4b99-9a17-7ca47accfc14" />

# Pertanyaan
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag p dengan tag br, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag img, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

**Jawab**

**1. Setelah saya ubah dan diamati lagi, tidak ada kesalahan satupun yang terjadi saat menjalankan web**
**2. Tag p (Paragraph)**
- Fungsinya untuk membuat paragraf baru.
- Secara default, browser memberikan jarak atas dan bawah pada setiap paragraf.
- Tag p adalah container/block element, artinya membungkus teks dalam sebuah blok.

  Tag br (Line Break)
- Fungsinya untuk membuat baris baru (pindah ke bawah), tanpa memulai paragraf baru.
- Tag br tidak memiliki penutup (</br> tidak dipakai di HTML5).
- Tag br adalah inline element, jadi hanya memecah baris di dalam teks.

**3. Atribut alt (Alternative Text)**
- Digunakan untuk memberikan teks alternatif jika gambar tidak bisa ditampilkan (karena error, koneksi lambat, atau aksesibilitas).
- Sangat penting untuk SEO dan aksesibilitas (screen reader akan membaca teks alt untuk pengguna tunanetra).
- Wajib digunakan pada tag img agar konten tetap bisa dimengerti meskipun gambar gagal dimuat.

  Atribut title
- Digunakan untuk memberikan informasi tambahan (tooltip) saat kursor diarahkan ke gambar.
- Tidak muncul jika gambar gagal dimuat.
- Bersifat opsional, hanya untuk memberi keterangan ekstra.

**4. Tentang Atribut width dan height pada img**

Fungsinya: mengatur ukuran tampilan gambar di halaman web (dalam pixel atau persentase).
Agar gambar tetap proporsional (tidak gepeng/terdistorsi), sebaiknya JANGAN mengisi kedua atribut (width dan height) sekaligus secara manual.

Kalau hanya mengisi salah satu (misalnya width saja)
Browser akan otomatis menyesuaikan ukuran sisi lainnya (height) sesuai rasio asli gambar.
Hasil: gambar tetap proporsional.

Kalau mengisi width dan height sekaligus dengan nilai yang tidak sesuai rasio asli
Gambar akan terlihat melebar atau memanjang (distorsi).
Praktik modern (CSS lebih baik)

Umumnya, ukuran gambar diatur dengan CSS agar lebih fleksibel (misalnya responsif di berbagai perangkat).

**5. Nilai atribut target dan efeknya**

_blank :

Membuka link di tab/jendela baru.
Paling sering dipakai kalau tidak ingin menutup halaman utama.

_self (default) :

Membuka link di halaman/tab yang sama.
Kalau target tidak ditulis, maka otomatis dianggap _self.

_top :

Membuka link di jendela penuh (top-level window), menghapus semua frame.
Berguna kalau halaman sedang berada dalam frameset/iframe, lalu ingin keluar ke halaman penuh.

_parent :

Membuka link di parent frame (satu tingkat di atas frame sekarang).
Kalau tidak ada parent frame, sama saja dengan _self.
