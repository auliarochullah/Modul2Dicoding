Materi 3 Perencanaan Modifikasi Aplikasi (Modul 2)
==
### Pengantar Perencanaan Modifikasi Aplikasi

di materi ini kita akan membuat perencanaan modifikasi aplikasi perangkat lunak dengan membuat spesifikasi kebutuhan aplikasi perangkat lunak dan diagram alur (atau biasa disebut dengan flowchart).
Berikut pokok-pokok bahasan materi yang akan Anda pelajari, seperti:
- Mengetahui spesifikasi kebutuhan aplikasi perangkat lunak, beserta studi kasusnya.
- Mengetahui cara aplikasi perangkat lunak bekerja dalam komputer
- Menyelesaikan masalah menggunakan cara berpikir sebuah aplikasi, beserta studi kasusnya.
- Mengetahui istilah flowchart, beserta studi kasusnya.
- Serta mengetahui tips sikap kerja dalam kolaborasi perencanaan aplikasi dengan tim.

Spesifikasi Kebutuhan Perangkat Lunak (SKPL) dan Struktur Penulisannya
==
Spesifikasi Kebutuhan Perangkat Lunak (SKPL) adalah sebuah dokumen yang dibuat sebelum mengembangkan sebuah aplikasi perangkat lunak. Dokumen ini menjelaskan cara kerja dan kebutuhan fungsional maupun non-fungsional dari aplikasi yang digunakan pengguna nantinya. 
Bukan hanya itu saja, berikut keuntungan yang bisa didapatkan dari pembuatan dokumen Spesifikasi Kebutuhan Perangkat Lunak:
- Keuntungan pertama adalah seorang desainer UI/UX dalam tim akan mendapat gambaran sehingga mereka dapat mendesain sesuai kebutuhan aplikasi.
- Selain desainer, tim penguji aplikasi (tester) akan mendapatkan panduan untuk membuat studi kasus dalam proses pengujian aplikasi.
- Bukan hanya dari sisi internal tim saja, pengguna akhir (end user) juga akan mendapatkan gambaran umum terkait aplikasi yang akan dibuat.
- Bahkan, dari sisi investor juga akan mendapatkan gambaran umum terkait fitur apa saja yang ada di dalam aplikasi. Sehingga, membantu mereka untuk mengambil keputusan untuk investasi atau tidak.

Berikut cakupan elemen yang ada dalam dokumen Spesifikasi Kebutuhan Perangkat Lunak:
- Mulai dari tujuan aplikasi;
- deskripsi umum;
- kebutuhan fungsional dan non fungsional;
- performa aplikasi dalam proses produksi;
- antarmuka eksternal atau bagaimana sebuah aplikasi berinteraksi dengan perangkat keras dan perangkat lunak lainnya;
- hingga batasan sistem aplikasi yang akan dibuat.

Perbedaan kebutuhan fungsional dan nonfungsional
- Kebutuhan fungsional menggambarkan cara sistem membantu menyelesaikan tugas atau kebutuhan pengguna ketika menggunakan aplikasi.
  Misalnya, dalam aplikasi pesan antar makanan secara daring adalah fitur yang memungkinkan pengguna dapat memilih menu yang tersedia di suatu restoran. Tanpa terpenuhinya kebutuhan fungsional dalam dokumen SKPL, sama halnya dengan Anda meniadakan fungsi atau fitur dari sebuah aplikasi.
- Sedangkan kebutuhan non fungsional berguna untuk mendukung kebutuhan fungsional yang sudah ada.
  Tanpa adanya persyaratan non fungsional, sistem aplikasi masih bisa berjalan untuk memenuhi kebutuhan pengguna.
  Contohnya, ketika pengguna berhasil memesan makanan secara daring, pihak pengemudi (driver) yang mengantarkan makanan
  hanya dapat menghubungi pengguna melalui fitur chat yang disediakan oleh aplikasi. Sehingga, keamanan nomor pribadi pengguna akan terjamin dan tidak diketahui oleh siapa pun.

### Struktur Penulisan Dokumen SKPL

Anda perlu mendeskripsikan kebutuhan untuk pengguna, menjelaskan secara rinci untuk tim pengembang dan penguji, serta menambahkan informasi tentang kemungkinan pengembangan aplikasi di masa mendatang.

Anda juga dapat mengacu pada standar IEEE 1998 untuk menulis dokumen Spesifikasi Kebutuhan Perangkat Lunak. 
Standar ini dapat Anda sesuaikan kembali bergantung pada kebutuhan aplikasi atau perangkat lunak yang ingin dikembangkan. Untuk lebih jelasnya, simak tabel berikut ini:
![Screenshot 2023-08-17 074435](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/dee36ce4-9484-4202-9f42-9d49dcd56024)

Studi Kasus Pembuatan Dokumen Spesifikasi Kebutuhan Perangkat Lunak
==
**Tujuan**
Studi Kasus ini bertujuan untuk memperdalam materi tentang dokumen Spesifikasi Kebutuhan Perangkat Lunak (SKPL). Kita akan menggunakan struktur dokumen SKPL seperti pembahasan materi sebelumnya, tetapi dengan penyesuaian khusus berdasarkan aplikasi yang ingin kita buat.

**Tahapan Proses**
Kali ini kita akan membuat sebuah dokumen SKPL untuk membuat autentikasi dari halaman website. Tenang saja, kita hanya membahas fitur login dan logout dari halaman website secara sederhana.

Pertama, Anda perlu menuliskan struktur kerangka dasar dokumen SKPL. Karena contoh autentikasi website yang akan kita buat cukup sederhana, maka kerangka yang diperlukan adalah sebagai berikut:

**Pengantar**
- 1. Tujuan Aplikasi

Pengguna dapat mengakses suatu halaman web setelah melakukan proses autentikasi dengan memasukkan username dan password.
- 2. Sasaran Pengguna

Semua pengguna atau masyarakat umum yang sudah memiliki hak akses dalam website.

**Kebutuhan Pengguna**

- 1. Deskripsi umum dari aplikasi
  
Autentikasi dari sebuah halaman website adalah hal yang penting. Kita harus mengetahui elemen apa saja yang dibutuhkan untuk masuk ke halaman website seperti email, password, dan tombol login.

Ketika pengguna berhasil melakukan autentikasi dengan memasukkan email dan password dengan benar, maka ia dapat mengakses konten website yang ada di dalamnya. Sedangkan jika pengguna tidak berhasil melakukan proses autentikasi, pengguna tidak dapat mengakses konten yang ada dan harus memeriksa kembali apakah email dan password yang dimasukkan sudah benar.

Supaya lebih aman, ketika pengguna selesai mengakses konten website, ia dapat melakukan proses logout dengan menekan tombol logout yang ada di dalam halaman website tersebut. Setelah logout, pengguna akan keluar dari konten halaman website dan harus melakukan autentikasi kembali untuk bisa masuk.

- 2. Kegunaan aplikasi bagi pengguna
  
Pengguna dapat masuk (login) untuk mengakses konten yang ada di halaman website.
Aplikasi dapat memeriksa penulisan format email di dalam form pengisian email.
Pengguna dapat memasukkan password dengan aman karena antarmuka form password tersamarkan tampilannya.
Pengguna dapat keluar (logout) dari halaman konten website dengan menekan tombol logout.

**Spesifikasi Kebutuhan Sistem**
- 1. Kebutuhan fungsional

Pengguna dapat memasukkan email dan password pada form yang disediakan. Kemudian ketika tombol login ditekan, pengguna yang sudah melengkapi email dan password untuk mengakses konten halaman website.

Pengguna dapat keluar dari konten halaman website dengan menekan tombol logout.

- 2. Kebutuhan non fungsional

Ketika pengguna memasukkan email di dalam form email, sistem dapat memeriksa apakah inputan tersebut sudah sesuai dengan struktur email yang benar. Jika tidak sesuai, pengguna diberi pengingat bahwa belum mengisi form email dengan benar.

Ketika pengguna memasukkan password di dalam form password, sistem dapat menyembunyikan setiap huruf yang diketikkan. Sehingga, pengguna akan merasa aman ketika mengetik passwordnya di tempat umum sekalipun.

- 3. Antarmuka Pengguna (User interface)

Perangkat lunak front-end: HTML dan CSS
Perangkat lunak back-end: JavaScript
    
- 4. Antarmuka perangkat keras (Hardware interface)
 
Komputer atau ponsel cerdas dengan browser yang sudah terinstal di dalamnya

**Rencana Pengembangan Sistem**

Enkripsi password pada aplikasi autentikasi halaman website.
Pengecekan panjang password yang harus memiliki minimal 6 karakter.

Alur Kerja Aplikasi
==
### Proses Komunikasi Aplikasi dengan Komputer
Berkomunikasi dengan komputer tidak dapat menggunakan bahasa manusia, melainkan menggunakan bahasa pemrograman. Instruksi yang kita berikan akan diproses oleh CPU (Central Processing Unit) yang ada pada komputer. Lalu, bagaimana kode yang kita buat bisa dipahami oleh komputer?
Ketika seorang pengembang software menulis dan menjalankan sebuah kode, maka terjadilah proses konversi. Proses tersebut dibedakan menjadi dua yaitu Compile dan Interpret.

Compiler merupakan sebuah aplikasi yang bertugas untuk mengonversi source code yang kita buat menjadi bahasa mesin. Apabila terdapat penulisan kode yang salah, maka compiler akan mengirimkan pesan eror kepada kita dan harus diperbaiki. Jika tidak, maka akan menghasilkan berkas executable, contohnya seperti .exe. 

Metode interpret sama dengan compile yaitu mengonversi bahasa pemrograman supaya bisa dipahami oleh mesin dengan bantuan interpreter. Perbedaannya adalah ketika kita menggunakan compiler, source code akan dikonversi menjadi machine code (membuat berkas executable) sebelum aplikasi tersebut dijalankan. Sedangkan interpreter mengonversi source code menjadi machine code secara langsung ketika aplikasi dijalankan. 

Perbedaan nya pada tabel berikut
![Screenshot 2023-08-17 083029](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/1b281608-7d01-4b51-972f-b897b0d7fc79)

### Konsep Jalannya Program secara Sekuensial
Suatu program pada dasarnya adalah kumpulan instruksi yang memiliki tujuan tertentu. Kumpulan instruksi tersebut perlu kita susun secara berurutan agar berjalan dengan semestinya. Penyusunan instruksi tersebut adalah tugas seorang pengembang software.

