# Studi Kasus Menganalisis Kebutuhan Aplikasi dari Sisi Pengguna
**Contoh studi kasus yang akan kita buat kali ini adalah User Requirement Specification (URS) terkait proses login dan logout.**
Kali ini kita akan menggunakan teknik interview untuk mengumpulkan informasi terkait kebutuhan aplikasi yang ditujukan untuk end-user atau calon pengguna nantinya. Salah satu contoh pertanyaan yang dapat diajukan adalah sebagai berikut:

"Apa yang sebenarnya diharapkan pengguna ketika melakukan proses login atau logout?"

Setelah Anda menanyakan hal tersebut, bersiaplah untuk mencatat jawaban dari pengguna. Anggap saja Anda memperoleh beberapa jawaban seperti berikut:

Di halaman login seharusnya pengguna bisa melakukan proses login dengan memasukkan email dan password.
Ketika pengguna melakukan proses logout, ia akan secara otomatis pindah ke halaman login.

Apa itu Spesifikasi Teknis Aplikasi
==
Spesifikasi Teknis Aplikasi, yakni dokumen yang menyimpan informasi detail mengenai fungsionalitas dari sistem/aplikasi, servis, dan juga limitasi-limitasinya. Berbeda dengan URS di mana tidak boleh menggunakan jargon teknis, dokumen Spesifikasi Teknis justru akan banyak jargon-jargon yang digunakan. Ini memang karena kebutuhannya sudah mengarah ke sistemnya.

Cara Menentukan Spesifikasi Teknis Aplikasi
==
Sebelumnya kita sudah mengetahui ada beragam solusi yang ditawarkan untuk memenuhi kebutuhan pengguna. Misalnya ada kebutuhan pengguna untuk mengirimkan pesan ke orang lain. Nah, solusi yang ditawarkan bermacam-macam, bisa dengan menggunakan email, atau aplikasi messenger seperti whatsapp.
Banyaknya alternatif atau solusi dalam hal pengembangan software tentunya malah memberikan potensi munculnya ide-ide bagus, yang memiliki dampak baik pada aplikasi.

Berangkat dari permasalahan ide tersebut maka ada beberapa prinsip pada spesifikasi teknis yang bisa kita terapkan:
*  Clear (jelas)
*  Unambiguous (tidak ambigu)
*  Mudah dipahami
*  Complete (lengkap)
*  Consistent (konsisten)
<br>
Dari beberapa prinsip tersebut memang mengarah kepada kejelasan implementasi fiturnya. Ini memanglah penting, karena ada beberapa stakeholder yang perlu memahami dokumen spesifikasi teknis aplikasi.
Dari berbagai macam stakeholder memang memiliki kebutuhannya masing-masing, oleh karena itu kita perlu tahu kebutuhan berdasarkan sisi pandangnya:

**Developer**
Dari sisi developer tentunya yang diperlukan ada kedetailan dan kejelasan spesifikasi. Karena merekalah yang akan mengimplementasinya ke dalam aplikasi.

**Client/User**
Dari sisi client meskipun spesifikasi teknis lebih mengarah ke teknis akan tetapi mereka berharap tetap bisa dimengerti. Dalam artian istilah teknis yang dipakai harus bisa dibuat semudah mungkin untuk dimengerti.

**Legal**
Karena spesifikasi teknis ini bisa menjadi kontrak, maka perlu memasukkan acceptance criteria dengan jelas juga. Acceptance criteria adalah klausul kriteria yang berisi apakah suatu fitur sudah berjalan dengan baik. Jika aplikasi yang dibuat lulus semua acceptance criteria maka seharusnya tidak ada masalah dari sisi kontrak/legal.

Masih sama seperti materi sebelumnya di user requirement mari kita implementasikan Spesifikasi Teknis Aplikasi dengan menggunakan studi kasus proses login dan logout.

