1941720101
Hafiz Kalam Abdillah 
TI3A / 09 

Rangkuman 

Widget merupakan komponen utama dalam membuat UI di Android
Widget merupakan turunan dari View class

* UI Hirarki
UI Hirarki adalah antarmuka pengguna (UI) untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget. Perlu mendefinisikan ID dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin.

* Set/ Get Value of Widget
Bergantung pada widget itu
Edittext : text etc
ImageView : ImageResource stc
RadioButton: Text, Checked
CheckBox : Text, Checked

* Komponen navigasi
Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman seorang user. Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip secara default, memastikan bahwa pengguna/user dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

* Destinasi 
Setiap aplikasi yang dibuat harus memiliki awal tujuan. Ini merupakan layer pertama yang user dilihat ketika mereka meluncurkan  aplikasi. Tujuan ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.

* Grafik navigasi
Tujuan adalah area konten yang berbeda di sebuah aplikasi. Tindakan adalah koneksi logic antara tujuan anda yang mewakili jalur yang dapat diambil pengguna.

* Editor navigasi
Panel tujuan: Mencantumkan host navigasi anda dan semua tujuan yang ada di Editor Grafik.
Editor Grafik: Berisi representasi visual dari grafik navigasi anda. Dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
Atribut: Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi

* Tambahkan navhost kedalam aktivitas
Salah satu bagian inti dari komponen Navigasi adalah host navigasi. Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi anda. Host navigasi harus berasal dari NavHost
