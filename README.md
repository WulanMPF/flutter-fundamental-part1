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

![Langkah 9](/images/p3_langkah9.png)

### Langkah 10
Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.

![Langkah 10](/images/p3_langkah10.png)

### Langkah 11
Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.

![Langkah 11](/images/p3_langkah11.png)

### Langkah 12
Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.

![Langkah 12](/images/01.png)

## PRAKTIKUM 4
### Langkah 1: Text Widget
Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart.

![Langkah 1](/images/p4_langkah1a.png)

Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.

![Langkah 1](/images/p4_langkah1b.png)

### Langkah 2: Image Widget
Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.

![Langkah 2](/images/p4_langkah2a.png)

Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.

![Langkah 2](/images/p4_langkah2b.png)

Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.

![Langkah 2](/images/p4_langkah2c.png)

## PRAKTIKUM 5
### Langkah 1: Cupertino Button dan Loading Bar
Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

![Langkah 1](/images/p5_langkah1a.png)

![Langkah 1](/images/p5_langkah1b.png)

*When Click The Button:*

![Langkah 1](/images/p5_langkah1c.png)

### Langkah 2: Floating Action Button (FAB)
Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.

Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

![Langkah 2](/images/p5_langkah2a.png)

![Langkah 2](/images/p5_langkah2b.png)

*When Click The Button:*

![Langkah 2](/images/p5_langkah2c.png)

### Langkah 3: Scaffold Widget
Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.

Ubah isi kode main.dart seperti berikut.

![Langkah 3](/images/p5_langkah3a.png)

![Langkah 3](/images/p5_langkah3b.png)

![Langkah 3](/images/p5_langkah3c.png)

*When Hover The Button:*

![Langkah 3](/images/p5_langkah3d.png)

*When Click The Button Once:*

![Langkah 3](/images/p5_langkah3e.png)

### Langkah 4: Dialog Widget
Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.

Ubah isi kode main.dart seperti berikut.

![Langkah 4](/images/p5_langkah4a.png)

*When Click The Button:*

![Langkah 4](/images/p5_langkah4b.png)

### Langkah 5: Input dan Selection Widget
Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.

Contoh penggunaan TextField widget adalah sebagai berikut:

![Langkah 5](/images/p5_langkah5a.png)

*When Fill The TextField:*

![Langkah 5](/images/p5_langkah5b.png)

### Langkah 6: Date and Time Pickers
Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.

![Langkah 6](/images/p5_langkah6a.png)

*When Click The Button:*

![Langkah 6](/images/p5_langkah6b.png)

*When Pick The Date:*

![Langkah 6](/images/p5_langkah6c.png)

## TUGAS PRAKTIKUM
### 1. Selesaikan Praktikum 1 sampai 5, lalu dokumentasikan dan push ke repository Anda berupa screenshot setiap hasil pekerjaan beserta penjelasannya di file README.md!

### 2. Selesaikan Praktikum 2 dan Anda wajib menjalankan aplikasi hello_world pada perangkat fisik (device Android/iOS) agar Anda mempunyai pengalaman untuk menghubungkan ke perangkat fisik. Capture hasil aplikasi di perangkat, lalu buatlah laporan praktikum pada file README.md.

Hasil Praktikum 5 Langkah 6 (Date and Time Pickers) pada device Android:

![Tugas 2](/images/tgs_no2a.jpg)

![Tugas 2](/images/tgs_no2b.jpg)

![Tugas 2](/images/tgs_no2c.jpg)

![Tugas 2](/images/tgs_no2d.jpg)

### 3. Pada praktikum 5 mulai dari Langkah 3 sampai 6, buatlah file widget tersendiri di folder basic_widgets, kemudian pada file main.dart cukup melakukan import widget sesuai masing-masing langkah tersebut!

### 4. Selesaikan Codelabs: Your first Flutter app, lalu buatlah laporan praktikumnya dan push ke repository GitHub Anda!

