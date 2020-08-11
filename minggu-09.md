## Docker swarm 
adalah container orchestration toolatau alat orkestrasi kontainer.
Pada Docker Swarm Cluster ini terdapat 2 bagian utama sebagai unsur yaitu, Swarm manager dan Swarm Worker.
    1. Swarm Manager memiliki tugas salah satunya membuat dan melakukan cluster service, selain itu swarm manager juga bertugas menyediakan HTTP API Endpoints.
    2. Swarm Worker bertugas untuk menjalankan container atau service yang telah di definisikan pada Swarm Manager.
Untuk memvalidasi bahwa aplikasi dalam container berfungsi dengan baik di Swarm, menggunakan lingkungan Swarm bawaan Docker Desktop tepat di mesin pengembangan untuk menerapkan aplikasi, sebelum dijalankan di cluster Swarm penuh dalam produksi. Lingkungan Swarm yang dibuat oleh Docker Desktop berfitur lengkap, yang berarti ia memiliki semua fitur Swarm yang akan dinikmati aplikasi di real cluster atau kluster nyata.
Swarm tidak pernah membuat wadah individual. Sebagai gantinya, semua beban kerja Swarm dijadwalkan sebagai layanan, yang merupakan grup kontainer yang dapat diskalakan dengan fitur jaringan tambahan yang dikelola secara otomatis oleh Swarm. Selanjutnya, semua objek Swarm dapat dan harus dijelaskan dalam manifes yang disebut file tumpukan(stack).
