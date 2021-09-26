Widget Android Studio
Widget merupakan komponen utama dalam membuat UI di Android

UI Hirarki
Antarmuka pengguna (UI) untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget.

Set/ Get Value of Widget
Bergantung pada widget
Edittext : text etc
ImageView : ImageResource stc
RadioButton: Text, Checked
CheckBox : Text, Checked

Komponen navigasi
Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna.
Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default.

Destinasi
Setiap aplikasi yang dibuat harus memiliki awal tujuan. Ini merupakan layer pertama yang user dilihat ketika mereka meluncurkan aplikasi

Grafik navigasi
Tujuan adalah area konten yang berbeda di aplikasi anda
Tindakan adalah koneksi logis antara tujuan anda yang mewakili jalur yang dapat diambil pengguna.

Editor navigasi
Panel tujuan: Mencantumkan host navigasi anda dan semua tujuan yang ada di Editor Grafik.
Editor Grafik: Berisi representasi visual dari grafik navigasi anda.
Atribut: Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi

Tambahkan navhost kedalam aktivitas
Salah satu bagian inti dari komponen Navigasi adalah host navigasi.
Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi anda. Host navigasi harus berasal dari NavHost
