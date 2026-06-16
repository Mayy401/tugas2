Sistem Informasi Jadwal Kelas
Aplikasi ini berguna untuk siswa yang ingin melihat jam pelajaran keberapa, pelajaran apa, dan siapa guru yang mengajar secara mudah (bagian jadwalnya belum beres karena ascnya tidak bisa dipublish). Dibuat menggunakan PHP, MySql, CSS. Memiliki fitur login, logout, register.

Macam-macam fitur
login menggunakan username dan password yang telah dibuat, jika belum memiliki akun maka bisa untuk mendaftar terlebih dahulu.
tersedia semua jadwal kelas dari kelas 10 hingga kelas 12
memiliki daftar guru mengajar
File dan fungsinya
koneksi.php untuk menyambungkan ke database mysql, login.php itu adalah form login untuk user, dan memiliki tombol lanjut untuk masuk ke halaman dashboard.php, register.php untuk user yang belum memiliki akun, maka user harus mendaftar dulu untuk bisa lanjut kehalaman dashboard.php, proses_daftar.php adalah jika user sudah mengisi kolom username dan password dan mengklik tombol daftar, maka data tersebut akan terkirim ke database dan otomatis terdaftarkan sebagai akun, jadi tinggal memasukan data yang dia daftarkan saja maka sudah bisa login ke bagian dashboard.php, proses.php adalah saat user sudah memilih opsi dibagian dashboard.php, maka dibagian proses.php ini akan memilih case yang si user ini pilih, jika user memilih kelas X RPL pada opsi ke 3, maka dalam prosesnya akan memilih case 3, dashboard.php adalah tampilan utama dari website ini, user diharuskan untuk memilih opsi ingin melihat jadwal kelas, atau jadwal guru mengajar, guru.php ini sama seperti dashboard.php tapi bedanya hanya ini untuk memilih opsi guru mengajar, jadwal.css untuk mengatur tampilan dan desain sebuah website, file ini digunakan untuk dashboard.php dan guru.php, style.css ini juga sama untuk mengatur tampilan dan desain sebuah website, file ini digunakan untuk login.php dan register.php.

Alur pengerjaan webnya
Pertama-tama user harus mengisi form login, jika belum memiliki akun maka diperkenankan untuk daftar terlebih dahulu, user harus mengisi username dan password, jika sudah data tersebut akan terkirim ke database mysql dan terbentuk menjadi sebuah akun untuk login, setelah login dan berhasil, user akan langsung diarahkan ke bagian dashboard.php, disitu user akan diharuskan untuk memilih jadwal pelajaran kelas atau jadwal guru mengajar, jika jadwal guru mengajar maka halamannya akan dipindahkan lagi ke bagian guru.php, dan jika user memilih kelas XI RPL A pada opsi ke 6 maka dibagian proses.php akan mengalihkan halaman pada case 6 dan akan diarahkan sesuai dengan link yang diberi dalam case tersebut.

Database
Hanya memiliki 4 kolom utama, yaitu id, username, password, created_at.

Bahasa pemrograman yang digunakan pada website ini
PHP
CSS
HTML
MYSQL (DATABASE)
