## Mock Test
Faisal Baqir Tahmidi
Fullstack Web 36 - Binar Academy

# 1. Apakah Kegunaan JSON pada REST API?
Pada REST API, JSON digunakan untuk merepresentasikan data yang dikirimkan oleh server kepada klien. Kegunaan JSON pada REST API yaitu:
- Memudahkan pertukaran data antar aplikasi. JSON adalah format data yang standar dan umum digunakan, sehingga memudahkan aplikasi untuk saling berkomunikasi.
- Meningkatkan efisiensi. JSON adalah format data yang ringan, sehingga dapat meningkatkan efisiensi pengiriman data melalui jaringan.
- Meningkatkan keterbacaan. JSON adalah format data yang mudah dibaca dan ditulis, sehingga dapat meningkatkan keterbacaan dan pemahaman terhadap data yang dikirimkan.

# 2. Jelaskan bagaimana REST API bekerja
REST API bekerja berdasarkan arsitektur REST (Representational State Transfer). Arsitektur REST adalah arsitektur web yang menggunakan protokol HTTP untuk melakukan transfer data.
Pada REST API, klien dapat mengakses data dari server melalui metode HTTP, seperti GET, POST, PUT, dan DELETE. Metode HTTP tersebut digunakan untuk melakukan operasi CRUD (Create, Read, Update, Delete) terhadap data. Berikut beberapa contoh cara kerja REST API:
- Klien mengirimkan permintaan request kepada server. Permintaan tersebut berisi metode HTTP, URL, dan data yang akan dikirimkan ke server.
- Server menerima permintaan dari klien. Server kemudian memproses permintaan tersebut sesuai dengan metode HTTP yang digunakan.
- Server mengirimkan respons kepada klien. Respons tersebut berisi data yang diminta oleh klien.

# 3. Buatlah sebuah website
# Website ToDo List
Saya membuat website ToDo List yang saya namai dengan LifeSimplify. LifeSimplify adalah aplikasi web yang dirancang untuk membantu Anda mengatur dan melacak tugas sehari-hari dengan mudah. Dengan antarmuka yang sederhana dan fungsionalitas yang intuitif, Anda dapat membuat, mengupdate, dan menghapus tugas dengan cepat.

# Fitur:
1. Register dan Login
- Buat akun baru dengan mengisi form register, termasuk username, email dan PIN.
- Gunakan informasi login yang sudah terdaftar untuk masuk ke akun Anda.

2. Autentikasi User
- Memastikan bahwa hanya pengguna yang terautentikasi yang dapat mengakses dan mengelola tugasnya.
- Sistem akan memeriksa keberlanjutan token setelah setiap operasi login atau registrasi.

3. Tambahkan Tugas
- Tambahkan tugas baru dengan mudah menggunakan formulir input yang intuitif.
- Sertakan nama tugas dan deskripsi untuk memberikan detail tambahan.

4. Perbarui Status Tugas
- Perbarui status tugas ketika tugas telah diselesaikan.

5. Filter Tugas
- Filter tugas berdasarkan status, sehingga dapat dengan cepat melihat tugas yang belum selesai atau yang sudah diselesaikan.

6. Hapus Tugas
- Hapus tugas yang sudah tidak diperlukan atau sudah selesai.

# Cara menggunakan aplikasi:
1. Autentikasi
- Akses https://life-simplify.onrender.com/login untuk login atau https://life-simplify.onrender.com/register untuk registrasi jika belum memiliki akun.

2. Tambahkan Tugas
- Setelah login, anda akan diarahkan ke beranda aplikasi, lalu masukkan judul tugas di bidang "Task..."
- Jika diperlukan, tambahkan deskripsi tugas di bidang "Description..."
- Klik tombol "Add" untuk menambahkan tugas.

3. Perbarui Status Tugas
- Temukan tugas yang ingin diperbarui di daftar.
- Jika statusnya "Todo," klik tombol "Update Status" untuk mengubahnya menjadi "Completed."

4. Filter Tugas
Gunakan filter "All," "Completed," atau "Todo" untuk menyaring tugas sesuai dengan statusnya.

5. Hapus Tugas
- Temukan tugas yang ingin dihapus di daftar.
- Klik tombol "Delete" untuk menghapus tugas tersebut.

6. Logout
-Jika ingin keluar, klik tombol "Logout" pada bagian navigasi.

LifeSimplify memberikan keamanan tambahan dengan mengimplementasikan autentikasi pengguna, memastikan bahwa hanya pengguna yang terdaftar yang dapat mengakses dan mengelola tugas mereka. Selamat menggunakan!


Link Website: https://life-simplify.onrender.com/
Link Github Frontend: https://github.com/faisalbaqirt/todolist_frontend
Link Github Backend: https://github.com/faisalbaqirt/todolist_backend