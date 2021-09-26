NIM     : 1941720186
NAMA    : Hisyam Haryo Mahdyan
KELAS   : TI-2A

Pada pertemuan ke empat membahas tentang Recycle View. Recycle view sendiri pada dasarnya adalah list view yang dikembangkan sehingga lebih responsif dan fleksibel. Ada beberapa cara menggunakan list view yaitu

1. Membuat rancangan tampilan pada layout nya
2. Membuat Logic pada menggunakan bahasa java

Lalu pada class java yang dibuat dengan meng-extends class tersebut dengan adapter. Ada 3 fungsi penting yang wajib ada pada kelas tersebut

1. onCreateViewHolder
Untuk memanggil file xml agar dapat bisa diakses menggunakan bahasa java, menggunakan Layout Inflater, lalu men set ukuran pada list
2. onBindViewHolder
Mengambil elemen dari dataset yang sudah dibuat pada posisi tertentu, lalu mengisi view yang sudah dengan dataset yang sudah dibuat
3. getItemCount
Menghitung ukuran dataset/jumlah data yang ditampilkan pada recycle view

Setelah melakukan itu mungkin akan terjadi kesalahan pada view nya. Yaitu menampilkan satu data untuk satu halaman. Jalan keluarnya yaitu dengan mengatur height nya menjadi wrap content agar tingginya mengikuti dari elemennya