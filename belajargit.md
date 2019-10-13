#Belajar GIT
Apa itu Git dan Kenapa Penting bagi Programmer?

Belajar Git untuk Pemula

Git adalah salah satu tool yang sering digunakan dalam proyek pengembangan software.

Git bahkan menjadi tool yang wajib dipahami oleh programmer, karena banyak digunakan di mana-mana.

Pada kesempatan ini kita akan belajar Git dari dasar.

Artikel ini hanya akan membahas pengenalan Git saja. Untuk mempelajari Git lebih lanjut, saya sudah menyediakan link di bagian akhir.
Mengenal Git

Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.

Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.

Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

<img src="https://d33wubrfki0l68.cloudfront.net/5d30666dda588f5e24d11ad4ba9bc2b9e5202cf8/cc89a/img/git/sistem-git.png">

Sistem VSC Terdistribusi

Semua orang yang terlibat dalam pengkodean proyek akan menyimpan database Git, sehingga akan memudahkan dalam mengelola proyek baik online maupun offline.

Dalam Git terdapat merge untuk menyebut aktifitas penggabungan kode.

Sedangkan pada VCS (Version Control System) yang terpusat… database disimpan dalam satu tempat dan setiap perubahan disimpan ke sana.

Sistem VCS Terpusat

VCS terpusat memiliki beberapa kekurangan:

    Semua tim harus terkoneksi ke jaringan untuk mengakses source-code;
    Tersimpan di satu tempat, nanti kalau server bermasalah bagaimana?

Karena itu, Git hadir untuk menutupi kerkurangan yang dimiliki oleh VCS terpusat.
Apa yang dilakukan oleh Git?

Git sebenarnya akan memantau semua perubahan yang terjadi pada file proyek. Lalu menyimpannya ke dalam database.

Sebelum menggunakan Git:
<img src="https://d33wubrfki0l68.cloudfront.net/71ed5b84cb44b653bfd07c85849cff210fdf5404/a2798/img/git/revisi-tanpa-git.png">

Revisi File tanpa Git

Setelah menggunakan Git:
<img src="https://d33wubrfki0l68.cloudfront.net/6b9ec3079ab5698d7a74ddddbc7f691ee84417bf/ce8f5/img/git/database-git.png">

Revisi File dengan Git

Apa perbedaannya?

Saat kita ingin menyimpan semua perubahan pada file, biasanya kita membuat file baru dengan “save as”. Lalu, file akan menumpuk dalam direktori proyek seperti pada ilustrasi di atas.

Tapi setelah menggunakan Git…

Hanya akan ada satu file dalam proyek dan perubahannya disimpan dalam database.

Git hanya akan menyimpan delta perubahannya saja, dia tidak akan menyimpan seluruh isi file yang akan memakan banyak memori.

Git memungkinkan kita kembali ke versi revisi yang kita inginkan.
Kenapa Git Penting Bagi Programmer?

Git untuk kolaborasi kode

Jadi selain untuk mengontrol versi, git juga digunakan untuk kolaborasi.

Saat ini Git menjadi salah satu tool terpopuler yang digunakan pada pengembangan software open souce maupun closed source.

Google, Microsoft, Facebook dan berbagai perusahaan raksasa lainnya menggunakan Git.

Jadi, buat kamu yang punya impian ingin bekerja di sana, maka kamu harus bisa Git