Pertama yaitu proses login, kita bisa membuat spesifikasi seperti berikut:
Untuk melakukan proses login, pengguna haruslah mengisi kolom email dan juga password terlebih dahulu.
Kolom email harus memiliki pengecekan kesesuaian format email.
Kolom password harus mampu menutupi (masking) nilai yang dimasukkan oleh pengguna dengan mengubahnya menjadi asterisk (*).
Ketika user melakukan proses login tetapi email atau passwordnya tidak cocok maka harus muncul informasi bahwa email atau passwordnya salah dan perbaiki terlebih dahulu.

Kedua yaitu proses logout, kita bisa membuat spesifikasi seperti berikut:
Tombol logout haruslah terlihat jelas.
Ketika tombol logout ditekan maka halamannya akan berpindah ke halaman login.
Materi yang telah kita bahas tadi merupakan analisis spesifikasi teknis aplikasi untuk proses login dan logout. Tentu saja, spesifikasi teknis untuk satu aplikasi akan berbeda dengan aplikasi lainnya. Anda bisa menyesuaikan spesifikasi teknis untuk aplikasi yang akan dikembangkan nanti sesuai dengan kebutuhan. 

Di internet, @ dibaca at sign, atau address sign adalah simbol untuk alamat email yang memisahkan nama pengguna dengan alamat internet pengguna.

Tips Sikap Kerja dalam Meneliti, Menganalisis, dan Mengevaluasi Kebutuhan Aplikasi
==
Pertama yang diperlukan adalah komunikasi yang baik dengan pihak yang memiliki kebutuhan aplikasi. Ingat, sebaik apa pun aplikasi jika tidak sesuai dengan kebutuhan pengguna maka tidak akan ada artinya. Oleh karena itu, sewaktu melakukan interaksi dengan pengguna pastikan tidak asal-asalan ya. 

Lakukan riset terlebih dahulu sebelum berinteraksi dengan pengguna. Apakah interview yang dilakukan akan menjadi efektif, atau justru kita salah sasaran. Pahami terlebih dahulu siapa penggunanya atau audien. 

Sewaktu berinteraksi pun, pastikan Anda mencatat dengan rapi (terstruktur) daftar kebutuhan aplikasi sesuai kebutuhan pengguna. Sebab ketika komunikasi dengan pengguna berjalan dengan baik, namun Anda justru tidak mencatatnya maka tidak akan ada hasilnya. Jangan hanya mengandalkan ingatan saja ya. Namun tulislah agar apa yang disampaikan pengguna menjadi lebih melekat.

Latihan Kuis
==
Manakah yang tidak termasuk teknik requirement gathering?
<br>
- A  Interview
- B  User Stories
- C  Retrospectives <
- D  Prototyping

Kapan User Requirement Specification sebaiknya dibuat?
-  A  Setelah proses pengembangan
-  B  Sebelum proses pengembangan <
-  C  Saat proses pengembangan
-  D  Sebelum software dirilis

Apakah yang dimaksud dengan Prototyping?
-  A  Wawancara yang berupa tanya jawab
-  B  Membuat sampel program yang hanya memiliki fitur-fitur utamanya saja <
-  C  Menuliskan kebutuhan user sesuai dengan role dan keinginannya
-  D  Menyampaikan ide tanpa menggunakan kode

Apakah yang dimaksud dengan User Stories?
-  A  Wawancara yang berupa tanya jawab
-  B  Membuat sampel program yang hanya memiliki fitur-fitur utamanya saja
-  C  Menuliskan kebutuhan user sesuai dengan role dan keinginannya  <
-  D  Menyampaikan ide tanpa menggunakan kode

Apakah tujuan dari dibuatnya User Requirement Specification?
-  A  Supaya mendapatkan pemahaman yang sama akan kebutuhan user pada aplikasi <
-  B  Supaya mengetahui teknis aplikasi yang dibuat
-  C  Supaya mengetahui arsitektur aplikasi yang akan dibuat
-  D  Supaya mengetahui bagaimana cara menggunakan aplikasi
