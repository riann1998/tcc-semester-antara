## Docker Compose
Compose merupakan alat untuk mendefinisikan dan menjalankan aplikasi multi-container Docker. Dengan Compose, file YAML digunakan untuk mengonfigurasi layanan aplikasi. Kemudian, dengan satu perintah dapat membuat dan memulai semua layanan dari konfigurasi YAML.
Menggunakan Compose pada dasarnya memiliki 3 langkah proses:
    1. menetapkan lingkungan aplikasi dengan Dockerfile sehingga dapat direproduksi di mana saja
    2. menentukan layanan yang membentuk aplikasi di docker-compose.yml sehingga aplikasi tersebut dapat dijalankan bersama di lingkungan yang terisolasi.
    3. Jalankan docker-compose up dan Compose dimulai dan jalankan seluruh aplikasi.
## Docker Network
perintah Docker network digunakan untuk mengelola jaringan. dapat menggunakan sub perintah untuk membuat(create), memeriksa(inspect), mendaftar(list), menghapus(remove), memangkas(prune), menghubungkan(connect), dan memutuskan jaringan(disconnect networks).