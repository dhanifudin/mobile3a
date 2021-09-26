Rangkuman Pertemuan ke-4

materi pada hari ini membahas mengenai Recyler View yang terdiri dari beberapa Layout yaitu Grid Layout, Liner Layout dan Cardview. pada intinya belajar bagaimana membuat sebuah aplikasi perhitungan hutang teman. kemudian praktik bagaimana cara membuat list view yang sesuai dengan keinginan dan jarak pada antar view tidak terlalu jauh.Pada pertemuan ini juga dicontohkan bagaimana membuat list view yang horizontal. Pengelola layout menangani penyusunan (layout) komponen antarmuka pengguna dalam suatu tampilan. Semua grup tampilan memiliki pengelola layout. Untuk LinearLayout, sistem Android menangani layout untuk Anda. RecyclerView memerlukan pengelola layout eksplisit untuk mengelola susunan list item yang terdapat di dalamnya. Layout ini bisa vertikal, horizontal, atau berupa grid.
 Saat menentukan adaptor, perlu mengganti tiga metode :
onCreateViewHolder():
onBindViewHolder()
getItemCount() 
masing masing fungsi tersebut memiliki fungsinya masing masing dan berbedabeda, onCreateViewHoder() dipanggil ketika diperlukan viewholder tetapi tidak mengisi konten  viewholder yang belum terikat dengan suatu data. onBindViewHolder() dipanggil ketika membutuhkan distribusi viewholder.getItemCount() dipanggil ketika mendapat ukuran set data.
apabila adapter sudah dibuat juga, maka langkah selanjutnya adalah mengisi data pada main activity untuk pengisian data dan mengisi data yang berulang, nantinya data akan di tampilkan sesuai dengan layout yang sudah di set dalam fungsi.