#### Make new project, and name your project something like namer_app or my_awesome_namer.

![Tugas 4](/images/tgs_no4a.png)

#### In the left pane of VS Code, make sure that Explorer is selected, and open the pubspec.yaml file. Replace the contents of this file with the following:

![Tugas 4](/images/tgs_no4b.png)

#### Next, open another configuration file in the project, analysis_options.yaml. Replace its contents with the following:

![Tugas 4](/images/tgs_no4c.png)

#### Finally, open the main.dart file under the lib/ directory. Replace the contents of this file with the following:

![Tugas 4](/images/tgs_no4d.png)

#### Launch the app. First, open lib/main.dart and make sure that you have your target device selected. At the bottom right corner of VS Code, you'll find a button that shows the current target device. Click to change it. While lib/main.dart is open, find the "play" button in the upper right-hand corner of VS Code's window, and click it. After about a minute, your app launches in debug mode. It doesn't look like much yet

![Tugas 4](/images/tgs_no4e.png)

#### First Hot Reload. At the bottom of lib/main.dart, add something to the string in the first Text object, and save the file (with Ctrl+S or Cmd+S). For example:

![Tugas 4](/images/tgs_no4f.png)

#### Adding a button. Next, add a button at the bottom of the Column, right below the second Text instance.

![Tugas 4](/images/tgs_no4g.png)

#### A Flutter crash course in 5 minutes. As much fun as it is to watch the Debug Console, you want the button to do something more meaningful. Before getting to that, though, take a closer look at the code in lib/main.dart, to understand how it works. At the very top of the file, you'll find the main() function. In its current form, it only tells Flutter to run the app defined in MyApp.

![Tugas 4](/images/tgs_no4h.png)

#### The MyApp class extends StatelessWidget. Widgets are the elements from which you build every Flutter app. As you can see, even the app itself is a widget. The code in MyApp sets up the whole app. It creates the app-wide state (more on this later), names the app, defines the visual theme, and sets the "home" widget—the starting point of your app.

![Tugas 4](/images/tgs_no4i.png)

#### Next, the MyAppState class defines the app's...well...state. This is your first foray into Flutter, so this codelab will keep it simple and focused. There are many powerful ways to manage app state in Flutter. One of the easiest to explain is ChangeNotifier, the approach taken by this app.

![Tugas 4](/images/tgs_no4j.png)

#### Your first behavior. Scroll to MyAppState and add a getNext method.

![Tugas 4](/images/tgs_no4k.png)

#### All that remains is to call the getNext method from the button's callback.

![Tugas 4](/images/tgs_no4l.png)

#### Extract a widget. For that reason, rewrite the MyHomePage widget as follows:

![Tugas 4](/images/tgs_no4m.png)

#### Now, call up the Refactor menu. Right click the piece of code you want to refactor (Text in this case) and select Refactor... from the drop-down menu

![Tugas 4](/images/tgs_no4n.png)

#### In the Refactor menu, select Extract Widget. Assign a name, such as BigCard, and click Enter.

![Tugas 4](/images/tgs_no4o.png)

#### This automatically creates a new class, BigCard, at the end of the current file. The class looks something like the following:

![Tugas 4](/images/tgs_no4p.png)

#### Add a Card. Instead, select Wrap with Padding. This creates a new parent widget around the Text widget called Padding. After saving, you'll see that the random word already has more breathing room.

![Tugas 4](/images/tgs_no4q.png)

#### Next, go one level higher. Place your cursor on the Padding widget, pull up the Refactor menu, and select Wrap with widget.... This allows you to specify the parent widget. Type "Card" and press Enter.

![Tugas 4](/images/tgs_no4r.png)

#### This wraps the Padding widget, and therefore also the Text, with a Card widget.

![Tugas 4](/images/tgs_no4s.png)

*When Click The Button:*

![Tugas 4](/images/tgs_no4t.png)

#### Theme and style. Make the following changes to BigCard's build() method.