Kenapa harus secara berurutan? Karena ketika suatu program dieksekusi, sistem akan membaca kumpulan instruksinya dari atas ke bawah satu per satu. Sehingga, ketika ada instruksi yang posisinya tidak pas, program menjadi eror.

Penyelesaian Masalah Menggunakan Cara Berpikir Komputasional
==
Setiap orang pasti pernah melakukan kesalahan dalam menulis kode. Oleh karena itu mungkin Anda bertanya, “Bagaimana kalau program yang kita buat mengalami eror?” Sebagai seorang pengembang software kita harus belajar dari pengalaman untuk mengasah kemampuan pemecahan masalah.

Ketika pengembang software membuat aplikasi, mereka akan mulai berpikir secara terstruktur layaknya sebuah komputer mengeksekusi setiap perintah. Begitu pula saat memecahkan sebuah permasalahan. Mereka akan mencari solusi dari permasalahan secara terstruktur dan seefisien mungkin. Berikut teknik penyelesaian masalah menggunakan cara berpikir komputasional.

### Memecah permasalahan yang besar menjadi bagian kecil (decomposition)
Contoh sederhananya yaitu membuat nasi goreng. Membuat nasi goreng bukanlah satu perintah yang langsung bisa dikerjakan. Di dalamnya harus kita pecah terlebih dahulu supaya lebih mudah dikerjakan, seperti mengetahui:

Apa saja alat yang dibutuhkan?
Apa saja bahan-bahannya?
Berapa lama waktu yang dibutuhkan?
Bagaimana cara memasaknya?

### Pelajari pola dari setiap permasalahan (pattern recognition)
Untuk dapat memperjelas maksud dari Pattern Recognition, mari kita ilustrasikan dengan menggambar kucing.

Bayangkan Anda mendapat tugas untuk menggambar 3 jenis kucing, antara lain kucing persia, anggora, dan kucing oranye. Kita harus mempelajari persamaan dan perbedaan setiap jenis kucing. Persamaan yang dapat diambil misalnya ketiga jenis kucing tersebut memiliki bulu, berkaki empat, bermata dua, dan mempunyai ekor. Persamaan tersebut merupakan ciri-ciri kucing secara umum yang ada di ketiga jenis kucing tersebut. Sedangkan perbedaannya bisa dilihat dari segi warna, panjang kaki, dan kelebatan bulu. 

Setelah mengetahui perbedaan dan persamaan tersebut, kita dapat mulai menggambarkan setiap jenis kucing dengan cepat dan tepat.

### Mengabstraksikn suatu permasalahan (abstraction)
Abstraksi identik dengan penyaringan dan pengumpulan data yang bersifat umum. 

Selain itu, abstraksi juga mengesampingkan detail data yang bersifat khusus supaya lebih berkonsentrasi terhadap apa yang akan dilakukan. Misalnya saat naik sepeda motor, kita tidak perlu tahu komponen mana yang membuatnya berjalan. Kita cukup mengetahui cara menyalakan mesin dengan menekan tombol starter yang ada di setir atau pedal kaki.

Masih ingat ilustrasi menggambar kucing? Dalam proses abstraksi, kita mulai dengan mencatat karakteristik yang dimiliki kucing secara umum dan khusus.

Karakteristik umum kucing antara lain: Memiliki kaki, bulu, ekor, mata, bisa mengeong, makan ikan.
Karakteristik khusus kucing antara lain: Memiliki kaki pendek, ekor panjang, mata biru, mengeong dengan keras, makan ikan asin.

Untuk menggambar kucing secara umum, kita memang perlu mengetahui kalau kucing pasti memiliki kaki, ekor, bulu, dan mata. Namun, kita tidak perlu tahu apa warna bulu atau matanya, ekornya panjang atau pendek, dan seterusnya.

### Susun langkh menggunakan algoritma (algorithm)
Algoritma merupakan sekumpulan alur instruksi yang berurutan untuk menyelesaikan permasalahan. Sehingga kita akan merangkai sekumpulan instruksi menjadi urutan yang terstruktur, logis, dan mudah dipahami. 

Ketika kita memberikan algoritma yang tidak cukup efisien terhadap komputer, maka hasilnya juga pasti tidak seperti yang diharapkan.

Ibaratkan proses penyusunan algoritma ini dengan alur kegiatan yang harus dilakukan untuk berangkat ke sekolah. Mulai dari bangun tidur, mandi, menggosok gigi, sarapan, hingga tiba di sekolah. Setiap kegiatan juga memiliki detailnya sendiri-sendiri, misal mandi pukul 6, sarapan nasi goreng, pergi ke sekolah naik sepeda, dll.

### Mengevaluasi solusi yang didapatkan (evaluation)
Salah satu penyebab kegagalan adalah kurangnya proses evaluasi yang tepat. Kita telah melalui proses pemecahan masalah menjadi bagian kecil hingga merangkainya menjadi sebuah solusi.

Proses terakhir yang dapat kita lakukan adalah melakukan evaluasi terhadap solusi yang telah kita dapatkan. Proses ini perlu dilakukan sebelum melangkah ke permasalahan atau tugas yang baru. 

Bayangkan ketika membuat sebuah program yang menurut Anda sudah tidak ada eror. Karena Anda tidak mengevaluasi, seorang pengguna menemukan sebuah kendala yang membuat program tersebut terasa lambat. Ketika Anda memeriksanya kembali ternyata ada beberapa kode yang harusnya perlu ditambahkan untuk membuat programnya berjalan lancar. Seandainya Anda telah melakukan evaluasi sebelumnya, maka pengguna tidak akan merasakan aplikasinya berjalan lambat.

Studi Kasus Penyelesaian Masalah yang Terjadi Pada Sebuah Aplikasi
==
Studi Kasus ini bertujuan untuk memperdalam materi tentang Penyelesaian Masalah Menggunakan Cara Berpikir Komputasional. Sehingga kita dapat menyelesaikan masalah yang terjadi pada sebuah aplikasi dengan menerapkan teknik-teknik seperti berikut: 

### Tahapan Proses
Pada studi kasus kali ini kita menyelesaikan sebuah permasalahan dengan kondisi sebagai berikut:

“Sebuah perusahan menerima laporan 5 orang pengguna yang tidak bisa melakukan proses login pada halaman website kita.”

**Memecah permasalahan yang besar menjadi bagian kecil (decomposition).**

Pengguna hanya memasukkan email saja
Pengguna lupa password yang dimilikinya
Pengguna belum memasukkan email dan password yang sesuai
Sistem yang mengatur proses login bermasalah
Sistem form isian username dan email bermasalah

*Dari studi kasus di atas, Anda juga dapat memecahnya kembali menjadi bagian kecil tentang apa saja yang harus Anda lakukan nantinya, seperti berikut:*

Mencoba dengan email dan password yang sesuai.
Memeriksa teknis kode yang menangani proses login tersebut.
Memeriksa laporan eror yang sudah dicatat sistem jika ada pengguna yang mengalami gagal login.
Memeriksa email yang khusus digunakan perusahaan untuk menampung laporan eror yang dikirimkan pengguna.

**Pelajari pola dari setiap permasalahan (pattern recognition).**

Dari penjabaran kasus yang sudah kita pecah-pecah pada tahap sebelumnya, kita dapat mempelajari pola dari pengguna salah satunya dengan memeriksa laporan eror yang pasti tercatat pada sistem. Mengapa kita memilih untuk mempelajari pola dari laporan eror yang dicatat sistem?

Anda sebagai seorang pengembang software mungkin berasumsi bahwa bisa saja pengguna yang mengalami eror tidak melaporkan ke email perusahaan.

Lalu, mengapa Anda tidak langsung memeriksa teknis kode yang menangani proses login tersebut? Anda juga berasumsi tidak perlu sampai memeriksa teknis kode karena sebelum rilis, website tersebut sudah diperiksa oleh tim penguji.

Sehingga, Anda memilih untuk memeriksa laporan eror pada sistem karena semua kesalahan yang terjadi dalam website pasti tercatat di sana.

Kemudian dari sana Anda mendapati 5 orang pengguna tersebut sudah memasukkan email dan password yang menurut mereka  benar serta sudah menekan tombol login, tetapi masih tidak bisa masuk.

**Mengabstraksikan suatu permasalahan (abstraction).**

Setelah kita mempelajari pola berdasarkan data valid dari laporan eror yang dicatat sistem, 5 pengguna sudah memasukkan email dan password dengan benar. Sehingga, Anda perlu mengabstraksikan untuk mendapatkan gagasan umum tentang permasalahan yang terjadi.

Sehingga, untuk memperoleh gagasan umum, kita perlu memecahnya menjadi karakteristik umum dan khusus.

Karakteristik umum: kesalahan terjadi pada sisi pengguna, kesalahan terjadi pada sistem autentikasi.

Karakteristik khusus: kesalahan pengisian pada email dan/atau password, kesalahan logika alur autentikasi pada sistem.
Dalam proses login kita tahu bahwa kesalahan dapat terjadi dari sisi pengguna atau sistem. Namun, tidak semua pengguna salah dalam mengisi email dan/atau password. Serta tidak semua kesalahan yang terjadi di sistem ada pada logika alur autentikasinya.

Sehingga dapat disimpulkan jika seseorang melakukan proses login dengan email dan password yang sudah benar, tetapi masih belum bisa masuk, maka ada kesalahan pada proses autentikasinya. Seperti yang kita tahu bahwa proses autentikasi adalah hal teknis yang harus diperbaiki pada kode aplikasinya.

**Susun langkah menggunakan algoritma (algorithm).**

Berikut ini urutan algoritma permasalahan dari sudut pandang pengembang software:

Buka kode aplikasi website secara keseluruhan.
Cari kode yang mengarah pada fitur autentikasi.
Periksa dan perbaiki alur logika program autentikasi yang bermasalah
Setelah diperbaiki, lakukan pengujian beberapa kali dengan berbagai skenario untuk memastikan proses login sudah aman.
Perbarui versi dari website kita dengan menyertakan catatan perbaikan apa yang sudah dilakukan.
Selain itu, Anda juga harus menempatkan diri Anda sebagai pengguna dengan cara menguji kembali sistem yang sudah Anda perbaiki, algoritmanya sebagai berikut:

