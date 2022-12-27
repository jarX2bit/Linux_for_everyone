
<h1 class="blog-post-title mb-1">27 Perintah Dasar Linux</h1>

<h3>cd (change directory)</h3>
<p>Cd atau change directory digunakan untuk berpindah dari folder satu ke folder lain dalam terminal atau shell di linux.</p>

![cd shell](https://user-images.githubusercontent.com/86142230/209636893-d8c994da-27f9-43f8-98de-b6ad28eb980a.png)

<h3>pwd (print woring directory)</h3>
<p>Commnad pwd digunakan untuk melihat directory kamu berada di sini.</p>

![pwd shell](https://user-images.githubusercontent.com/86142230/209636939-7c4f054b-50e4-4de4-91da-0b2f6793c6ed.png)


<h3>ls (list)</h3>
<p>ls adalah perintah untuk melihat direktori di Linux. Perintah ini digunakan untuk melihat atau menampilkan/menampilkan daftar isi direktori/folder di Linux. Jika kamu mengetik secara langsung, isi folder tempat kamu berada saat ini akan ditampilkan. kamu juga dapat menggunakannya untuk melihat isi folder lain dengan menambahkan folder tersebut setelah perintah ls. Misalnya, kamu dapat melihat isi direktori /etc/ dengan perintah ls /etc.
</p>

![ls shell](https://user-images.githubusercontent.com/86142230/209637345-061d24e8-0824-4a70-812b-ab109642b886.png)

<h3>touch</h3>
<p>Touch merupakan perintah termudah untuk membuat file kosong dan bisa digunakan juga untuk merubah timestamp. Untuk membuat sebuh file kosong cukup kamu ketikkan touch namafile1 kamu juga bisa membuat banyak file kosong sekaligus dengan mengetikan nama file lebih dari satu dipisahkan dengan spasi. Contoh: touch namafile1 namafile2 namafile3.</p>

![touchshell](https://user-images.githubusercontent.com/86142230/209637395-02502b7f-5e28-47e0-b6eb-179fb064ef8e.png)

<h3>mkdir</h3>
<p>Perintah ini digunakan untuk membuat direktori kosong. Cukup mengetik direktori mkdir akan membuat direktori tempat kamu berada. Jika kamu ingin membuat folder di tempat lain tanpa membuka folder ini, kamu dapat menggunakan perintah mkdir /path/folder.</p>

![mkdir shell](https://user-images.githubusercontent.com/86142230/209637349-d7fa72b7-dcb6-49ec-b692-ae2d665cd001.png)

<h3>cp (copy)</h3>
<p>Digunakan untuk menyalin dan menempel file dan folder dan cukup mudah digunakan. Cukup ketik cp /path/file/origin /path/file/destination.</p>

![cp shell](https://user-images.githubusercontent.com/86142230/209637304-debb7b75-55ca-42a4-9e28-6d691c5bf1c4.png)

<h3>mv (move)</h3>
<p>Untuk memindahkan dan mengganti nama file atau folder mv /path/origin /path/destination Jika tujuan sama dengan asal, cara ini bisa digunakan untuk mengganti nama file dan folder di Linux.</p>

![mv shell](https://user-images.githubusercontent.com/86142230/209637351-67ddd2ab-5de8-4c4f-b3bd-dfa421ae3109.png)

<h3>rm (remove)</h3>
<p>Perintah rm di Linux dapat digunakan untuk menghapus file atau direktori apa pun, dan menambahkan opsi -rf akan menghapus seluruh direktori dan isinya. Contoh: kamu menghapus folder yang juga berisi folder dan file, jadi kamu harus menggunakan opsi -rf, mis. Misalnya. rm -rf direktori saya.</p>

![rm shell](https://user-images.githubusercontent.com/86142230/209637365-0b847473-31a5-4a12-a8d6-40a8f44e5054.png)

<h3>rmdir (remove directory)</h3>
<p>Perintah rmdir hanya dapat digunakan untuk menghapus direktori/folder kosong. Jika kamu ingin menghapus folder yang memuatnya, kamu dapat menggunakan perintah rm -rf foldername.</p>
 
 ![rmdir shell](https://user-images.githubusercontent.com/86142230/209637362-23c862e9-834d-4542-ab2b-96b66786374a.png)

<h3>du (disk usage)</h3>
<p>Dua perintah digunakan untuk menampilkan ruang yang digunakan oleh file atau folder. Misalnya, kamu dapat menemukan ukuran file dan folder di direktori /var/www/html dengan perintah du -sch /var/www/html/*.</p>

![du shell](https://user-images.githubusercontent.com/86142230/209637320-9660a599-3873-425f-9d13-ae0bd220146c.png)

<h3>cat</h3>
<p>cat (kependekan dari dri concatenate) adalah salah satu perintah dasar yang paling banyak digunakan dalam sistem operasi Linux. Perintah ini menampilkan isi file atau isinya ke stkamurd output (sdout). Jalankan perintah ini dengan mengetikkan cat diikuti dengan nama dan ekstensinya. Sebagai contoh: berkas kucing. txt.</p>

![cat shell](https://user-images.githubusercontent.com/86142230/209637276-2891ea7d-9e0b-4ac2-8172-469d342ae370.png)

<h3>find</h3>
<p>Seperti perintah loc, perintah find dapat digunakan untuk mencari file dan folder. Bedanya, perintah Find More ditujukan untuk mencari file di direktori yang ditentukan. Misalnya, perintah find /home/ -name notes.txt mencari direktori home dan subdirektorinya untuk file bernama notes.txt. Berikut adalah beberapa variasi yang bekerja dengan baik dengan pencarian: penemuan – Beri nama notes.txt untuk mencari file di direktori saat ini. / -type d -nama notes.txt untuk mencari folder.</p>
 
![find shell](https://user-images.githubusercontent.com/86142230/209637326-6bb4aef3-adb7-48a6-8ef6-d23515465898.png) 
 
<h3>grep</h3>
<p>Perintah dasar Linux lainnya yang sangat berguna untuk melakukan tugas sehari-hari adalah grep. kamu dapat menggunakan perintah ini untuk mencari file tertentu di seluruh teks. Misalnya, ketik grep blue notepad.txt untuk mencari kata blue di file Notepad. Baris dengan kata yang kamu cari ditampilkan sepenuhnya.</p>
   
![grep shell](https://user-images.githubusercontent.com/86142230/209637331-f58badb2-1122-40c6-aa65-728b994d69b2.png)   
   
<h3>sudo</h3>
<p>sudo merupakan singkatan dari “SuperUser Do” dan berfungsi untuk menjalankan task yang memerlukan izin (permission) administrative atau root. Namun, kami tidak menyarankan penggunaan command sudo untuk task harian karena bisa terjadi error kapan saja bila kamu melakukan kesalahan.</p>

![sudo su](https://user-images.githubusercontent.com/86142230/209637372-512f600f-eaa0-4868-a672-b106c5a390bc.png)

<h3>df</h3>
<p>Gunakan perintah df untuk mendapatkan laporan tentang penggunaan ruang disk sistem. Laporan yang diberikan dalam format persentase dan kilobit. Untuk melihat laporan dalam megabita, ketik df -m.</p>
  
![df shell](https://user-images.githubusercontent.com/86142230/209637311-fe615b92-4673-4492-963d-f6f955c80555.png)  
  
<h3>head</h3>
<p>Perintah utama digunakan untuk menampilkan baris pertama dari semua file teks. Secara default, perintah ini menampilkan sepuluh baris pertama. Namun, jumlah baris dapat diubah sesuka hati. Misalnya, jika kamu hanya ingin menampilkan lima baris pertama, masukkan head -n 5 filename.ext</p>

![head shell](https://user-images.githubusercontent.com/86142230/209637335-48a5e4ee-058a-4bdd-8b34-f38873bbee6a.png)

<h3>tail</h3>
<p>Perintah tail memiliki fungsi yang sama dengan perintah head. Hanya saja, alih-alih baris pertama, perintah tail akan menampilkan sepuluh baris terakhir dari suatu file. Misalnya, tail -n filename.ext.</p>

![tail shell](https://user-images.githubusercontent.com/86142230/209637379-19c2b633-c8e3-473d-866f-cc7c80607537.png)

<h3>diff</h3>
<p>diff adalah perintah dasar Linux yang membandingkan konten atau isi dua file berdasarkan baris demi baris. Setelah menganalisis file, perintah ini akan menghasilkan output berupa line atau baris yang tidak cocok. Programmer sering menggunakan command ini ketika mereka perlu membuat perubahan program, alih-alih menulis kembali semua kode source. Format paling sederhana dari command dasar Linux ini adalah diff file1.ext file2.ext.</p>

![diff shell](https://user-images.githubusercontent.com/86142230/209637317-2c0cba0b-ca60-49a5-a38c-b842ddb942ee.png)

<h3>tar</h3>
<p>tar adalah perintah Linux yang paling umum digunakan untuk mengarsipkan banyak file dalam tarball - format file Linux yang mirip dengan zip, di mana fitur kompresi bersifat opsional. Perintah dasar dari sistem operasi Linux ini cukup kompleks dan memiliki daftar operasi yang panjang seperti menambahkan file baru ke arsip yang sudah ada, membuat daftar isi arsip, mengekstrak isi arsip dan banyak lagi. Informasi lebih lanjut tentang fungsi lain dapat ditemukan di sini dalam contoh sederhana.</p>

![tar shell](https://user-images.githubusercontent.com/86142230/209637389-ef845d18-b460-412f-baa2-a85198622756.png)

<h3>chmod</h3>
<p>chmod adalah perintah dasar Linux lainnya yang digunakan untuk membaca, menulis, dan menjalankan permission (izin) file dan direktori. Karena perintah ini cukup sulit, maka untuk menjalankannya, silakan baca tutorial lengkap ini terlebih dulu.</p>

![chmod shell](https://user-images.githubusercontent.com/86142230/209637296-1d983d8f-70bb-432f-9c32-9a64b7d37563.png)

<h3>chown</h3>
<p>Di sistem operasi Linux, semua file milik pengguna tertentu. Perintah Linux dasar, chown memungkinkan kamu mengubah kepemilikan file atau mentransfernya ke nama pengguna tertentu atau yang ditentukan. Misalnya, chown linuxuser2 file.ext menetapkan linuxer2 sebagai pemilik file.ext.</p>

![chown shell](https://user-images.githubusercontent.com/86142230/209637302-ff9ae4cf-e494-403c-9405-636f885f7fc3.png)

<h3>jobs</h3>
<p>Perintah jobs akan menampilkan semua jobs saat ini beserta dengan statusnya. Pada dasarnya job merupakan proses yang dimulai oleh shell.</p>

![jobs shell](https://user-images.githubusercontent.com/86142230/209637338-5b7cd8f7-cd19-4d8e-b57d-8e6413d0e9ba.png)

<h3>kiil</h3>
<p>Jika tidak ada program yang merespons, kamu dapat mematikannya secara manual menggunakan perintah Linux kill. Perintah ini mengirimkan beberapa sinyal ke aplikasi bermasalah dan memberi tahu aplikasi untuk berhenti sendiri atau mati. Total ada 64 sinyal yang tersedia, namun umumnya hanya dua sinyal yang digunakan, yaitu: SIGTERM (15) - memberi tahu program untuk berhenti dan memberinya waktu untuk menyimpan semua kemajuan. Jika tidak ada sinyal khusus yang ditentukan saat perintah kill dikeluarkan, sinyal tersebut akan digunakan. SIGKILL(9) - memaksa program untuk segera berhenti. Progres yang belum disimpan akan hilang. Selain sinyal, kamu juga perlu mengetahui nomor identifikasi proses (PID) dari program yang ingin kamu hentikan. Jika kamu tidak mengetahui PID, kamu dapat menjalankan perintah ps ux. Setelah kamu mengetahui sinyal yang akan digunakan dan PID program, masukkan sintaks ini: matikan [opsi sinyal] PID.</p>
 
![kill shell](https://user-images.githubusercontent.com/86142230/209637340-20b702be-3c0d-4960-8922-9aeec5021c36.png)

<h3>ping</h3>
<p>Perintah ping memeriksa status koneksi ke server. Misalnya, jika kamu menambahkan ping google.com, perintah tersebut akan memeriksa apakah kamu terhubung ke Google atau tidak dan juga mengukur waktu respons.</p>

![ping shell](https://user-images.githubusercontent.com/86142230/209637353-f7d7c81b-69aa-49f5-bf2b-4c8991e575cd.png)

<h3>wget</h3>
<p>Perintah dasar Linux ini sangat berguna - kamu bahkan dapat menggunakan perintah wget untuk mengunduh file dari Internet. Yang harus kamu lakukan adalah mengetik wget diikuti dengan tautan unduhan.</p>

![wget shell](https://user-images.githubusercontent.com/86142230/209637400-efbc2a24-8aeb-40ad-8e3a-659038b3bfb9.png)

<h3>uname</h3>
<p>uname, kependekan dari Unix-like name, adalah perintah dasar sistem operasi Linux yang mencetak informasi lengkap tentang sistem Linux, mis. B. Nama komputer, sistem operasi, kernel, dll.</p>

![uname shell](https://user-images.githubusercontent.com/86142230/209637398-44b76c63-8533-4a09-a47a-e1e60781afd5.png)

<h3>top</h3>
<p>Sebagai Terminal yang setara dengan Windows Task Manager, perintah di atas menampilkan daftar proses yang sedang berjalan dan berapa banyak ruang CPU yang digunakan setiap proses. Pemantauan penggunaan sumber daya sistem sangat dianjurkan, terutama ketika kamu perlu mengetahui proses mana yang perlu dimatikan karena terlalu banyak menggunakan sumber daya.</p>

![top shell](https://user-images.githubusercontent.com/86142230/209637394-22691187-53d5-468f-9daf-f5f05c1f3f64.png)
                                          