![Tugas 4](/images/tgs_no4u.png)

#### TextTheme. The card still has a problem: the text is too small and its color is hard to read. To fix this, make the following changes to BigCard's build() method.

![Tugas 4](/images/tgs_no4v.png)

#### Improve accessibility. Use Text's semanticsLabel property to override the visual content of the text widget with a semantic content that is more appropriate for screen readers:

![Tugas 4](/images/tgs_no4w.png)

#### Center the UI. First, remember that BigCard is part of a Column. By default, columns lump their children to the top, but we can easily override this. Go to MyHomePage's build() method, and make the following change:

![Tugas 4](/images/tgs_no4x.png)

#### You can just center the column itself. Put your cursor onto Column, call up the Refactor menu (with Ctrl+. or Cmd+.), and select Wrap with Center.

![Tugas 4](/images/tgs_no4y.png)

#### With the optional changes, MyHomePage contains this code:

![Tugas 4](/images/tgs_no4z.png)

#### Add the business logic

![Tugas 4](/images/tgs_no4z1.png)

#### Add the button

![Tugas 4](/images/tgs_no4z2.png)

#### Here's one way to add the second button to MyHomePage

![Tugas 4](/images/tgs_no4z3.png)

*When Click The Button:*

![Tugas 4](/images/tgs_no4z4.png)

#### Select all of MyHomePage, delete it, and replace with the following code:

![Tugas 4](/images/tgs_no4z5.png)

#### You can change the extended: false line in NavigationRail to true. This shows the labels next to the icons. In a future step, you will learn how to do this automatically when the app has enough horizontal space.

![Tugas 4](/images/tgs_no4z6.png)

#### Stateless versus stateful widgets. Place your cursor on the first line of MyHomePage (the one that starts with class MyHomePage...), and call up the Refactor menu using Ctrl+. or Cmd+.. Then, select Convert to StatefulWidget.

![Tugas 4](/images/tgs_no4z7.png)

#### setState. The new stateful widget only needs to track one variable: selectedIndex. Make the following 3 changes to _MyHomePageState:

![Tugas 4](/images/tgs_no4z8.png)

*When Click The Favourites Bar:*

![Tugas 4](/images/tgs_no4z9.png)

#### Use selectedIndex. Place the following code at the top of _MyHomePageState's build method, just before return Scaffold:

![Tugas 4](/images/tgs_no4z10.png)

#### Here's _MyHomePageState after that single remaining change:

![Tugas 4](/images/tgs_no4z11.png)

*When Click The Favourites Bar:*

![Tugas 4](/images/tgs_no4z12.png)

#### Responsiveness. Inside _MyHomePageState's build method, put your cursor on Scaffold. Next, Call up the Refactor menu with Ctrl+. (Windows/Linux) or Cmd+. (Mac). Next, Select Wrap with Builder and press Enter. Next, Modify the name of the newly added Builder to LayoutBuilder. Last, Modify the callback parameter list from (context) to (context, constraints).

![Tugas 4](/images/tgs_no4z13.png)

#### Now your code can decide whether to show the label by querying the current constraints. Make the following single-line change to _MyHomePageState's build method:

![Tugas 4](/images/tgs_no4z14.png)

*When Changing The Screen Size:*

![Tugas 4](/images/tgs_no4z15.png)

#### Add New Page. Here's the new FavoritesPage class:

![Tugas 4](/images/tgs_no4z16.png)

*When Click The Like Button & Favourites Bar:*

![Tugas 4](/images/tgs_no4z17.png)

### 5. README.md berisi: capture hasil akhir tiap praktikum (side-by-side, bisa juga berupa file GIF agar terlihat proses perubahan ketika ada aksi dari pengguna) dengan menampilkan NIM dan Nama Anda sebagai ciri pekerjaan Anda.

### 6. Kumpulkan berupa link repository/commit GitHub Anda kepada dosen yang telah disepakati!