Buka halaman login dari website
Isi email dan password dengan benar
Ketika tombol tombol login, pastikan sistem sudah berfungsi dengan normal.
Pastikan juga ketika berhasil login, diarahkan ke halaman utama.

**Mengevaluasi solusi yang didapatkan (evaluation).**

Setelah itu Anda dapat mengevaluasi beberapa hal, misalnya seperti berikut:

Apakah masih ada pengguna yang masih mengalami eror login?
Apakah setelah perbaikan sistem ada feedback positif dari pengguna terkait permasalahan eror login yang ia alami?
Apakah ada kendala lain yang terjadi pasca perbaikan sistem tersebut?

Pengenalan Flowchart
==
Flowchart atau bisa disebut dengan diagram alur merupakan bentuk penggambaran dengan pendekatan visual terkait langkah-langkah dan keputusan untuk melakukan sebuah proses, alur kerja, ataupun algoritma. Setiap langkah dalam urutan proses akan digambarkan dalam bentuk diagram dan dihubungkan dengan garis atau arah panah.

Berikut adalah beberapa simbol yang sering dijumpai pada flowchart:
![Screenshot 2023-08-17 085327](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/2f1159f0-8d62-4a1b-bb76-e918f1e3aab2)

### Jenis-Jenis Flowchart yang Umum Digunakan
flowchart juga bisa digunakan dalam berbagai kondisi misalnya seperti mendeskripsikan alur kerja organisasi, bisnis, hubungan antar departemen dalam sebuah perusahaan, bahkan tentang kegiatan sehari-hari.

**Process Flowchart (Diagram Proses)**
![Screenshot 2023-08-17 085708](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/fd515b75-0ab1-4faf-8bed-97b19a7eb37a)

Diagram Proses pertama kali dikemukakan oleh Frank Gilbreth, seorang Insinyur Industri Amerika pada tahun 1920. Beberapa dekade berikutnya, diagram proses ini sering digunakan dalam bidang teknik industri dan bahkan di sektor bisnis. 

Beberapa keunggulan dari diagram proses antara lain:

Memantau dan menganalisis dengan lebih lengkap mulai dari proses produksi hingga memeriksa kendala yang terjadi.
Meningkatkan efisiensi dalam proses produksi.
Meningkatkan komunikasi dan kolaborasi antar tim.

**Workflow Flowchart (Diagram Alur Kerja)**
![Screenshot 2023-08-17 085901](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/cc7bf725-9b44-473e-bf47-c1aa2871884c)

Sebuah perusahaan pasti memiliki banyak tugas dan orang yang terlibat di dalamnya. Masing-masing orang memiliki tugas yang berbeda, bahkan bisa saja merangkap beberapa tugas sekaligus. Agar lebih mudah mengetahui alur kerja dalam perusahaan maupun bisnis, kita dapat menggunakan diagram alur kerja. Selain untuk menggambarkan tugas dari individu atau kelompok, diagram alur kerja ini juga dapat digunakan untuk sebuah proses. Sehingga diagram ini merupakan cara terbaik untuk merancang, mengubah, dan menganalisis sebuah proses bisnis.

**Program Flowchart (Diagram Program)**
![Screenshot 2023-08-17 090029](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/088203ae-c237-4ab0-b92c-cc13620f91e4)

Seperti namanya, diagram program dapat membantu kita untuk menggambarkan algoritma ke dalam bentuk visual. Sehingga waktu yang dibutuhkan untuk proses pemahaman akan lebih cepat dan efisien. Selain itu juga terdapat beberapa manfaat yang didapat dari diagram program berikut:

Membantu pengembang software menemukan dan menganalisis bug dari sebuah alur proses, bahkan sebelum menjalankan aplikasinya.
Berperan sebagai  cetak biru (blueprint) saat menganalisis dan mengembangkan program, sehingga penulisan kode lebih efisien.
Meningkatkan efisiensi programmer dalam proses maintenance sebuah program.
Memudahkan komunikasi logika dari sebuah sistem kepada semua anggota tim lainnya, bahkan yang bukan pengembang software sekalipun.

Studi Kasus Penggunaan Flowchart untuk Aplikasi Penjualan
==
 Di sini Anda akan membuat flowchart dari aplikasi penjualan barang. Berikut tahapan-tahapan dari aplikasi yang ingin kita buat:

1. Masuk tampilan awal aplikasi.
2. Jika pengguna sudah memiliki akun, ia bisa masuk ke halaman beranda aplikasi.
3. Namun, jika pengguna belum mempunyai akun, ia harus mendaftar terlebih dahulu sebelum bisa masuk ke halaman beranda aplikasi.
4. Pengguna dapat mencari barang berdasarkan kategori
5. Jika barangnya sudah ketemu, pengguna dapat memilih dan melakukan pembelian dari barang tersebut.
6. Jika barang yang diinginkan tidak ketemu, pengguna dapat mencarinya berdasarkan nama barang terlebih dahulu sebelum dapat melakukan pembelian barang.
7. Ketika melakukan proses pembelian otomatis data sudah tersimpan di database sistem aplikasi.
8. Kemudian pengguna melakukan proses pembayaran.
9. Selesai.

Berikut merupakan flowchartnya

![Screenshot 2023-08-17 091055](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/94f72e38-1db5-47db-af65-d25c92b98599)

Tips Sikap Kerja dalam Kolaborasi Perencanaan Aplikasi dengan Tim
==
Kebanyakan perusahaan saat ini menerapkan pola kolaborasi tim untuk menyelesaikan proyek. Apalagi ketika kita bergerak di perusahaan berbasis IT atau pemrograman.

Tidak terkecuali dalam sebuah proses perencanaan aplikasi. Berdiskusi dengan pihak-pihak yang berkepentingan menjadi hal krusial. 

### Efektifkan Komunikasi
Mulailah dari menjadi pendengar yang baik. Jika ada anggota tim yang menyampaikan pendapat, maka dengarkan dengan baik dan jangan diabaikan. Sampaikan apresiasi terhadap pendapat tersebut dengan jujur jika memang bagus. Sebaliknya, jika dari pendapat tersebut ada yang perlu dikritik, maka sampaikanlah umpan balik atau kritik yang membangun, tidak menyinggung, dan berorientasi untuk kemajuan bersama.

### Membangun Kepercayaan dalam Tim
Kepercayaan berarti Anda mengandalkan orang lain untuk melakukan sebuah pekerjaan. Anda percaya pada integritas dan kemampuan orang tersebut walaupun ada kemungkinan risiko yang bisa kembali ke diri Anda sendiri. Begitu pula sebaliknya, jika orang lain mengandalkan Anda untuk membantu pekerjaannya, maka orang tersebut percaya pada kemampuan dan integritas Anda.

### Berikan Semangat Anda
Kita telah mengetahui pentingnya membangun kepercayaan dalam sebuah proses kolaborasi. Selain itu, kita juga harus selalu menunjukkan semangat dan bergairah dalam mengerjakan tugas. Semangat dapat memengaruhi mental dari tim. Maka dari itu, ketika ada anggota tim yang sedang terlihat lesu karena kehilangan semangat atau bahkan hampir putus asa, kita harus menyemangatinya.

### Utamakan Diskusi
Jika rekan tim Anda berusaha menyelesaikan sendiri-sendiri, ajaklah mereka berdiskusi untuk mencapai tujuan bersama. Utarakan pendapat Anda sesuai dengan tujuan yang ingin dicapai. Anda juga harus bisa mendengarkan dan menghargai pendapat orang lain ketika mereka mengemukakan idenya.

### Hindari Sikap Tidak Tanggap (slow response)
Kondisi tidak tanggap atau slow response ini biasanya sering ditemui ketika bekerja secara jarak jauh. Satu-satunya cara untuk saling berkomunikasi adalah dengan mengirim pesan atau melakukan video call. Sehingga anggota tim yang bekerja secara jarak jauh harus selalu standby apabila sewaktu-waktu ada hal penting yang harus segera dikerjakan.

### Menentukan Prioritas
* Hal pertama yang bisa Anda lakukan adalah mengumpulkan semua todo yang Anda dalam satu tempat. Tidak perlu pedulikan urutan todo-nya pada langkah ini.
* Identifikasi todo yang urgent, alias harus segera diselesaikan. Di langkah ini, Anda perlu memindahkan todo yang sifatnya urgent ke urutan yang lebih atas. Urgent di sini bisa berarti kerjaan yang harus diselesaikan segera.
* Setelah itu, perhitungkan nilai tiap todo. Hitung dampak setiap todo jika telah terselesaikan. 
* Urutkan todo berdasarkan usaha yang harus dikeluarkan. Para expert di bidang produktivitas mengatakan, selesaikanlah dulu kerjaan yang membutuhkan usaha paling besar. Setelah itu, baru selesaikan todo yang membutuhkan usaha kecil.
* Lalu, Anda harus fleksibel dan mudah beradaptasi. Bersiaplah dengan segala perubahan, karena kita tidak tahu akan ada masalah apa yang muncul dan akan mempengaruhi pekerjaan kita.
* Selepas itu, hapus todo yang bisa dihapus. Ini adalah langkah terakhir dalam menentukan prioritas, coretlah todo yang memang bukan prioritas.

Latihan Kuis

1.
![Screenshot 2023-08-17 092606](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/1ca8396e-392b-4e06-aa48-fb3211ebd1e2)

2. 
![Screenshot 2023-08-17 092744](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/a6ac2d9b-b737-4ae3-87ef-e78d56ea33c3)

3.
![Screenshot 2023-08-17 092812](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/5d8c421f-eff5-44bd-8dff-8a37ac7c27ae)

4.
![Screenshot 2023-08-17 092843](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/52ee3cd5-e7af-46c7-bb9e-1e58928680f6)

5.
![Screenshot 2023-08-17 092908](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/dd75f313-2827-4427-9107-096ef1045019)

