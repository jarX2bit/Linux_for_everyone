<h2 class="blog-post-title mb-1">27 Perintah Dasar Linux</h2>

<h3>cd (change directory)</h3>
<p>Cd atau change directory digunakan untuk berpindah dari folder satu ke folder lain dalam terminal atau shell di linux.</p>

<h3>pwd (print woring directory)</h3>
<p>Commnad pwd digunakan untuk melihat directory kamu berada di sini.</p>

<h3>ls (list)</h3>
<p>ls adalah perintah untuk melihat direktori di Linux. Perintah ini digunakan untuk melihat atau menampilkan/menampilkan daftar isi direktori/folder di Linux. Jika kamu mengetik secara langsung, isi folder tempat kamu berada saat ini akan ditampilkan. kamu juga dapat menggunakannya untuk melihat isi folder lain dengan menambahkan folder tersebut setelah perintah ls. Misalnya, kamu dapat melihat isi direktori /etc/ dengan perintah ls /etc.
</p>

<h3>touch</h3>
<p>Touch merupakan perintah termudah untuk membuat file kosong dan bisa digunakan juga untuk merubah timestamp. Untuk membuat sebuh file kosong cukup kamu ketikkan touch namafile1 kamu juga bisa membuat banyak file kosong sekaligus dengan mengetikan nama file lebih dari satu dipisahkan dengan spasi. Contoh: touch namafile1 namafile2 namafile3.</p>

<h3>mkdir</h3>
<p>Perintah ini digunakan untuk membuat direktori kosong. Cukup mengetik direktori mkdir akan membuat direktori tempat kamu berada. Jika kamu ingin membuat folder di tempat lain tanpa membuka folder ini, kamu dapat menggunakan perintah mkdir /path/folder.</p>

<h3>cp (copy)</h3>
<p>Digunakan untuk menyalin dan menempel file dan folder dan cukup mudah digunakan. Cukup ketik cp /path/file/origin /path/file/destination.</p>

<h3>mv (move)</h3>
<p>Untuk memindahkan dan mengganti nama file atau folder mv /path/origin /path/destination Jika tujuan sama dengan asal, cara ini bisa digunakan untuk mengganti nama file dan folder di Linux.</p>

<h3>rm (remove)</h3>
<p>Perintah rm di Linux dapat digunakan untuk menghapus file atau direktori apa pun, dan menambahkan opsi -rf akan menghapus seluruh direktori dan isinya. Contoh: kamu menghapus folder yang juga berisi folder dan file, jadi kamu harus menggunakan opsi -rf, mis. Misalnya. rm -rf direktori saya.</p>

<h3>rmdir (remove directory)</h3>
<p>Perintah rmdir hanya dapat digunakan untuk menghapus direktori/folder kosong. Jika kamu ingin menghapus folder yang memuatnya, kamu dapat menggunakan perintah rm -rf foldername.</p>
 
