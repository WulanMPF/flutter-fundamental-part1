# JOBSHEET 5

Nama: Wulan Maulidya P. F

Kelas: TI-3H

No. Absen: 27

NIM: 2241720174

---

## PRAKTIKUM 1
### Langkah 1
Buka VS Code, lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project.

![Langkah 1](/images/p1_langkah1.png)

### Langkah 2
Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.

![Langkah 2](/images/p1_langkah2.png)

### Langkah 3
Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.

![Langkah 3](/images/p1_langkah3.png)

### Langkah 4
Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.

![Langkah 4](/images/p1_langkah4.png)

## PRAKTIKUM 2
### Mengaktifkan Proses Debug USB
#### Langkah 1
Di perangkat Android, ketuk Settings > About phone.

![Langkah 1](/images/p2a_langkah1.jpg)

#### Langkah 2
Ketuk Build number tujuh kali.

![Langkah 2](/images/p2a_langkah2.jpg)

#### Langkah 3
Jika diminta, masukkan sandi atau PIN perangkat. Anda tahu Anda telah berhasil saat melihat pesan You are now a developer!.

![Langkah 3](/images/p2a_langkah3.jpg)

#### Langkah 4
Kembali ke Settings, lalu ketuk System > Developer options.

![Langkah 4](/images/p2a_langkah4.jpg)

#### Langkah 5
Jika Anda tidak melihat Developer options, ketuk Advanced options.

#### Langkah 6
Ketuk Developer options, lalu ketuk tombol USB debugging untuk mengaktifkannya.

![Langkah 6](/images/p2a_langkah6.jpg)

### Menginstall Driver USB Google
#### Langkah 1
Di Android Studio, klik Tools > SDK Manager. Dialog Preferences > Appearance & Behavior > System Settings > Android SDK akan terbuka.

![Langkah 1](/images/p2b_langkah1.png)

#### Langkah 2
Klik tab SDK Tools.

![Langkah 2](/images/p2b_langkah2.png)

#### Langkah 3
Pilih Google USB Driver, lalu klik OK.

![Langkah 3](/images/p2b_langkah3.png)

### Menjalankan Aplikasi di Perangkat Android Menggunakan Kabel
#### Langkah 1
Sambungkan perangkat Android ke komputer menggunakan kabel USB. Dialog yang meminta Anda mengizinkan proses debug USB akan muncul di perangkat.

#### Langkah 2
Pilih kotak centang Always allow from this computer, lalu ketuk OK.

#### Langkah 3
Di Android Studio di komputer, pastikan perangkat Anda dipilih di menu drop-down. Klik ikon Run Android Studio.

#### Langkah 4
Pilih perangkat lalu klik OK. Android Studio akan menginstal aplikasi di perangkat, lalu menjalankannya.

#### Langkah 5
Jika perangkat menjalankan platform Android yang tidak diinstal di Android Studio dan melihat pesan berisi pertanyaan apakah Anda ingin menginstal platform yang diperlukan, klik Install > Continue > Finish. Android Studio akan menginstal aplikasi di perangkat, lalu menjalankannya.

### Menjalankan Aplikasi di Perangkat Android Menggunakan Wi-Fi
#### Langkah 1 (Memulai)
Pastikan komputer dan perangkat Anda terhubung ke jaringan nirkabel yang sama.

#### Langkah 2 (Memulai)
Pastikan perangkat Anda menjalankan Android 11 atau yang lebih baru. Untuk informasi selengkapnya, lihat Memeriksa & mengupdate versi Android.

#### Langkah 3 (Memulai)
Pastikan komputer Anda telah memiliki Android Studio versi terbaru. Untuk mendownloadnya, lihat Android Studio.

#### Langkah 4 (Memulai)
Pastikan komputer Anda memiliki SDK Platform Tools versi terbaru.

#### Langkah 1 (Menyambungkan Perangkat)
Di Android Studio, pilih Pair Devices Using Wi-Fi dari menu drop-down konfigurasi run. 

![Langkah 1](/images/p2d_langkah1.png)

Dialog Pair devices over Wi-Fi akan terbuka.