Materi 4 Mengerti Konsep Dasar Pemrograman (Modul 2)
==
### Pengenalan Konsep Dasar Pemrograman
Berikut adalah pokok pembahasan yang akan diulas dalam materi konsep dasar pemrograman:
* Pertama kita akan belajar sintaksis. Di sana kita akan belajar case sensitive, menulis statement, whitespace, dan keyword. Selain itu Anda juga akan mengenal kode semu (pseudocode) dan cara membuatnya.
* Setelah itu Anda akan mempelajari elemen-elemen dasar yang ada di dalam kode pemrograman, seperti variabel, operator, dan tipe data.
* Kemudian Anda juga akan belajar logika pemrograman, seperti logika perbandingan dan perulangan.
* Terakhir, Anda akan dikenalkan dengan bahasa pemrograman JavaScript serta penerapan konsep dasar pemrograman dalam bahasa tersebut.

### Pengenalan Sintaksis dan Case Sensitive
**Case sensitive vs Non case sensitive**

Hampir semua bahasa pemrograman saat ini bersifat case sensitive. Artinya, setiap kapitalisasi huruf pada sebuah kode akan berpengaruh.

![Screenshot 2023-08-17 093656](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/b153397b-7cbe-4199-93b1-2524bda98c4c)

Misalnya jika kita memiliki variabel bernama Kucing yang diawali dengan huruf besar dan variabel kucing yang diawali dengan huruf kecil, apakah dalam kasus case sensitive kedua variabel tersebut sama? Tentu tidak, karena keduanya merupakan entitas yang berbeda. Sedangkan kode yang bersifat Non Case Sensitive berarti sebaliknya. Ia tidak terpengaruh dengan penulisan huruf besar atau kecil.

Maksud dari si pengembang software Python adalah mengetik statement dengan kondisi True, tetapi ia menggunakan huruf “t” kecil sebagai awalan. Lalu ketika dijalankan, interpreter atau compiler mengirimkan pesan Error. Pesan tersebut mengatakan bahwa si kompiler atau interpreter tidak mengerti dengan kata “true” pada baris ke-8. Dari sini bisa disimpulkan bahwa kita bermaksud membuat nilai boolean “true” dengan awalan kecil, akan tetapi keyword yang digunakan pada Python menggunakan “True” dengan awalan besar, sehingga tetap saja error.

Lalu apakah ada bahasa pemrograman yang non case sensitive? Tentu ada, contohnya seperti Pascal dan Fortran. Mereka tidak memedulikan penulisan huruf besar dan kecil.

Semua penerapan case sensitive tersebut memiliki aturannya masing-masing di setiap bahasa pemrograman. Sama halnya ketika kita menulis kalimat dalam bahasa Indonesia atau bahasa lainnya. Misalnya seperti berikut:

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/fc331b10-9e78-4c43-8205-1cce38cf8d59)

Kenapa kalimat tersebut semuanya tidak menggunakan huruf kecil? Toh, juga artinya sama, kan?

Penulisan harus seperti itu karena mengikuti kaidah PUEBI (Pedoman Penulisan Ejaan Bahasa Indonesia). Berdasarkan kalimat tersebut, aturan penggunaan huruf kapital dalam PUEBI antara lain huruf di awal kalimat, nama hari, penyebutan kata “Anda”, dan nama kota.

Dengan kalimat yang sama, kita ubah menjadi bahasa Inggris seperti berikut.

![Screenshot 2023-08-17 094511](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/6ed1c7cb-b70b-44a2-b7de-27a46f2c4ea3)

Kalimat ini memiliki makna yang sama tetapi jika dilihat terdapat perbedaan huruf kapital. Menurut aturan bahasa Inggris, yang memakai huruf kapital antara lain, huruf pertama di awal kalimat, nama hari, penyebutan kata “saya”, dan nama kota. 

Perbedaannya dengan bahasa Indonesia adalah pada kata “Anda” dan “saya”. Dalam bahasa Indonesia “Anda” menggunakan kapital walau di tengah kalimat dan “saya” menggunakan huruf kecil. Sedangkan dalam bahasa Inggris justru “Saya” menggunakan huruf besar walau di tengah kalimat dan “Anda” menggunakan huruf kecil.

Untuk lebih detail lagi kita coba terjemahkan kalimat tersebut ke dalam bahasa Jerman sebagai berikut.

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/bf3eb292-5b4f-49a6-85f8-eeede5943644)

Berdasarkan kalimat tersebut, aturan penulisan kapital pada bahasa Jerman antara lain, huruf di awal kalimat yang yang kebetulan juga adalah nama hari (Sonntag = Minggu). Selain itu, ada juga penyebutan kata Anda (Sie), nama benda (kereta = Zug), dan nama kota. 

Untuk penyebutan kata saya dalam bahasa Jerman menggunakan huruf, sedangkan Anda (Sie) menggunakan huruf besar. Untuk kata “Anda” dan “saya” aturannya mirip dengan bahasa Indonesia, tetapi tidak sama dengan bahasa Inggris. 

Berikut beberapa highlight tentang huruf kapital berdasarkan beberapa contoh bahasa.

![Screenshot 2023-08-17 094640](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/1cf354e9-46d8-4a17-a93a-7d4919fb1c5a)

### Statement dan Whitespace
**Menulis Statement**

Aplikasi terdiri dari kumpulan instruksi tunggal yang berkaitan satu sama lain. Misalnya dalam buku resep masakan kita sering menemui instruksi, “Panaskan air hingga 200 derajat celcius.”, “Diamkan adonan di dalam kulkas selama 3 jam.”, dan banyak lagi instruksi lainnya. Dalam aturan menulis sebuah kode pemrograman, instruksi di atas sering disebut dengan istilah statement. 

![Screenshot 2023-08-17 095627](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/5da10983-dd11-4b46-8a4e-eeacbb08b9ef)

Contoh di atas merupakan statement sederhana yang berhubungan dengan dunia pemrograman. Sebuah statement harus jelas dan lengkap. Maksud dari lengkap adalah menjelaskan tentang hasil yang ingin dicapai. Jika statement yang ditulis tidak lengkap, maka aplikasi tidak akan berjalan lancar.

Contoh statement dalam kehidupan sehari-hari bisa kita ibaratkan seperti orang yang bertanya sebuah alamat. “Mas, alamat rumahnya Pak Lurah di mana ya?”

Si penanya ingin mendapatkan hasil berupa menemukan rumah Pak Lurah. Jadi Anda harus menjawab dengan lengkap dan detail supaya si penanya tidak tersesat. Seandainya Anda menjawab seperti ini.

![Screenshot 2023-08-17 095730](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/8ee7b88d-db4e-4813-a7c0-baf993142fb2)

Nah, jika Anda tidak menjelaskan secara lengkap dengan detail sejauh mana kira-kira harus berjalan, rumahnya warna apa, di samping rumahnya ada apa, maka kemungkinan akan terlewati rumahnya dan tidak sampai. Namun, jika Anda menjawab seperti berikut.

![Screenshot 2023-08-17 095816](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/731590c7-baf8-4120-90a1-b92a5e3b7a7c)

Dengan penjelasan yang lengkap seperti jawaban kedua maka kemungkinan si penanya tersesat, sangat kecil. Sebabnya, penjelasannya sudah jelas, runut, dan lengkap. Jika hal ini lantas dihubungkan dengan statement dalam pemrograman, mari perhatikan di tabel berikut.

![Screenshot 2023-08-17 095856](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/70ea1693-85fe-4b68-a3d0-0909b2510c3c)

Kita ambil salah satu contoh statement yaitu Add 10 to Health Point. Berarti kita ingin menambahkan nilai 10 pada Health Point yang ada saat ini. Jika dituliskan dalam bahasa pemrograman tertentu misalnya Swift atau Python, maka penulisannya menjadi healthPoint = healthPoint + 10. Contoh penulisan dengan sintaks di atas merupakan yang paling umum. Jika dibaca artinya, health point atau HP saat ini sama dengan health point + 10. Sehingga ketika statement tersebut berhasil dijalankan maka health point sudah bertambah 10 dari health point awal.

### Mengakhiri Statement
Jika statement Add 10 to Health dibuat dalam bahasa C, C++, atau Java, maka sintaksnya sama seperti sebelumnya tetapi ada tambahan semicolon di belakangnya. Sehingga menjadi healthPoint = healthPoint + 10;

Semicolon atau titik koma merupakan ciri khas dari sintaks bahasa pemrograman seperti C, C++, Java, dan beberapa bahasa pemrograman lainnya. Fungsi dari semicolon adalah untuk mengakhiri sebuah statement. Statement tidak selalu pendek. Ada juga yang panjang dan harus dipisahkan menjadi beberapa baris supaya mudah dibaca. Perhatikan pseudocode di bawah ini.

![Screenshot 2023-08-17 100106](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/503a2b1d-da69-461b-9aea-cbf93ad49484)

Nah, setiap statement pada contoh ilustrasi di atas akan diakhiri dengan semicolon. Jika statement terlalu panjang maka bisa dipisah ke baris selanjutnya supaya mudah dibaca. Namun, semicolon tetap harus berada di akhir dari statement tersebut seperti contoh statement empat di atas. 

### Whitespace dalam Pemgrograman
 Whitespace saat kita mengetik kode biasanya berupa spasi atau tab untuk indentasi. Selain itu kita juga menggunakan enter dan ada baris kosong untuk membedakan setiap kode yang ada. Sebenarnya seberapa berpengaruh whitespace pada kode yang kita tulis?

 ![Screenshot 2023-08-17 100310](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/fc1f513d-2347-4855-a6a0-dcb72011474c)

Perhatikan contoh kode menggunakan bahasa pemrograman php di atas. Kira-kira jika diubah menjadi seperti di bawah ini apakah akan mempengaruhi hasil akhirnya?

![Screenshot 2023-08-17 100345](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/98cd2bc8-a880-46b7-a1a9-269f0e6f5664)

Kebanyakan bahasa pemrograman tidak terlalu memperhatikan whitespace. Sehingga jika kita menambahkan tiga sampai lima baris kosong atau menambahkan spasi sebanyak mungkin juga tidak masalah. Namun, whitespace juga penting untuk formatting kode kita supaya lebih mudah dipahami. Mungkin jika kode yang dibuat hanya beberapa baris dan menggunakan whitespace yang tidak beraturan masih bisa dipahami. Tetapi jika kode yang dibuat kompleks sampai ratusan baris atau lebih, maka harus memperhatikan whitespace supaya setiap baris kodenya bisa dipahami. 

Penggunaan indentasi juga berkaitan dalam kurung kurawal dalam sebuah kode. Biasanya sering kita temui dalam sintaks bahasa C, C++, Swift, dan lainnya. Perhatikan contoh kode di bawah ini.

