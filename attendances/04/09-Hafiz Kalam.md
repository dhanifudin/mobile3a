Absensi 

Rangkuman Petermuan ke-4

Kelas RecyclerView adalah versi ListView yang lebih canggih dan fleksibel. Widget ini adalah kontainer untuk menampilkan rangkaian data besar yang bisa discroll secara efisien dengan mempertahankan tampilan dalam jumlah terbatas.

Widget RecyclerView digunakan saat perlu menampilkan banyak data yang bisa discroll, atau kumpulan data dengan elemen yang berubah pada waktu proses berdasarkan aksi pengguna atau kejadian jaringan.

RecyclerView terdiri dari beberapa komponen, yaitu :

- Data
    Tidak penting dari mana asal data. Data dapat dibuat secara lokal.
- RecyclerView 
    Berisi item daftar. Instance recyclerview didefinisikan dalam activity layout kontainer tampilan.
- Layout untuk satu item data 
    Semua item daftar tampak sama, sehingga bisa menggunakan layout yang sama untuk semuanya. Layout item harus dibuat secara terpisah dari activity layout, sehingga satu per satu tampilan item bisa dibuat dan diisi data.
- Pengelola layout 
    Pengelola layout adalah instance dari Recyclerview.LayoutManager untuk menyusun layout item dalam RecyclerView.
    Pengelola layout menangani penyusunan (layout) komponen antarmuka pengguna dalam suatu tampilan. Semua grup tampilan memiliki pengelola layout. Untuk LinearLayout, sistem Android menangani layout untuk Anda. RecyclerView memerlukan pengelola layout eksplisit untuk mengelola susunan item daftar yang terdapat di dalamnya. Layout ini bisa vertikal, horizontal, atau berupa petak.
- Adapter
    Adapter menghubungkan data dengan RecyclerView. Adapter menyiapkan data dan cara menampilkan data dalam view holder. Bila data berubah, adapter akan memperbarui materi tampilan item daftar terkait dalam RecyclerView. Adapter juga merupakan ekstensi dari RecyclerView. Adapter menggunakan ViewHolder untuk menampung tampilan yang menyusun setiap item dalam RecyclerView, dan mengikat data untuk ditampilkan dalam tampilan yang menampilkannya.
- View holder 
    View holder memperluas kelas ViewHolder. View holder berisi tampilan informasi untuk menampilkan satu item dari layout item. View holder digunakan oleh adapter untuk menyediakan data, yang merupakan ekstensi dari *RecyclerView.ViewHolder*. 

Pengelola Layout

Pengelola layout memosisikan tampilan item di dalam grup tampilan, seperti RecyclerView dan menentukan kapan harus menggunakan kembali tampilan item yang tidak lagi terlihat oleh pengguna. Untuk menggunakan kembali (atau mendaur ulang) tampilan, pengelola layout bisa meminta adapter untuk mengganti materi tampilan dengan elemen lain dari kumpulan data. Mendaur ulang tampilan dengan cara ini akan meningkatkan kinerja karena menghindari pembuatan tampilan yang tidak diperlukan atau melakukan pencarian findViewById() yang mahal.

RecyclerView menyediakan semua pengelola layout bawaan ini:

LinearLayoutManager menampilkan item dalam daftar gulir vertikal atau horizontal.
GridLayoutManager menampilkan item dalam petak.
StaggeredGridLayoutManager menampilkan item dalam petak zigzag.