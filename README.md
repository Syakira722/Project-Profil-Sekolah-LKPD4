1. Challenge 2 — Clone Repository

Apa arti hasil git status?
git status digunakan untuk melihat kondisi repository saat ini, seperti branch yang sedang digunakan, apakah ada perubahan file, dan apakah ada perubahan yang belum di-commit.

2. Challenge 3 — Membuat Branch

Mengapa setiap developer tidak langsung bekerja pada main?
Agar pekerjaan setiap developer terpisah dan tidak langsung mengganggu kode utama. Dengan menggunakan branch, setiap fitur dapat dikembangkan dan diperiksa terlebih dahulu sebelum digabungkan ke main. 

3. Challenge 5 — Commit

Apa perbedaannya?
git commit -m "update" memiliki pesan yang terlalu umum sehingga tidak menjelaskan perubahan yang dilakukan
Sedangkan git commit -m "Menambahkan halaman profil kelas" menjelaskan secara jelas perubahan yang dibuat.
Mana yang lebih baik?
git commit -m "Menambahkan halaman profil kelas" lebih baik karena pesan commit jelas dan memudahkan anggota tim mengetahui perubahan yang dilakukan. LKPD juga menekankan bahwa pesan commit harus jelas. 

4. Pertanyaan Analisis

1. Apa fungsi git pull?
git pull digunakan untuk mengambil perubahan terbaru dari repository remote GitHub dan menerapkannya ke repository lokal. 
2. Apa yang terjadi jika programmer tidak melakukan git pull?
Repository lokal dapat tertinggal dari versi terbaru di GitHub. Akibatnya programmer dapat bekerja menggunakan kode yang sudah tidak terbaru dan berpotensi mengalami masalah ketika menggabungkan perubahan.
3. Mengapa main harus dijaga agar tetap stabil?
Karena main merupakan branch utama yang berisi hasil pengembangan yang sudah digabungkan. Menjaga main tetap stabil membantu mencegah kesalahan dan memastikan hasil proyek tetap dapat digunakan oleh seluruh anggota tim. 

5. Pertanyaan Conflict

1. Mengapa conflict terjadi?
Conflict terjadi ketika dua anggota mengubah bagian yang sama dalam sebuah file dengan perubahan yang berbeda sehingga Git tidak dapat menentukan perubahan mana yang harus digunakan secara otomatis. 
2. Apakah conflict berarti Git rusak?
Tidak. Conflict merupakan hal yang normal dalam pengembangan perangkat lunak dan menunjukkan bahwa Git membutuhkan programmer untuk menentukan perubahan yang benar. 
3. Siapa yang harus menentukan versi kode yang benar?
Developer atau anggota tim yang memahami kebutuhan fitur tersebut harus menentukan perubahan yang benar, dengan berkoordinasi dengan anggota tim lainnya.
4. Mengapa komunikasi antar programmer penting?
Karena komunikasi membantu anggota tim memahami perubahan yang sedang dikerjakan, menghindari pekerjaan yang bertabrakan, dan menentukan solusi ketika terjadi conflict.

6. Refleksi Individu

1. Apa perbedaan bekerja sendiri dengan bekerja menggunakan Git dan GitHub?
Saat bekerja sendiri, perubahan kode dikelola secara pribadi. Dengan Git dan GitHub, beberapa developer dapat bekerja pada fitur masing-masing, melakukan commit, push, Pull Request, review, dan merge secara terorganisir
2. Apa manfaat branch?
Branch memungkinkan developer mengerjakan fitur secara terpisah tanpa langsung mengubah main.
3. Mengapa Pull Request diperlukan?
Pull Request diperlukan agar perubahan dari sebuah branch dapat diperiksa dan direview terlebih dahulu sebelum digabungkan ke main. 
4. Apa manfaat Code Review?
Code Review membantu menemukan kesalahan, memeriksa kualitas kode, memastikan informasi sesuai tugas, dan memberikan kesempatan untuk memperbaiki kode sebelum di-merge. 
5. Error apa yang paling sulit kalian selesaikan?
Error yang paling sulit bagi saya adalah kesalahan penulisan perintah Git, terutama ketika lupa memberikan spasi pada perintah seperti git commit -m dan git push -u.
6. Bagaimana kalian menemukan solusinya?
Saya membaca pesan error pada Terminal, kemudian mencari penyebab kesalahan dan memperbaiki format perintah Git. Setelah itu saya menjalankan kembali perintah tersebut sampai berhasil.
7. Apa kontribusi terbesar kalian dalam kelompok?
Kontribusi terbesar saya adalah mengerjakan fitur halaman anggota, membuat tampilan HTML dan CSS, melakukan commit, push branch, serta mengirim perubahan melalui Pull Request.
8. Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan?
Saya akan mempertahankan kebiasaan menggunakan branch, membuat commit dengan pesan yang jelas, melakukan Pull Request dan Code Review, serta selalu membaca pesan error sebelum mencari solusinya.

1. Sebelum belajar GitHub, saya berpikir bahwa...
GitHub hanya digunakan untuk menyimpan kode secara online.
2. Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa...
GitHub dapat digunakan untuk membantu developer bekerja sama, mengelola branch, melakukan Pull Request, Code Review, dan merge.
3. Kesalahan/error yang saya alami mengajarkan saya bahwa...
Saya harus lebih teliti dalam mengetik perintah dan membaca pesan error untuk mengetahui penyebab masalah.
4. Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan...
Menggunakan branch sesuai tugas, membuat commit yang jelas, berkomunikasi dengan anggota tim, dan melakukan review sebelum perubahan digabungkan ke main.