![Screenshot 2023-08-17 100518](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/8a130579-f13f-4164-a28d-9a546951624b)

### Whitespace pada Python
Terlepas dari itu semua, ada bahasa pemrograman yang sangat sensitif dengan whitespace. Jadi tidak semua bahasa pemrograman cuek dengan whitespace, ya. Bahasa pemrograman yang dimaksud adalah Python.

Keyword dan Pseudocode
==
### Keywords dalam Bahasa Pemrograman

**Keyword dalam C**

![Screenshot 2023-08-17 101322](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/9fb46f69-24a7-4d57-8a70-62662761779c)


**Keyword dalam Java**

![Screenshot 2023-08-17 101404](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/8870c81a-4167-4767-aca3-8f27c49968c1)

**Keyword dalam Python**

![Screenshot 2023-08-17 101444](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/a9b1bc6e-3a66-451d-89ea-b22bc12c5e57)

**Keyword dalam JavaScript**

![Screenshot 2023-08-17 101537](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/8df1842a-75da-4a57-bd23-d635933fff3f)

Keyword merupakan kata kunci yang telah disediakan oleh sebuah bahasa pemrograman. Keyword tidak bisa berdiri sendiri guna membuat sebuah program yang dapat dijalankan. Kita harus mengkombinasikan keyword dengan logika pemrograman yang ada dengan bahasa yang kita pahami. Untuk memperjelas maksud dari pernyataan di atas, perhatikan ilustrasi kode di bawah ini. 

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/c77631a6-f95b-44ed-be24-3bb42cb7de6d)

Menurut ilustrasi kode di atas, if merupakan keyword. Sedangkan currentScore dan highScore merupakan variabel yang kita definisikan sendiri di awal. Maka dari itu keyword tidak bisa berdiri sendiri dan perlu dikombinasikan dengan variabel dengan nama yang bisa kita pahami.

Contoh lainnya, coba perhatikan penggalan kode bahasa C di bawah ini.

![Screenshot 2023-08-17 101849](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/f1e7ba7a-0a14-47c1-8a09-5b52e2733cc0)

Perhatikan bagian yang dicetak tebal pada kode di atas. Terdapat sebuah keyword yang tertulis pada nama variabel. Kita tahu int dan float merupakan keyword dari bahasa C. Sehingga kita tidak bisa memberi nama variabel yang sama dengan nama keyword. Misal kita ingin membuat sebuah variabel int if atau string for, maka kompiler akan mengirimkan pesan eror karena Anda menggunakan keyword sebagai nama variabel. Begitu pula pada kode di atas. Seharusnya int diikuti nama variabel selain keyword. Misal int angka, int number, int nomor, dan lainnya.

Menulis Pseudocode
==
Pseudocode merupakan istilah dalam pemrograman untuk menuliskan sebuah sintaks, statement, algoritma, dan lainnya dalam bahasa yang bisa dipahami oleh manusia. Sederhananya, pseudocode adalah bentuk representasi dari kode kita nantinya dengan versi yang human readable, bukan computer readable.

Pada materi sebelumnya kita telah mencontohkan statement sebagai berikut.

![Screenshot 2023-08-17 102204](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/7b2d0d9e-9e66-4c91-8deb-0fcb19139859)

Contoh di atas sudah termasuk pseudocode dari statement yang berbeda. Kita bisa memahaminya tetapi tidak dengan komputer.

### Mengapa memulai dari Pseudocode?

Berikut ini adalah beberapa keuntungan jika kita menggunakan pseudocode sebelum memulai menulis kode.

- Meningkatkan pemahaman dari pendekatan apa pun. Hal ini merupakan cara terbaik untuk menjelaskan apa yang kita inginkan dan melatih logika dalam pemrograman.
- Menjelaskan secara detail tentang apa yang harus dilakukan setiap baris dari sebuah kode yang akan dibuat nantinya, sehingga membuat fase penulisan kode lebih mudah bagi seorang pengembang software. 
- Bertindak seperti penghubung antara program yang akan kita buat dengan logika pemrograman. Selain itu juga digunakan sebagai dokumentasi kasar, sehingga kode program yang dibuat dapat mudah dipahami orang lain yang ingin mengembangkannya.

### Latihan Menulis Pseudocode

Sebagai contoh kita ingin membuat aplikasi login. Ketika pengguna memasukkan email dan password yang sesuai dengan data yang tersimpan di database, ia dapat masuk ke halaman utama. Jika tidak sesuai, maka pengguna dipersilakan untuk memasukkan email dan password kembali.

1. Kita definisikan dulu tujuan programnya. Dalam contoh ini berarti kita akan membuat aplikasi login yang berasal dari input email dan password pengguna.

2. Kemudian sistem akan melakukan pengecekan, jika email dan password yang dimasukkan pengguna sesuai dengan data yang tersimpan di database, pengguna dapat masuk ke halaman utama. Namun, jika email dan username yang dimasukkan pengguna tidak sesuai, maka sistem menampilkan pesan login gagal, silakan ulangi kembali.

3. Selanjutnya kita akan menyusun pseudocode-nya. Sekarang kita akan membuat pseudocode dari alur aplikasi login tadi. Kita bisa menggunakan Notepad untuk menuliskan ini. Ingat bahwa kita tidak memerlukan editor khusus dalam menuliskan pseudocode karena tidak ada sintaksis yang kita perlukan dalam menuliskan ini.

Contoh pseudocode dari Studikasus diatas

![Screenshot 2023-08-17 103228](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/fc7d8e60-fa48-48e7-9332-c00a9e0dbbeb)

### Variabel
Dalam sebuah program, tentunya banyak sekali data individual, seperti nama user, skor permainan, alamat email, tanggal sebuah acara, kondisi pengguna sudah login atau belum, dan lain sebagainya.

Program dapat terisi data tersebut karena telah dibuatkan variabel yang menampung setiap data. Misal variabel username untuk menampung nama pengguna, variabel playerScore untuk menampung skor pemain, dan seterusnya.

Terdapat tiga hal yang harus diperhatikan dalam sebuah variabel yaitu nama, nilai, dan tipe dari variabel. Untuk memperjelas maksud dari ketiga hal tersebut, perhatikan ilustrasi skor permainan berikut.

![Screenshot 2023-08-17 103801](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/9fbfbb60-676b-4758-82ab-f903eae73502)

Gambar tersebut menunjukkan skornya adalah 100. Jika dijabarkan, Score merupakan nama variabel dan 100 adalah nilai yang disematkan dalam variabel tersebut. Dalam satu nama variabel, nilainya dapat diubah, misalnya angka 100 pada variabel tersebut diganti menjadi 3, 10, 90, 150, ataupun yang lainnya. Anggap saja variabel sebagai wadah yang sudah kita beri nama dan di dalamnya dapat diisi nilai apa pun. Lalu, tahukah Anda apa tipe dari variabel tersebut?

Tipe adalah jenis data yang akan kita taruh dalam variabel tersebut. Tipe dari variabel biasanya berupa angka, teks, kondisi ya atau tidak (true/false), atau apa pun itu. 

Bayangkan Anda memiliki sebuah wadah dan mengisinya dengan baju, tas, bahkan pemanggang roti sekalipun. Jenis barang yang kita letakkan di dalam wadah itulah yang disebut tipe. Misal, Anda mempunyai wadah besar bernama lemari. Kemudian Anda menginginkan lemari tersebut untuk menyimpan baju, selain baju tidak boleh dimasukkan ke sana. Anda bisa menyimpan baju berapa pun jumlahnya. Bagaimana jika Anda ingin meletakkan mesin penanak nasi di dalam lemari tersebut? 

Andai lemari tersebut bisa berbicara mungkin akan berkata, “Aku hanya boleh menyimpan baju, selain baju tidak diperbolehkan.” Lalu bagaimana jika kita tetap ingin menyimpan penanak nasi tersebut? Ada dua cara yang dapat dilakukan. Cara pertama adalah menyiapkan wadah baru lainnya yang khusus untuk menyimpan penanak nasi dan barang-barang elektronik dapur yang sejenis. 

Namun, jika ingin penanak nasi harus disimpan di lemari, maka kita bisa menggunakan cara kedua yaitu mengeluarkan semua baju dari lemari dan mengosongkannya. Secara tidak langsung Anda sudah mengubah lemari tersebut yang semula untuk menyimpan barang bertipe baju dengan tipe penanak nasi. Sehingga, lemari tersebut kini hanya bisa digunakan untuk menyimpan penanak nasi, dan bukan baju lagi.

### Mendeklarasikan dan Menggabungkan Variabel dengan Operator

Pada banyak bahasa pemrograman kita harus mendeklarasikan variabel terlebih dahulu sebelum bisa digunakan. Maksud dari deklarasi variabel adalah membuat statement pada source code untuk mengatakan bahwa “Saya ingin membuat variabel baru.” Anda juga perlu menjelaskan tentang apa nama variabel dan tipe data dari variabel tersebut. Setelah mendeklarasikan variabel tersebut, barulah Anda bisa memberi nilai ataupun mengubah nilainya. Berikut contoh sintaks dari beberapa bahasa pemrograman untuk mendeklarasikan sebuah variabel.

**Contoh Sintaks Bahasa C**

![Screenshot 2023-08-17 104412](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/7efe4140-715f-498e-9af0-02370be445a1)

Terlihat deklarasi variabelnya tertulis int score;. Dalam bentuk kode, integer biasanya dituliskan dengan int. Int merupakan tipe data dari variabel score. Sedangkan score merupakan nama variabelnya.

**Contoh Sintaks Bahasa Swift**

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/2cf93e2c-45c5-4b56-8704-ec1e4fe00918)

dalam bahasa Swift tertulis var score: Int. var merupakan keyword ketika kita membuat variabel. Score merupakan nama variabel dan int merupakan tipe data dari variabel tersebut. Sehingga setiap variabel score hanya menampung data bertipe integer.

**Contoh Sintaks Bahasa JavaScript**

![Screenshot 2023-08-17 104606](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/47d44bd0-36bc-4ffb-8392-9dea0477da0c)

pada bahasa JavaScript untuk mendeklarasikan variabel score hanya tertulis var score; tanpa imbuhan tipe data. Sehingga variabel score dalam bahasa JavaScript bisa kita isi sebagai angka, string, ataupun lainnya bergantung pada apa yang kita butuhkan.