<h3>du (disk usage)</h3>
<p>Dua perintah digunakan untuk menampilkan ruang yang digunakan oleh file atau folder. Misalnya, kamu dapat menemukan ukuran file dan folder di direktori /var/www/html dengan perintah du -sch /var/www/html/*.</p>

<h3>cat</h3>
<p>cat (kependekan dari dri concatenate) adalah salah satu perintah dasar yang paling banyak digunakan dalam sistem operasi Linux. Perintah ini menampilkan isi file atau isinya ke stkamurd output (sdout). Jalankan perintah ini dengan mengetikkan cat diikuti dengan nama dan ekstensinya. Sebagai contoh: berkas kucing. txt.</p>

<h3>find</h3>
<p>Seperti perintah loc, perintah find dapat digunakan untuk mencari file dan folder. Bedanya, perintah Find More ditujukan untuk mencari file di direktori yang ditentukan. Misalnya, perintah find /home/ -name notes.txt mencari direktori home dan subdirektorinya untuk file bernama notes.txt. Berikut adalah beberapa variasi yang bekerja dengan baik dengan pencarian: penemuan – Beri nama notes.txt untuk mencari file di direktori saat ini. / -type d -nama notes.txt untuk mencari folder.</p>
    
<h3>grep</h3>
<p>Perintah dasar Linux lainnya yang sangat berguna untuk melakukan tugas sehari-hari adalah grep. kamu dapat menggunakan perintah ini untuk mencari file tertentu di seluruh teks. Misalnya, ketik grep blue notepad.txt untuk mencari kata blue di file Notepad. Baris dengan kata yang kamu cari ditampilkan sepenuhnya.</p>
            
<h3>sudo</h3>
<p>sudo merupakan singkatan dari “SuperUser Do” dan berfungsi untuk menjalankan task yang memerlukan izin (permission) administrative atau root. Namun, kami tidak menyarankan penggunaan command sudo untuk task harian karena bisa terjadi error kapan saja bila kamu melakukan kesalahan.</p>

<h3>df</h3>
<p>Gunakan perintah df untuk mendapatkan laporan tentang penggunaan ruang disk sistem. Laporan yang diberikan dalam format persentase dan kilobit. Untuk melihat laporan dalam megabita, ketik df -m.</p>
        
<h3>head</h3>
<p>Perintah utama digunakan untuk menampilkan baris pertama dari semua file teks. Secara default, perintah ini menampilkan sepuluh baris pertama. Namun, jumlah baris dapat diubah sesuka hati. Misalnya, jika kamu hanya ingin menampilkan lima baris pertama, masukkan head -n 5 filename.ext</p>

<h3>tail</h3>
<p>Perintah tail memiliki fungsi yang sama dengan perintah head. Hanya saja, alih-alih baris pertama, perintah tail akan menampilkan sepuluh baris terakhir dari suatu file. Misalnya, tail -n filename.ext.</p>
        
<h3>diff</h3>
<p>diff adalah perintah dasar Linux yang membandingkan konten atau isi dua file berdasarkan baris demi baris. Setelah menganalisis file, perintah ini akan menghasilkan output berupa line atau baris yang tidak cocok. Programmer sering menggunakan command ini ketika mereka perlu membuat perubahan program, alih-alih menulis kembali semua kode source. Format paling sederhana dari command dasar Linux ini adalah diff file1.ext file2.ext.</p>

<h3>tar</h3>
<p>tar adalah perintah Linux yang paling umum digunakan untuk mengarsipkan banyak file dalam tarball - format file Linux yang mirip dengan zip, di mana fitur kompresi bersifat opsional. Perintah dasar dari sistem operasi Linux ini cukup kompleks dan memiliki daftar operasi yang panjang seperti menambahkan file baru ke arsip yang sudah ada, membuat daftar isi arsip, mengekstrak isi arsip dan banyak lagi. Informasi lebih lanjut tentang fungsi lain dapat ditemukan di sini dalam contoh sederhana.</p>
    
<h3>chmod</h3>
<p>chmod adalah perintah dasar Linux lainnya yang digunakan untuk membaca, menulis, dan menjalankan permission (izin) file dan direktori. Karena perintah ini cukup sulit, maka untuk menjalankannya, silakan baca tutorial lengkap ini terlebih dulu.</p>

<h3>chown</h3>
<p>Di sistem operasi Linux, semua file milik pengguna tertentu. Perintah Linux dasar, chown memungkinkan kamu mengubah kepemilikan file atau mentransfernya ke nama pengguna tertentu atau yang ditentukan. Misalnya, chown linuxuser2 file.ext menetapkan linuxer2 sebagai pemilik file.ext.</p>

<h3>jobs</h3>
<p>Perintah jobs akan menampilkan semua jobs saat ini beserta dengan statusnya. Pada dasarnya job merupakan proses yang dimulai oleh shell.</p>

<h3>kiil</h3>
<p>Jika tidak ada program yang merespons, kamu dapat mematikannya secara manual menggunakan perintah Linux kill. Perintah ini mengirimkan beberapa sinyal ke aplikasi bermasalah dan memberi tahu aplikasi untuk berhenti sendiri atau mati. Total ada 64 sinyal yang tersedia, namun umumnya hanya dua sinyal yang digunakan, yaitu: SIGTERM (15) - memberi tahu program untuk berhenti dan memberinya waktu untuk menyimpan semua kemajuan. Jika tidak ada sinyal khusus yang ditentukan saat perintah kill dikeluarkan, sinyal tersebut akan digunakan. SIGKILL(9) - memaksa program untuk segera berhenti. Progres yang belum disimpan akan hilang. Selain sinyal, kamu juga perlu mengetahui nomor identifikasi proses (PID) dari program yang ingin kamu hentikan. Jika kamu tidak mengetahui PID, kamu dapat menjalankan perintah ps ux. Setelah kamu mengetahui sinyal yang akan digunakan dan PID program, masukkan sintaks ini: matikan [opsi sinyal] PID.</p>
   
<h3>ping</h3>
<p>Perintah ping memeriksa status koneksi ke server. Misalnya, jika kamu menambahkan ping google.com, perintah tersebut akan memeriksa apakah kamu terhubung ke Google atau tidak dan juga mengukur waktu respons.</p>

<h3>wget</h3>
<p>Perintah dasar Linux ini sangat berguna - kamu bahkan dapat menggunakan perintah wget untuk mengunduh file dari Internet. Yang harus kamu lakukan adalah mengetik wget diikuti dengan tautan unduhan.</p>

<h3>uname</h3>
<p>uname, kependekan dari Unix-like name, adalah perintah dasar sistem operasi Linux yang mencetak informasi lengkap tentang sistem Linux, mis. B. Nama komputer, sistem operasi, kernel, dll.</p>

<h3>top</h3>
<p>Sebagai Terminal yang setara dengan Windows Task Manager, perintah di atas menampilkan daftar proses yang sedang berjalan dan berapa banyak ruang CPU yang digunakan setiap proses. Pemantauan penggunaan sumber daya sistem sangat dianjurkan, terutama ketika kamu perlu mengetahui proses mana yang perlu dimatikan karena terlalu banyak menggunakan sumber daya.</p>

                                          
