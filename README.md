 Mars Photos 
==================================

Aplikasi Mars Photos adalah aplikasi demo yang menampilkan gambar sebenarnya dari permukaan Mars. Gambar-gambar ini adalah
foto kehidupan nyata dari Mars yang diambil oleh penjelajah Mars NASA. Data disimpan di server Web
sebagai layanan web REST.


### Mendapatkan Data dari Internet
Proyek di tahap ini (repo-starter) bertujuan untuk mengajarkan dasar pengambilan data dari API. Langkah-langkahnya melibatkan konfigurasi endpoint API, membuat antarmuka untuk mendefinisikan permintaan HTTP, serta mendeserialisasi respons JSON menjadi objek data Kotlin. Data yang diterima dari internet kemudian diproses untuk digunakan dalam aplikasi. Tahap ini fokus pada memahami konsep dasar komunikasi jaringan dalam aplikasi Android.

### Menambahkan repositori dan DI Manual
Pada tahap ini (coil-starter), proyek melanjutkan pengembangan dengan menambahkan layer repositori untuk memisahkan logika pengambilan data dari komponen UI, seperti ViewModel. Anda akan belajar membuat repositori yang bertugas menangani semua interaksi dengan API dan menyediakannya sebagai dependensi ke ViewModel menggunakan Dependency Injection (DI) Manual. Teknik ini membantu menciptakan kode yang lebih modular, terstruktur, dan fleksibel untuk pengembangan aplikasi skala besar. Fokus utama tahap ini adalah mengajarkan arsitektur aplikasi yang lebih baik, di mana setiap komponen memiliki tanggung jawab yang jelas.

### Memuat dan menampilkan gambar dari internet
Tahap terakhir (main) melibatkan pengintegrasian library Coil (Coroutine Image Loader) untuk memuat dan menampilkan gambar dari internet dengan efisien. Langkah-langkah mencakup konfigurasi Coil untuk menampilkan foto Mars yang diambil dari API langsung di antarmuka pengguna. Library ini mendukung Jetpack Compose dan memungkinkan pengelolaan cache, placeholder, serta pemuatan gambar secara dinamis. Fokus tahap ini adalah menciptakan pengalaman pengguna yang mulus dan profesional dengan menampilkan elemen visual langsung dari sumber jaringan.

### Preview
![Screenshot_2024-11-30-09-24-56-78_a309694de1f2fbf3c0e5f24526b7d325](https://github.com/user-attachments/assets/930fad66-0fa9-49f3-89be-3471cc7a9d5f)

![Screenshot_2024-11-30-10-10-24-25_a309694de1f2fbf3c0e5f24526b7d325](https://github.com/user-attachments/assets/b8be1546-c6de-48b2-8557-fac44ff90016)