Jika dilihat dari kasus JavaScript di atas, maka kita harus bisa memilih nama variabel yang tepat sesuai kegunaannya supaya tidak bingung. Kita harus mematuhi aturan sintaks dan guideline style dari setiap bahasa pemrograman. Bukan berarti jika kita sudah mematuhi sintaks, kita menghiraukan guidelines style ya. Guideline style di sini adalah penamaan variabel supaya mudah dipahami kegunaannya. Untuk lebih memahami maksud dari guidelines style, perhatikan contoh variabel di bawah ini.

![Screenshot 2023-08-17 105746](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/6bd72972-0c53-4df7-b5da-91ecae2464f6)

**Jangan menulis nama variabel yang sama dengan keyword**

Sedikit mengingat kembali bahwa keyword merupakan kata kunci yang dipakai di bahasa pemrograman. Setiap bahasa memiliki keywordnya masing-masing. Sehingga Anda tidak boleh memberi nama variabel misalnya:

![Screenshot 2023-08-17 105915](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/33196cc0-5322-4dec-8adf-8694fd6c56b5)

Hal tersebut akan membuat eror dan variabel Anda tidak bisa terbaca. Lalu apa saja nama variabel yang diperbolehkan? Perhatikan tabel di bawah ini.

![Screenshot 2023-08-17 105955](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/c16532a7-7a42-4a0c-b2c8-26f3ebdf740b)

**Jangan mengawali nama variabel dengan angka**
Mengapa tidak boleh? Hal tersebut akan membuat kompiler akan membacanya sebagai nilai atau value bukan sebagai variabel. Perhatikan contoh di bawah ini.

![Screenshot 2023-08-17 110106](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/e63e5317-7cf4-47a0-abeb-568190261fe7)

Oleh karena itu, jika variabel kita memang mengharuskan ada angka di dalamnya, maka angka tersebut tidak boleh diletakkan di awal.

**Menggabungkan Variabel dan Operator**

Perhatikan contoh variabel yang sebelumnya pernah kita buat dengan ditambahkan statement yang berisi nilai dari sebuah variabel berikut ini.

![Screenshot 2023-08-17 110248](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/4703fe8e-b88e-425d-9e2c-e9de83ca2d27)

Pada hampir semua bahasa pemrograman ketika menginisialisasi variabel kita menggunakan nama variabel yang diikuti operator sama dengan (“=”) dan nilai yang ingin kita masukkan. Sama seperti contoh tabel di atas, kita melihat operator sama dengan pada score = 0;. Operator tersebut menyatakan perintah pada komputer untuk melakukan sesuatu atau bisa disebut assignment operator (operator penugasan). 

Dalam bahasa pemrograman, operator merupakan sebuah cara untuk menunjukkan tugas yang spesifik atau satu operasi saja, seperti penjumlahan, pengurangan, perkalian, dan lainnya. Perhatikan contoh operator berikut:

![Screenshot 2023-08-17 110359](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/170beafc-2eb9-4f5f-a3a3-8d6604bb0fa0)

Dalam contoh penggunaan di atas kita melihat bahwa operator membutuhkan dua nilai atau kita sebut operand yang berada di sebelah kanan dan kiri dari operator.

![Screenshot 2023-08-17 110444](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/fe56bf5d-655f-45d2-85d3-8478323dddaa)

![Screenshot 2023-08-17 110519](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/523ee6b9-db6c-4e9a-82ff-d06edf1511b4)

Setelah itu kita juga dapat menambahkan statement lain di bawahnya untuk mengubah nilai dari variabel score misalnya seperti berikut:

![Screenshot 2023-08-17 110610](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/b06c98d2-83d5-4b06-83b2-e780e51eb19f)

Tipe Data
==
Seperti yang kita ketahui, data memiliki tipe yang beragam. Dengan banyaknya jenis data maka kita harus mengetahui jenis data apa yang digunakan dan fungsinya. Untuk lebih jelasnya, mari kita ilustrasikan dengan contoh data sensus penduduk berikut ini.

![Screenshot 2023-08-17 111919](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/e9a711e6-6312-4376-85fa-cc8be6d54e53)

Pertama kita ambil contoh data umur. Pada sensus di atas tertulis umur dari Isabela adalah 30 tahun. Jika dilihat dari jenis datanya, kira-kira apa saja kemungkinan yang dapat masuk untuk mengisi data umur? Pastinya umur dituliskan dengan bilangan bulat dan bernilai positif. Karena tidak mungkin kita akan menemui seseorang dengan umur 30,6 atau -30 tahun. 

 Pada data alamat, ada campuran  data teks  dan angka di dalamnya. Terdapat data berupa angka karena biasanya digunakan untuk nomor rumah, nomor jalan, nomor gang, dsb. Maka dari itu alamat dapat menampung text dan angka secara bersamaan. Kemudian terdapat data yang berupa pertanyaan “Apakah memiliki NPWP?” Kemungkinan dari data tersebut cuma dua yaitu iya atau tidak. Sehingga tipenya hanya true atau false.

 ### Macam-Macam Tipe Data

 Setiap bahasa pemrograman memiliki tingkat detail yang berbeda-beda saat menentukan tipe data. Beberapa bahasa memperbolehkan atau fleksibel dalam tipe data dan ada juga yang harus ditulis spesifik dalam proses deklarasi variabel.Oke kita memiliki variabel yang bertipe angka tetapi tidak berhenti di sana. Kita harus menentukan apakah itu angka positif, negatif, bilangan bulat, atau desimal. Anda harus disiplin dalam menerapkan penulisan variabel untuk setiap penggunaannya. Semisal awalnya Anda mendefinisikan variabel tersebut untuk bilangan bulat. Kemudian di tengah-tengah perjalanan Anda ingin mengubahnya dalam bentuk desimal, maka Anda harus menuliskan kode lagi untuk memastikan tipe variabelnya sudah berubah.
 
**Numerik**
Variabel numerik adalah variabel yang erat hubungannya dengan angka. Terkadang ada nilai angka yang bulat seperti 3, 5, 7, 12, 20, dll. Ada juga yang berupa nilai angka desimal dengan koma di dalamnya seperti 4,5 ; 5,4 ; 10,3 ; 15, 6 ; dsb. 

 Berikut contoh penerapan dari tipe data integer dan float.

 ![Screenshot 2023-08-17 112408](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/2fa0d9ec-b63f-4da8-a35e-d61b1b53c42e)

 Jika Anda tahu bahwa data yang akan Anda tulis adalah bilangan bulat, seperti usia, jumlah halaman buku, jumlah penduduk di suatu wilayah, jumlah lantai dalam gedung, dan lainnya, maka Anda bisa menggunakan tipe data integer (int).

 jika kita ingin membuat data yang berupa bilangan desimal atau pecahan seperti suhu tubuh seseorang, berat badan, nilai IPK, dan semacamnya. Di sini kita perlu tipe data float. 

 **Boolean**
 Tipe data ini lebih sederhana dari lainnya karena hanya memiliki dua nilai yaitu true atau false. Contoh penerapan boolean dalam beberapa bahasa pemrograman sebagai berikut.

 ![Screenshot 2023-08-17 112632](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/b23baa36-e5c8-400f-92e9-c3f9ca86de37)

 Dari contoh di atas jika dibaca kondisi bool-nya antara lain, 

- Apakah kondisi saat ini sedang bermain, true atau false?
- Apakah kondisinya sudah game over, true atau false?
- Apakah pengguna sudah login, true atau false?

Dalam beberapa bahasa pemrograman, penulisan bool berbeda-beda. Pada Swift menggunakan Bool sedangkan pada Java tertulis Boolean. Penulisan boolean menyesuaikan dan mengikuti keyword dari bahasa pemrograman yang sedang digunakan. Sedangkan nilai yang tertulis true atau false merupakan kondisi awal dari variabel tersebut.

**Teks atau Karakter**

Char hanya dapat menampung satu karakter saja, 

![Screenshot 2023-08-17 112848](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/cb1cd3ad-9d14-47bc-a196-0a6fb0169b3f)

sedangkan string adalah kumpulan karakter yang dirangkai secara berurutan. Untuk lebih jelasnya perhatikan ilustrasi berikut.

![Screenshot 2023-08-17 113013](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/55df14c0-0b66-45a5-b79f-ceb57ce08af6)

### Logika Perbandingan
**Logika Pemrograman Dasar**
Logika merupakan pemikiran yang digunakan untuk mencari solusi terhadap sebuah permasalahan dalam program. Sedangkan algoritma merupakan alur yang berurutan ketika menyelesaikan permasalahan tersebut. Sehingga permasalahan dapat terselesaikan sesuai alur yang semestinya.

**Logika Perbandingan Sederhana**
Logika ini digunakan untuk membandingkan dua hal yang mempunyai nilai. Jadi, jika sebelumnya kita sudah belajar tentang variabel dan tipe data, maka sudah pasti berhubungan dengan nilai yang melekat di dalamnya. Nilai inilah yang akan dibandingkan dengan nilai lain atau kondisi yang diinginkan. Sehingga pembahasan kali ini akan bermuara di sebuah keyword yang akan sering digunakan dalam pemrograman yaitu IF. Berikut ilustrasi penggunaan IF yang dituliskan dengan gaya bahasa C.

![Screenshot 2023-08-17 114219](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/a3a0df2b-50a1-4021-b851-3ef6e3ee9e3f)

Dalam contoh penggunaan IF di atas terdapat 3 bagian, yaitu keyword IF, kondisi, dan statement. Bacalah contoh di atas yang berarti, “Jika score lebih dari 500, maka mencetak kata Congratulations.” Sehingga tidak peduli berapapun skor yang diperoleh asalkan lebih dari 500 akan mengeksekusi statement di bawahnya yaitu mencetak kata Congratulations. Lalu, bagaimana jika skornya kurang dari 500? Jawabannya adalah tidak ada hasilnya. Sebabnya, tidak ada kondisi tambahan yang dapat menampung skor di bawah 500.

**Mengecek Kondisi Pada IF**
Selain menggunakan tanda > seperti contoh sebelumnya, kita juga dapat menggunakan operator lainnya seperti < , >=, dan lainnya. Lalu bagaimana jika kondisinya sama dengan suatu hal yang kita tentukan? Pada bagian ini biasanya sering terjadi kesalahan yang umum dialami ketika awal belajar pemrograman. Misalnya ada kondisi sebagai berikut, 