![Langkah 1](/images/p2d_langkah1b.png)

#### Langkah 2 (Menyambungkan Perangkat)
Buka Developer options, scroll ke bawah ke bagian Debugging, lalu aktifkan Wireless debugging.

![Langkah 2](/images/p2d_langkah2.jpg)

#### Langkah 3 (Menyambungkan Perangkat)
Pada pop-up Izinkan proses debug nirkabel di jaringan ini?, pilih Allow.

![Langkah 3](/images/p2d_langkah3.jpg)

#### Langkah 4 (Menyambungkan Perangkat)
Jika Anda ingin menyambungkan perangkat dengan kode QR, pilih Pair device with QR code, lalu pindai kode QR di komputer Anda. Atau, jika Anda ingin menyambungkan perangkat dengan kode penghubung, pilih Pair device with pairing code, lalu masukkan 6 digit kode.

#### Langkah 5 (Menyambungkan Perangkat)
Klik jalankan dan Anda dapat men-deploy aplikasi ke perangkat.

![Langkah 5](/images/p2d_langkah5.png)

## PRAKTIKUM 3
### Langkah 1
Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"

![Langkah 1](/images/p3_langkah1.png)

### Langkah 2
Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut.

![Langkah 2](/images/p3_langkah2.png)

### Langkah 3
Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.

![Langkah 3](/images/p3_langkah3.png)

### Langkah 4
Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.

![Langkah 4](/images/p3_langkah4.png)

### Langkah 5
Beri pesan commit "tambah gitignore" lalu klik Commit (✔)

![Langkah 5](/images/p3_langkah5.png)

### Langkah 6
Lakukan push dengan klik bagian menu titik tiga > Push

![Langkah 6](/images/p3_langkah6.png)

### Langkah 7
Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"

![Langkah 7](/images/p3_langkah7.png)

### Langkah 8
Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote

![Langkah 8](/images/p3_langkah8.png)

Setelah berhasil, tulis remote name dengan "origin"

![Langkah 8](/images/p3_langkah8b.png)

### Langkah 9
Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.

### Langkah 10
Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.

### Langkah 11
Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.

### Langkah 12
Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.

## PRAKTIKUM 4
### Langkah 1: Text Widget
Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart.

Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.

### Langkah 2: Image Widget
Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.

Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.

Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.

## PRAKTIKUM 5
### Langkah 1: Cupertino Button dan Loading Bar
Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

### Langkah 2: Floating Action Button (FAB)
Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.

Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

### Langkah 3: Scaffold Widget
Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.

Ubah isi kode main.dart seperti berikut.

### Langkah 4: Dialog Widget
Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.

Ubah isi kode main.dart seperti berikut.

### Langkah 5: Input dan Selection Widget
Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.

Contoh penggunaan TextField widget adalah sebagai berikut:

### Langkah 6: Date and Time Pickers
Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.

## TUGAS PRAKTIKUM
### 1. Selesaikan Praktikum 1 sampai 5, lalu dokumentasikan dan push ke repository Anda berupa screenshot setiap hasil pekerjaan beserta penjelasannya di file README.md!

### 2. Selesaikan Praktikum 2 dan Anda wajib menjalankan aplikasi hello_world pada perangkat fisik (device Android/iOS) agar Anda mempunyai pengalaman untuk menghubungkan ke perangkat fisik. Capture hasil aplikasi di perangkat, lalu buatlah laporan praktikum pada file README.md.

### 3. Pada praktikum 5 mulai dari Langkah 3 sampai 6, buatlah file widget tersendiri di folder basic_widgets, kemudian pada file main.dart cukup melakukan import widget sesuai masing-masing langkah tersebut!

### 4. Selesaikan Codelabs: Your first Flutter app, lalu buatlah laporan praktikumnya dan push ke repository GitHub Anda!

### 5. README.md berisi: capture hasil akhir tiap praktikum (side-by-side, bisa juga berupa file GIF agar terlihat proses perubahan ketika ada aksi dari pengguna) dengan menampilkan NIM dan Nama Anda sebagai ciri pekerjaan Anda.

### 6. Kumpulkan berupa link repository/commit GitHub Anda kepada dosen yang telah disepakati!