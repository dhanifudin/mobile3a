Nama	: Muhammad Navis Abdillah
Nim	: 1941720147
No	: 14

ListView & RecyclerView

ListView
•	Dalam development Android, setiap kali kami ingin menampilkan daftar vertikal item yang dapat digulir, kami akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor
•	Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

Custom ArrayAdaptar
•	Definisi Model
•	Membuat View Template
•	Definisi Adapter -> ArrayAdapter Inheritance
•	Memasang Adapter ke ListView
•	Mengisi data ke ListView

RecyclerView
•	RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView.
•	Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Anda menentukan view holder dengan memperluas RecyclerView.ViewHolder.
•	RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.
•	Layout Manager mengatur elemen individual dalam daftar Anda. Anda dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau Anda dapat menentukan sendiri. Layout Manager semuanya didasarkan pada library's LayoutManager abstract class.

LayoutManagers
RecyclerView menyediakan pengelola layout managers :
•	LinearLayoutManager menampilkan item dalam daftar gulir vertikal atau horizontal.
•	GridLayoutManager menampilkan item dalam kotak.
•	StaggeredGridLayoutManager menampilkan item dalam staggered grid.