* Jika score sama dengan 0
* Jika nama pengguna sama dengan Budi
* Kira-kira bagaimanakah cara penulisan kondisi tersebut? Perhatikan ilustrasi berikut ini.

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/da9d17dd-d362-46d3-a3db-5990d0c537d1)

Jika penulisan kondisinya seperti di atas, maka kondisi tersebut tidak bisa dijalankan karena operator ”(=)” / “sama dengan” hanya untuk memasukkan nilai saja, bukan untuk cek kondisi dari sebuah nilai. Sehingga kita harus menggunakan simbol sama dengan ganda (“==”) untuk mengecek kondisi sebuah nilai. Sedangkan untuk kondisi tidak sama dengan menggunakan simbol tanda seru dan sama dengan (“!=”). Untuk lebih jelasnya perhatikan ilustrasi di bawah ini.

![Screenshot 2023-08-17 114608](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/0785d9c3-6b78-4b1b-aa09-da24ddedabb3)

**Blok Kode**
 selanjutnya kita dapat menulis apa yang harus dilakukan ketika kondisi tersebut terpenuhi. Maka kita dapat membuat statement yang sudah kita kelompokkan dalam suatu blok kode. Beberapa bahasa pemrograman yang bergaya C seperti Swift, Java, dan lainnya menggunakan simbol kurung kurawal. (“{. . .}”)

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/f6960d39-a3f7-40a1-8eb3-e29aea39038a)

Jadi berapapun statement yang dimulai setelah awal blok kode dan sebelum akhir blok kode, maka akan dijalankan ketika kondisinya sudah terpenuhi. Sehingga setiap ada kurung kurawal pembuka harus diakhiri dengan kurung kurawal penutup untuk menandai statement yang dijalankan.

**IF/Else**
Sebelumnya kita memiliki kondisi jika skor lebih dari 500, maka cetak tulisan Congratulations. Jika tidak memenuhi kondisi tersebut maka tidak ada statement apapun yang dijalankan . Lalu bagaimana caranya jika kita ingin memberikan informasi kalau score kurang dari 500 akan memunculkan tulisan Try again? Jawabannya adalah kita harus menambahkan else setelah akhir blok kode. Lebih detailnya sebagai berikut.

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/2237ac19-7962-4d85-bafc-8611a66cd07b)

Dari ilustrasi kode di atas kita memiliki dua blok kode. Blok kode pertama dijalankan ketika kondisi true. Sedangkan blok kode kedua dijalankan ketika kondisi false. Cara membacanya adalah jika kondisi skor lebih dari 500 maka kondisinya adalah true lantas mengimplementasikan statement Congratulations tanpa menjalankan kondisi yang ada di bawahnya.

### Logika Perbandingan Kompleks
**Kondisi AND dan OR**
AND menggunakan tanda dobel ampersand (“&&”). Sedangkan untuk OR dituliskan dengan tanda (“||”).  Mengapa dobel? Sama halnya seperti kasus pengecekan kondisi sama dengan (“==”), AND dan OR pun juga sama karena digunakan untuk mengecek sebuah nilai. Untuk memperjelas kondisi OR dan AND, perhatikan ilustrasi berikut.

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/a5533afb-315b-42b6-8431-5a1f7f7cb624)

Logika Perulangan
==
Dalam pemrograman, kita harus menghindari menulis kode yang sama berulang kali. Hal tersebut dilakukan supaya proses menulis kode lebih efektif dan efisien. Contoh sederhana juga ada di dunia nyata, lho. Ketika kita dihukum untuk menulis
"Saya tidak akan mengulangi lagi" di papan selama 100 kali.

**While**
While merupakan jenis perulangan yang statement di dalamnya akan dijalankan terus menerus selama kondisinya memenuhi syarat atau true. Ilustrasi while seperti berikut:

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/3580cd0a-6dd3-452b-8427-f3a0085e99f0)

Pada saat kondisi while bernilai true karena variabel myNumber kurang dari 500, maka statement dalam while akan terus menerus dijalankan selama kondisinya tidak berubah. Jika tidak dibuat kode yang berisi kondisi untuk menghentikan perulangan tersebut, maka statement akan terus dijalankan selamanya atau bisa disebut dengan infinite loop.

Perhatikan contoh kode dengan gaya penulisan C berikut. 

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/3f32d566-1370-4a08-96c6-ad567dcc7819)

Dalam program menghitung nilai counter di atas, awalnya adalah  deklarasi variabel bertipe integer bernilai 0. Kemudian terdapat kondisi perulangan menggunakan while di mana selama variabel counter kurang dari 5, maka akan menjalankan statement di dalamnya. Statement di dalamnya adalah menghitung dan mencetak nilai counter

**For**
 Tahukah Anda apa bedanya dengan while? While digunakan ketika kita tidak mengetahui berapa kali perulangan akan berjalan. Yang terpenting adalah selama kondisinya memenuhi syarat maka perulangan akan terus berjalan. Sedangkan dalam For, nilai perulangan, jumlah perulangan, dan akhiran yang biasanya berupa statement. Untuk lebih jelasnya perhatikan uraian berikut.

 ![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/af8c9ee7-85e9-46ce-b478-d74d62ac8407)

Terdapat 3 bagian dalam kondisi For yaitu inisialisasi awal perulangan, kondisi, statement dari kondisi perulangan. Sehingga terlihat lebih ringkas jika dibandingkan dengan while. Perhatikan contoh kode dengan gaya penulisan C berikut. 

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/3cc437e3-d382-4419-9802-2e290dccfd4a)

Dalam program menghitung nilai counter di atas tertulis kondisi perulangan for yang terdapat 3 bagian di dalamnya dan dipisahkan dengan titik koma. 

- Bagian pertama adalah inisialisasi variabel counter yang bernilai 0. 
- Kemudian terdapat kondisi counter < 5 yang menandakan perulangan variabel counter tidak sampai 5. 
- Setelah itu bagian ketiga adalah akhiran yang berupa statement.

**Menggabungkan IF dengan salah satu perulangan**

Kita telah belajar penggunaan IF, for, dan while. Apakah setiap logika tersebut bisa digunakan secara bersamaan? Jawabannya adalah bisa. Sebagai contoh kita akan menggabungkan kondisi while dengan IF.

Kondisi yang ingin kita buat adalah kita membuat program menghitung counter dengan menggunakan while. Jika nilai counter yang awalnya bernilai 0 saat proses while kurang dari sama dengan 10, maka akan mencetak nilai tersebut di layar. Tetapi yang tercetak hanya nilai genap saja. Kira-kira bagaimanakah caranya?

Pertama kita pecah terlebih dahulu kasus di atas menjadi bagian-bagian kecil yaitu.

* Variabel counter memiliki nilai awal 0
* Kondisi while berjalan selama nilai counter kurang dari sama dengan 10
* Ketika berada dalam while juga dilakukan pengecekan nilai counter, jika habis dibagi 2 maka nilai counter tersebut akan tercetak. Sehingga jika tidak habis dibagi 2, maka nilai counter tidak ditampilkan.

Dari proses pemecahan masalah di atas, maka kita akan membuatnya dalam sebuah kode. Seperti biasa kita akan menggunakan gaya penulisan bahasa C.

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/5e80faef-ff6f-4549-958c-7e62a8f796e1)

Lalu bagaimana jika menggunakan gabungan for dan IF dengan contoh kasus yang sama seperti di atas. Maka contoh konsep kodenya akan terlihat seperti berikut.

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/9767da1b-09ab-41b4-8f5b-1d4ee3e1e0f7)

Pengenalan JavaScript
==
bahasa JavaScript merupakan bahasa yang umum digunakan untuk membuat suatu website supaya terlihat dinamis. Pernah melihat sebuah website yang menerapkan animasi ketika masuk ke sebuah artikel? Atau sebuah website yang interaktif yang menunjukkan slide foto serta saran penulisan di kolom pencarian? Hal tersebut dilakukan oleh JavaScript.

Contoh lainnya adalah dalam penggunaan sosial media, misalnya Instagram. Tentunya Anda akan melihat beranda Instagram Anda selalu diperbarui dengan memperlihatkan posting terbaru. Pembaruan beranda tersebut biasanya secara otomatis ketika masuk ke aplikasinya atau mengusap layar Anda ke bawah. Hal tersebut juga merupakan contoh sederhana dari penerapan JavaScript yang sering kita temui.

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/979dca6e-29ae-4dfa-8356-e345a884beda)

### Variabel dalam JavaScript
Variabel merupakan sebuah wadah yang nantinya akan diisi oleh sebuah nilai. Variabel bisa kita anggap seperti sebuah gelas. Di dalam gelas, Anda bisa mengisikan air, jus, kopi, teh, atau minuman lainnya. Gelas merupakan sebuah variabel. Air, jus, kopi, atau teh merupakan nilai dari variabel. Itulah konsep dasar variabel yang telah kita pelajari pada sub-modul sebelumnya.

Lalu bagaimana implementasinya di JavaScript? Variabel di JavaScript dapat dibuat dengan menggunakan keyword let dan const. Mari kita coba buat sebuah variabel di JavaScript.

Variabel di JavaScript dapat dibuat menggunakan keyword let dan const 
yang dimana let digunakan untuk variabel yang bersifat teks atau String dan const digunakan untuk variabel yang bersifat number atau Boolean

Contoh menggunakan keyword let

//untuk membuat variabel dengan cara "let"

let name = "Dicoding";

//untuk mencetak variabel "name" diatas 

console.log(name);

Contoh melakukan perubahan nama variabel

//untuk membuat variabel dengan cara "let"

let name = "Dicoding";

//untuk merubah nama variabel

name = "Dicoding Academy";

//untuk mencetak variabel "name" diatas 

console.log(name);

Contoh menggunakan keyword const

//untuk membuat variabel dengan cara "let"

const score = 1000;

//untuk mencetak variabel "name" diatas 

console.log(score);

pada variabel const kita tidak bisa melakukan perubahan nilai variabel jika melakukan persis seperti yang kita lakukan dengan menggunakan let maka akan terjadi error

Ada hal lain yang penting untuk Anda ketahui ketika membuat sebuah nama variabel.

- Hindari penamaan variabel dengan istilah umum contohnya data. Penamaan data tidak menjelaskan apa pun. Nama tersebut akan membuat Anda bingung kelak. Sebaiknya gunakan nama yang dapat mendeskripsikan nilai dari variabel itu sendiri.
- Variabel di JavaScript hanya dapat dimulai dengan huruf atau tanda underscore. Anda tidak bisa membuat variabel dengan awalan angka atau menggunakan simbol selain underscore.
- Nama variabel tidak boleh mengandung spasi. Jika nama variabel memiliki lebih dari dua kata, maka gunakan format camelCase seperti ini:
firstName, lastName, catName.
- Tidak boleh mengandung karakter spesial (!.,/\+*= dan lainnya).

### Tipe Data dalam JavaScript
**Undefined**

Tipe data ini terbentuk ketika sebuah variabel tidak memiliki nilai. Artinya, ketika kita mendeklarasikan variabel tanpa menginisialisasikan nilainya, variabel tersebut menjadi undefined.

Contoh menggunakan Undefined

let score;

console.log(typeof(score));

**Numbers**

Nilai dari tipe data number adalah angka. Variabel bertipe data number dituliskan seperti angka pada umumnya:

Contoh menggunakan Numbers

let playerScore = 100;

Jika angka tersebut merupakan sebuah bilangan desimal, maka kita bisa gunakan tanda titik pada pecahan bilangannya.

let age = 24;

console.log(typeof(age));
 
let height = 165.3;

console.log(typeof(height));

Pada tipe data number, kita juga dapat melakukan perhitungan aritmatika. seperti contoh dibawah : 

![image](https://github.com/auliarochullah/PembelajaranDicoding/assets/126051321/d9f454f4-4b71-4f6c-b392-f8913c71e231)

**Increment dan Decrement**

Pada operator aritmatika juga terdapat operator increment (++) dan decrement (--). Operator increment dan decrement digunakan untuk menambahkan atau mengurangi nilai 1 pada nilai variabel yang ada sekarang.

Operator ini dapat dituliskan sebelum atau sesudah variabel, tetapi hal tersebut bukan berarti sama. Berikut ketentuannya:

- Jika dituliskan setelah variabel (x++), expression akan menghasilkan nilai variabel sebelum ditingkatkan nilainya.
- Jika dituliskan sebelum variabel (++x), expression akan menghasilkan nilai variabel setelah ditingkatkan nilainya.
Untuk lebih jelasnya, berikut adalah contoh kode penerapan operator tersebut, perhatikan hasil yang didapat.

let postfix = 5;

console.log("Hasil dari postfix++ adalah ", postfix++);

console.log("Sehingga, nilai dari postfix saat ini adalah ", postfix);
 
let prefix = 5;

console.log("Hasil dari ++prefix adalah ", ++prefix);

console.log("Sehingga, nilai dari prefix saat ini adalah ", prefix);

**Strings**

Tipe data selanjutnya adalah string yang merupakan sebuah teks. Untuk menetapkan nilai sebagai string pada variabel gunakan tanda petik satu (‘) atau petik dua (“) di antara teksnya. Contohnya:

let name = "Dicoding";

console.log(typeof(name));

Tidak ada perbedaan antara menggunakan petik satu atau petik dua. Anda dapat menggunakan tanda petik secara bergantian, khususnya jika Anda memiliki teks yang mengandung tanda petik.

const question = '"What do you think of JavaScript?" he asked';
 
console.log(question)
 
/* output: "What do you think of JavaScript?" he asked */

Namun, bagaimana jika sebuah teks memiliki kedua tanda petik tersebut? Misalnya kalimat berikut, “I think it's great!” i answered.

Solusinya, gunakan backslash(\) untuk mengurangi ambiguitas dalam tanda petik. Mekanisme ini juga dikenal dengan nama escape string. Sehingga kode di atas akan menjadi seperti berikut:

const answer = '"I think it\'s great!" i answered';
 
console.log(answer);

Backslash sebelum tanda petik akan memberitahukan interpreter bahwa itu hanyalah tanda petik dan tidak boleh ditafsirkan sebagai pembatas string. Selain tanda petik, backslash juga berguna untuk mengabaikan simbol lain yang menimbulkan ambigu di dalam string, contohnya seperti backslash itu sendiri.

console.log("Windows path: C:\\Program Files\\MyProject");

**Boolean**

Boolean hanya memiliki dua nilai, yaitu true atau false. Tipe data ini menjadi kunci utama dalam penentuan logika. Kita akan banyak menggunakannya nanti dalam materi if/else statement. Untuk menetapkan nilai boolean pada variabel, gunakan keyword true atau false seperti di bawah ini.

let x = true;

let y = false;
 
console.log(typeof(x))

console.log(typeof(y))

Kita juga bisa menggunakan operator komparasi seperti lebih dari (>) atau kurang dari (<). Contohnya:

const a = 10;

const b = 12;
 
let isGreater = a > b;

let isLess = a < b;
 
console.log(isGreater);

console.log(isLess);

**Null**

Tipe berikutnya adalah null. Null biasa digunakan sebagai nilai sementara pada variabel, tapi sebenarnya nilai tersebut “tidak ada”.

Terkadang kita perlu membuat sebuah variabel, namun kita belum memerlukan nilai apa-apa dan tidak ingin terikat oleh tipe data apa pun. 

let someLaterData = null;

console.log(someLaterData);

### Fungsi dalam JavaScript
**terdapat beberapa fungsi pada JavaScript** yaitu :

console.log();

function greeting()

Namun, apa sebenarnya function itu? Bagaimana ia bisa bekerja? Mari kita lihat contoh kodenya.

function greeting() {

   console.log("Selamat sore!");
}
 
greeting(); 

Kode di atas merupakan sebuah fungsi di JavaScript, fungsi ini berguna untuk menampilkan pesan Selamat sore pada konsol.

Anda sudah mengenal console.log. console.log merupakan sebuah fungsi yang berguna untuk menampilkan data pada konsol. Data yang ditampilkan merupakan data yang kita berikan melalui sebuah parameter.

Jika kita memberikan nilai 5, maka console.log akan menampilkan 5. Bila kita memberikan data teks selamat malam, maka ia akan mencetak selamat malam.

console.log(5); // 5

console.log("Selamat Malam"); // Selamat Malam

Nah, bagaimana dengan fungsi yang sudah kita buat sebelumnya? Bisakah fungsi yang kita buat menampilkan data secara dinamis seperti fungsi console.log?

Jawabannya, tidak! Karena fungsi yang kita buat sebelumnya, tidak memiliki atau menampung sebuah parameter. Sehingga tidak ada cara untuk memberikan sebuah nilai pada fungsi tersebut.

function greeting() {

  console.log("Selamat sore!");
}
 
greeting("Selamat malam!"); // Selamat sore!

greeting(5); // Selamat sore!

Bila kita coba panggil layaknya seperti memanggil fungsi console.log, maka hasilnya tetap akan mencetak Selamat sore.

Lantas, bagaimana caranya agar fungsi greeting dapat menampilkan data yang dinamis?

Jawabannya, tentu dengan menambahkan sebuah parameter fungsi. Kemudian kita cetak teks di console.log berdasarkan data yang diberikan pada fungsi.

function greeting(greet) {

  console.log("Selamat " + greet + "!");
  
}
 
greeting('malam'); // Selamat malam!

greeting('pagi'); // Selamat pagi!

Dengan begini, ketika fungsi dipanggil dengan teks “malam”, ia akan mencetak teks “Selamat Malam”. Begitu juga bila kita memanggil dengan memberikan nilai “pagi”, maka ia akan mencetak teks “Selamat Pagi”.

Kita juga bisa memberikan lebih dari satu parameter fungsi bila memang dibutuhkan. Misalkan, pada fungsi greeting, selain parameter greet, kita bisa menambahkan parameter name agar fungsi dapat menyapa nama kita.

function greeting(greet, name) {

  console.log("Selamat " + greet + ", " + name + "!");
  
}
 
greeting("sore", "Dimas"); // Selamat sore, Dimas!

greeting("pagi", "Yasmin"); // Selamat pagi, Yasmin!

Kini, bila saya memanggil fungsi greeting dengan nilai sore dan dimas. Maka fungsi greeting akan mengembalikan nilai, “Selamat sore, Dimas”.

Misal, saat ini fungsi greeting dapat menerima dua parameter, yang pertama greet dan yang kedua name.

function greeting(greet, name = "Bapak/Ibu") {

  console.log("Selamat " + greet + ", " + name + "!");
  
}
 
greeting("sore", "Dimas"); // Selamat sore, Dimas!

greeting("pagi"); // Selamat pagi, Bapak/Ibu!

**TIPS DALAM MEMBUAT FUNGSI DI JAVAASCRIPT**
* Hindari membuat parameter yang banyak
Memberikan batasan pada jumlah parameter fungsi merupakan hal yang sangat penting. Fungsi dengan parameter yang terlalu banyak akan sulit untuk diuji ataupun digunakan. Karena kita perlu banyak sekali nilai untuk menggunakan sebuah fungsi.

* Melakukan satu hal
Ketika membuat fungsi yang melakukan lebih dari satu hal, cobalah untuk memecah fungsinya. Hingga tiap fungsi benar-benar melakukan satu hal. Tentu ini juga membuat kode pada fungsi jauh lebih bersih dan mudah dibaca.

* Nama fungsi harus merepresentasikan tujuannya
Tak hanya variabel, kita juga perlu memperhatikan penamaan pada fungsi. Pastikan nama yang diberikan merepresentasi tujuan atau tugas dari fungsi tersebut. Hal ini juga bisa membantu developer lain mudah untuk mengetahui tujuan dari fungsi yang Anda buat.

* Buatlah fungsi untuk menghindari duplikasi kode
Bila Anda merasa sering menuliskan kode yang berulang-ulang. Sebaiknya perhatikan kode tersebut. Karena kode yang berulang menjadi kandidat kuat untuk dibuatkan sebuah fungsi.

### Logika Perbandingan dalam JavaScript
**perbandingan pada IF/Else**

let myScore = 100;
let computerScore = 90;
 
if(myScore > computerScore){
    console.log("Selamat, Anda menang");
}
else{
    console.log("Anda kalah");
}








































