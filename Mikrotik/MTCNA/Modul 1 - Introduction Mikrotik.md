## Perbedaan Mikrotik dan Router

Seringkali orang salah mengartikan Mikrotik dengan router. Keduanya memiliki perbedaan mendasar:

- **Mikrotik** adalah **perangkat lunak** (software) yang bertindak sebagai sistem operasi.
    
- **Router** adalah **perangkat keras** (hardware) yang berfungsi menghubungkan dua jaringan atau lebih.
    

Jadi, Mikrotik adalah sistem operasi yang ditanamkan pada router untuk menjalankan dan mengelola semua aktivitas jaringan.

---

## Sejarah Singkat Mikrotik

Mikrotik didirikan pada tahun 1996 di Latvia oleh dua orang, John Trully dan Arnis Riekstins. Mereka memulai dengan mengembangkan perangkat lunak router berbasis Linux. Tujuannya adalah menciptakan perangkat lunak router yang andal dan dapat digunakan di seluruh dunia, terutama bagi ISP (Internet Service Provider) yang ingin memberikan layanan internet nirkabel (wireless) kepada pelanggan. Seiring berjalannya waktu, mereka mulai memproduksi perangkat keras yang sesuai dengan perangkat lunak buatan mereka, sehingga kini Mikrotik dikenal sebagai produsen hardware dan software jaringan yang dominan, khususnya di negara-negara berkembang.

---

### Fungsi Utama Mikrotik

Mikrotik memiliki berbagai fungsi penting untuk mengelola jaringan secara efektif:

1. **Pengaturan Jaringan Lokal (LAN)**: Mengatur dan mengonfigurasi jaringan LAN, bahkan dengan spesifikasi perangkat keras yang rendah.
    
2. **Manajemen Pengguna dan Akses Internet**: Mengatur sistem otentikasi pengguna dan mengelola billing hotspot, yang memudahkan konfigurasi dan pembagian bandwidth pada jaringan.
    
3. **Pemblokiran Konten Negatif**: Memiliki fitur untuk memblokir situs yang dianggap ilegal atau mengandung konten yang tidak sesuai, seperti pornografi, untuk mendukung terciptanya "Internet Positif".
    
4. **Pembagian Bandwidth**: Memungkinkan Anda memisahkan dan mengatur bandwidth antara lalu lintas data internasional dan lokal, sehingga penggunaan internet bisa lebih efisien.
    
5. **Pembuatan Server PPPoE**: Bisa digunakan untuk membuat server PPPoE (Point-to-Point Protocol over Ethernet) untuk layanan internet.
    

---

## Jenis Mikrotik : 

### 1. RouterOS

Setelah mengetahui setiap fungsi yang dimiliki oleh mikrotik, berikutnya masuk pada topik  pembahasan mengenai jenis dari perangkat lunak berbasis sistem operasi jaringan ini yang  terbagi menjadi dua jenis utama.

RouterOS adalah **sistem operasi (OS)** yang dikembangkan oleh Mikrotik untuk menjalankan perangkat keras router mereka. 💻 Secara sederhana, RouterOS mengubah perangkat keras Mikrotik, seperti routerboard, menjadi sebuah router yang sangat kuat dan fleksibel.

RouterOS bukan sekadar program untuk menghubungkan internet, melainkan sebuah OS lengkap yang mengelola semua fungsi jaringan. Ini mirip seperti Windows atau macOS pada komputer, tapi dirancang khusus untuk tugas-tugas jaringan seperti **routing, firewall, manajemen bandwidth, dan VPN**.

### Fitur-fitur Utama RouterOS

Berikut adalah beberapa fitur penting yang membuat RouterOS begitu populer:

- **Routing**: Ini adalah fungsi inti. RouterOS bisa mengelola lalu lintas data antar jaringan yang berbeda. Ia mendukung berbagai protokol routing canggih seperti **OSPF, BGP, dan RIP**, yang biasanya hanya ditemukan pada perangkat jaringan kelas atas.
    
- **Firewall**: RouterOS memiliki **firewall** yang sangat kuat. Ini memungkinkan kamu untuk membuat aturan yang sangat spesifik untuk mengontrol lalu lintas data. Kamu bisa memblokir situs web tertentu, mencegah serangan dari luar, atau bahkan memprioritaskan jenis data tertentu.
    
- **Manajemen Bandwidth (QoS)**: Dengan fitur **Quality of Service (QoS)**, kamu bisa mengatur kecepatan internet untuk setiap pengguna atau perangkat. Contohnya, kamu bisa memprioritaskan bandwidth untuk streaming video 🎬 atau game online 🎮, sementara mengurangi bandwidth untuk unduhan file besar.
    
- **Wi-Fi (Wireless)**: RouterOS mendukung banyak mode Wi-Fi, termasuk sebagai **access point** (titik akses) atau **client** (klien). Kamu bisa mengelola banyak jaringan Wi-Fi, membuat hotspot, dan mengatur keamanan nirkabel.
    
- **VPN (Virtual Private Network)**: Ini memungkinkan kamu membuat koneksi aman ke jaringan lain melalui internet. Misalnya, seorang karyawan bisa mengakses jaringan kantor dari rumah seolah-olah ia berada di kantor. RouterOS mendukung berbagai jenis VPN seperti **PPTP, L2TP, dan OpenVPN**.
    
- **Alat Diagnostik**: Ada banyak alat bawaan untuk memantau dan memecahkan masalah jaringan, seperti **ping, traceroute, dan bandwidth test**. Ini sangat membantu saat kamu perlu mencari tahu mengapa koneksi internet lambat.
    



### Antarmuka Pengguna

Mikrotik RouterOS bisa dikelola dengan beberapa cara, yang membuatnya fleksibel untuk berbagai tingkat pengguna:

- **WinBox**: Ini adalah aplikasi GUI (Graphical User Interface) untuk Windows yang paling sering digunakan. 🖥️ Dengan WinBox, kamu bisa mengelola router dengan tampilan grafis yang mudah dipahami, tanpa perlu mengetik perintah.
    
- **WebFig**: Ini adalah antarmuka berbasis web. Kamu bisa mengaksesnya dari browser apa pun (Chrome, Firefox, dll.) dengan mengetik alamat IP router.
    
- **Command Line Interface (CLI)**: Untuk pengguna yang lebih ahli, RouterOS bisa dikelola melalui baris perintah. Ini sangat powerful dan sering digunakan untuk mengotomatisasi tugas atau melakukan konfigurasi yang sangat spesifik. Kamu bisa mengaksesnya melalui Telnet, SSH, atau konsol serial.
    



### Kenapa RouterOS Populer?

RouterOS menjadi pilihan banyak administrator jaringan dan penyedia layanan internet (ISP) karena beberapa alasan:

1. **Harga Terjangkau**: Perangkat Mikrotik dengan RouterOS menawarkan fitur setara dengan perangkat merek lain yang harganya jauh lebih mahal.
    
2. **Fleksibilitas dan Kekuatan**: Kamu bisa mengonfigurasi hampir semua hal yang berkaitan dengan jaringan. Ini membuatnya cocok untuk penggunaan di rumah, kantor kecil, hingga jaringan skala besar.
    
3. **Stabilitas**: RouterOS dikenal sangat stabil dan jarang mengalami _crash_, menjadikannya pilihan yang andal untuk jaringan 24/7.
    
4. **Komunitas Aktif**: Ada banyak dokumentasi, tutorial, dan forum komunitas yang bisa membantu kamu belajar dan memecahkan masalah. 🧑‍💻
    

Secara keseluruhan, **RouterOS adalah "otak" di balik perangkat Mikrotik** yang memberikannya kemampuan luar biasa untuk mengelola dan mengamankan jaringan dengan harga yang sangat bersaing.


### 2. RouterBoard

**RouterBOARD** adalah **perangkat keras (hardware)** yang diproduksi oleh perusahaan Mikrotik. Secara sederhana, RouterBOARD adalah komputer mini yang dirancang khusus untuk menjalankan sistem operasi RouterOS. Kamu bisa membayangkan RouterBOARD sebagai "wadah" fisik, dan RouterOS sebagai "otak" di dalamnya.



### Komponen RouterBOARD

Sama seperti komputer biasa, RouterBOARD memiliki komponen-komponen utama:

- **Prosesor (CPU)**: Ini adalah otak RouterBOARD yang memproses semua instruksi dan data.
    
- **RAM (Memori)**: Digunakan untuk menyimpan data sementara saat perangkat sedang beroperasi.
    
- **ROM (Read-Only Memory) dan Flash Storage**: Ini adalah tempat RouterOS diinstal secara permanen. Berbeda dengan PC yang menggunakan hard drive, RouterBOARD menggunakan memori flash yang lebih tahan banting dan efisien.
    
- **Port Ethernet**: Ini adalah colokan untuk kabel jaringan. Beberapa model memiliki beberapa port, yang memungkinkan RouterBOARD terhubung ke banyak perangkat atau jaringan sekaligus.
    
- **Port SFP/SFP+**: Pada model-model tertentu, ada port untuk modul fiber optik (kabel serat optik), yang biasanya digunakan untuk koneksi jarak jauh dengan kecepatan tinggi.
    
- **Modul Wi-Fi**: Banyak RouterBOARD juga dilengkapi dengan modul wireless (Wi-Fi) bawaan, menjadikannya router nirkabel yang lengkap.
    



### Keuntungan Menggunakan RouterBOARD

Mengapa banyak orang memilih RouterBOARD?

- **Praktis dan Hemat Ruang**: RouterBOARD memiliki ukuran yang ringkas dan portabel, cocok untuk ruang kerja yang terbatas atau kebutuhan mobilitas.
    
- **Desain Terintegrasi**: Karena hardware dan software-nya dirancang oleh Mikrotik, keduanya bekerja sangat optimal. Ini meminimalisasi masalah kompatibilitas dan menghasilkan kinerja yang stabil.
    
- **Tahan Lama**: RouterBOARD tidak menggunakan hard drive mekanik, sehingga lebih tahan terhadap guncangan dan kerusakan fisik. Ini juga membuat sistem operasinya tidak mudah _corrupt_.
    
- **Beragam Pilihan**: Mikrotik menawarkan berbagai model RouterBOARD dengan spesifikasi dan harga yang berbeda, mulai dari model untuk penggunaan rumahan hingga perangkat kelas _enterprise_ untuk ISP (Internet Service Provider).
    



### Perbedaan Utama RouterBOARD dan RouterOS

Penting untuk membedakan keduanya, karena ini adalah konsep dasar dalam ekosistem Mikrotik:

- **RouterBOARD**: **Hardware** (perangkat keras) fisik, seperti motherboard, CPU, RAM, dan port jaringan.
    
- **RouterOS**: **Software** (sistem operasi) yang berjalan di atas RouterBOARD, menyediakan semua fitur routing, firewall, dan manajemen jaringan.
    

Singkatnya, **RouterBOARD adalah badan, dan RouterOS adalah jiwa** dari sebuah router Mikrotik. Keduanya bekerja bersama-sama untuk menciptakan solusi jaringan yang kuat dan serbaguna.

Video ini memberikan gambaran yang bagus tentang perangkat keras dan produk Mikrotik, termasuk RouterBOARD. An Introduction to RouterBOARD and MikroTik Hardware

--- 

## Pertama Kali Mengakses Router

Ada tiga cara utama untuk mengakses router Mikrotik untuk pertama kalinya, yaitu melalui **WinBox**, **WebFig**, dan **Quick Set**. Masing-masing memiliki keunggulan, tetapi tujuannya sama: memberi kamu akses ke RouterOS.

#### 1. WinBox dan MAC-WinBox

**WinBox** adalah aplikasi kecil (GUI) khusus untuk Windows yang sangat populer di kalangan pengguna Mikrotik.

- **Keunggulan**: Tampilannya sangat lengkap dan cepat. Hampir semua konfigurasi bisa dilakukan di sini. Ini juga sangat stabil dan responsif.
    
- **Cara Penggunaan (WinBox)**:
    
    1. Sambungkan komputer kamu ke salah satu port LAN (bukan port WAN/Internet) di router Mikrotik menggunakan kabel Ethernet.
        
    2. Unduh aplikasi `winbox.exe` dari situs resmi Mikrotik dan jalankan (tidak perlu instalasi).
        
    3. Buka WinBox, pergi ke tab **`Neighbors`**. Di sini, WinBox akan secara otomatis mendeteksi semua perangkat Mikrotik yang terhubung di jaringan lokalmu, baik berdasarkan IP Address maupun MAC Address.
        
    4. Untuk pertama kali, seringkali IP Address belum terkonfigurasi. Jadi, kamu bisa mencoba klik pada **MAC Address**-nya.
        
    5. Masukkan username **`admin`** dan biarkan password kosong (default).
        
    6. Klik **`Connect`**.
        

**MAC-WinBox** adalah metode koneksi melalui MAC Address, yang sangat berguna saat router belum memiliki IP Address. Ini memastikan kamu tetap bisa mengakses router meskipun ada masalah pada konfigurasi IP.

---
#### 2. WebFig dan Quick Set

**WebFig** adalah antarmuka berbasis web. Ini mirip seperti mengakses router Wi-Fi pada umumnya, di mana kamu bisa mengelola router dari _browser_ (seperti Chrome, Firefox, dll.).

- **Keunggulan**: Tidak perlu menginstal aplikasi tambahan. Kamu bisa mengaksesnya dari perangkat apa pun yang memiliki browser, termasuk laptop macOS atau smartphone.
    
- **Cara Penggunaan (WebFig)**:
    
    1. Sambungkan komputer kamu ke router.
        
    2. Buka browser dan ketik alamat IP default Mikrotik, yaitu **`192.168.88.1`**.
        
    3. Masukkan username **`admin`** dan biarkan password kosong.
        

**Quick Set** adalah fitur di dalam WebFig yang dirancang khusus untuk pemula. Ini adalah tampilan yang paling sederhana dan seringkali menjadi halaman pertama yang muncul saat kamu mengakses router Mikrotik yang baru.

- **Tujuan Quick Set**: Mengatur konfigurasi dasar seperti nama Wi-Fi (SSID), password Wi-Fi, dan mode router (misalnya, `Home AP` untuk router di rumah) dalam satu halaman saja. Ini mempercepat proses _setup_ awal tanpa harus masuk ke menu yang rumit.
    

---
#### 3. Default Configuration

Saat kamu pertama kali terhubung ke router Mikrotik, kamu akan melihat sebuah _pop-up_ yang menanyakan apakah kamu ingin "Remove Configuration" atau tidak. Ini merujuk pada **Default Configuration** atau konfigurasi bawaan pabrik.

- Apa itu Default Configuration?
    
    Ini adalah serangkaian aturan dasar yang sudah terpasang dari pabrik agar router bisa langsung berfungsi. Konfigurasi ini biasanya mencakup:
    
    - **IP Address**: `192.168.88.1` pada port LAN (atau bridge).
        
    - **DHCP Server**: Aktif di port LAN agar perangkat lain bisa mendapatkan IP Address otomatis.
        
    - **Firewall**: Aturan dasar untuk melindungi jaringan dari serangan dari luar (port WAN/Internet).
        
    - **NAT (Masquerade)**: Aturan untuk berbagi koneksi internet dari satu IP publik ke banyak perangkat di jaringan lokalmu.
        
    - **Wireless**: Konfigurasi dasar untuk Wi-Fi (jika router-nya memiliki fitur ini).
        
- **Apa yang Harus Dilakukan?**
    
    - **Untuk Pemula**: **Jangan hapus** Default Configuration. Klik **`OK`** untuk tetap menggunakannya. Kamu bisa mengubah pengaturan yang kamu butuhkan (seperti nama Wi-Fi atau password) dari WebFig atau WinBox.
        
    - **Untuk Pengguna Ahli**: Kamu bisa memilih untuk menghapusnya jika kamu ingin membuat konfigurasi jaringan dari awal, yang sepenuhnya disesuaikan dengan kebutuhanmu.
        

Singkatnya, untuk pertama kali, gunakan **WinBox** atau **WebFig** untuk masuk ke router. Pastikan untuk tidak menghapus konfigurasi default dan segera ubah password admin untuk alasan keamanan.

---

## RouterOS Command Line Interface (CLI): Kontrol Penuh dengan Teks

**Command Line Interface (CLI)** adalah metode interaksi dengan sistem operasi (RouterOS) menggunakan perintah berbasis teks. Ini berbeda dengan antarmuka grafis (GUI) seperti WinBox atau WebFig, di mana kamu mengklik tombol dan mengisi formulir. CLI adalah alat yang sangat powerful dan efisien bagi administrator jaringan profesional.

- **Mengapa CLI Penting?**
    
    - **Efisiensi**: Kamu bisa menyelesaikan tugas yang kompleks dengan cepat. Misalnya, untuk mengaktifkan 500 port firewall, daripada mengklik satu per satu, kamu cukup mengetik satu atau dua perintah.
        
    - **Otomatisasi**: CLI memungkinkan kamu membuat _script_ (program) yang bisa menjalankan serangkaian perintah secara otomatis, menghemat waktu dan mengurangi kesalahan manual.
        
    - **Diagnostik Lanjutan**: Beberapa alat diagnostik jaringan yang paling kuat hanya tersedia melalui CLI, memungkinkan kamu untuk memeriksa masalah dengan sangat rinci.
        
    - **Akses Minimalis**: Saat router bermasalah atau sumber daya terbatas, CLI bisa menjadi satu-satunya cara untuk mengakses dan memperbaikinya.
        

Ada empat cara utama untuk mengakses CLI pada RouterOS, yang masing-masing punya skenario penggunaan ideal.


---
### 1. Null Modem Cable (Serial Console)

**Null modem** adalah metode koneksi fisik yang sangat fundamental dan seringkali menjadi "jalur penyelamat" saat semua jalur lain terputus.

- Apa Itu Null Modem?
    
    Ini adalah jenis kabel serial yang menghubungkan langsung port serial (biasanya RS232) di RouterBOARD ke port serial di komputer. Banyak RouterBOARD memiliki port serial fisik yang terlihat seperti port lama di komputer. Kabel ini memungkinkan komunikasi langsung antara dua perangkat tanpa melalui jaringan.
    
- **Skenario Penggunaan**:
    
    - **_Initial Setup_** **Tanpa IP**: Saat router masih baru dan belum memiliki IP Address, atau saat konfigurasi awal gagal dan router tidak terdeteksi di jaringan.
        
    - **_Troubleshooting_ Kritis**: Ketika router mengalami masalah serius, seperti _bootloop_ (terus-menerus _restart_), atau konfigurasi firewall yang terlalu ketat sehingga memblokir semua akses jaringan. Konsol serial memungkinkan kamu melihat log _boot_ secara _real-time_ dan melakukan perbaikan tanpa perlu koneksi jaringan.
        
    - **Pembaruan Firmware Tingkat Rendah**: Dalam beberapa kasus langka, pembaruan firmware atau _bootloader_ memerlukan akses langsung melalui konsol serial.
        
- **Kelemahan**: Metode ini tidak praktis untuk penggunaan sehari-hari karena memerlukan kabel fisik dan mengharuskan kamu berada di dekat perangkat router.
    


---
### 2. SSH dan Telnet: Akses Jarak Jauh (Remote Access)

Ini adalah metode utama untuk mengakses CLI dari jaringan, baik di dalam jaringan lokal maupun dari lokasi yang jauh.

#### SSH (Secure Shell)

**SSH** adalah protokol jaringan yang memungkinkan kamu mengakses CLI secara **aman dan terenkripsi** melalui jaringan.

- **Cara Kerja**: SSH membuat "terowongan" yang aman antara komputer kamu dan router. Semua data yang dikirim, termasuk username, password, dan perintah yang kamu ketik, diacak (dienkripsi).
    
- **Kelebihan**:
    
    - **Keamanan Maksimal**: Mencegah orang lain (seperti peretas) untuk menguping data yang kamu kirim, sehingga sangat cocok untuk akses dari jaringan publik atau internet.
        
    - **Autentikasi Kuat**: SSH mendukung berbagai metode autentikasi, termasuk kunci SSH, yang lebih aman daripada sekadar password.
        
- **Skenario Penggunaan**:
    
    - **Pilihan Utama untuk Akses Jarak Jauh**: Sebagian besar administrator jaringan selalu menggunakan SSH saat mengakses router dari luar jaringan kantor.
        
    - **Manajemen Harian**: Mengonfigurasi router dari komputer kerja kamu dengan aman.
        

#### Telnet

**Telnet** adalah protokol jaringan lama yang juga digunakan untuk mengakses CLI, tetapi **tidak aman** karena semua data dikirim dalam bentuk teks biasa.

- **Kelebihan**: Cukup sederhana dan cepat untuk digunakan, tetapi hanya direkomendasikan dalam lingkungan jaringan yang sangat aman (misalnya, di dalam jaringan kantor yang sudah terlindungi firewall).
    
- **Kelemahan Paling Fatal**:
    
    - **Tidak Terenkripsi**: Siapapun yang bisa mengakses jaringan kamu bisa melihat username, password, dan perintah yang kamu ketik. Ini merupakan risiko keamanan yang sangat besar.
        
- **Skenario Penggunaan**:
    
    - **Penggunaan Terbatas**: Hanya digunakan di lingkungan yang sangat terkontrol dan terisolasi. Dalam praktiknya, sebagian besar administrator jaringan modern telah menonaktifkan Telnet di router mereka dan beralih sepenuhnya ke SSH.
        


---
### 3. New Terminal di WinBox/WebFig

Ini adalah metode yang paling mudah dan nyaman jika kamu sudah berhasil terhubung ke router melalui WinBox atau WebFig.

- **Cara Akses**: WinBox dan WebFig memiliki fitur bawaan untuk membuka jendela CLI langsung. Kamu tidak perlu aplikasi tambahan seperti PuTTY.
    
- **Keunggulan**:
    
    - **Terintegrasi**: Kamu bisa beralih dengan cepat antara antarmuka grafis (misalnya, untuk melihat status _interface_) dan CLI (untuk mengetik perintah).
        
    - **Tidak Perlu Konfigurasi Tambahan**: Cukup satu klik, dan kamu sudah terhubung ke CLI.
        
- **Skenario Penggunaan**:
    
    - **Kombinasi GUI dan CLI**: Sangat berguna untuk pengguna yang lebih suka menggunakan GUI tetapi perlu melakukan beberapa tugas khusus atau _debugging_ yang lebih mudah dilakukan dengan CLI.
        

Dengan memahami keempat metode ini, kamu bisa memilih cara yang paling tepat untuk setiap situasi, apakah itu untuk konfigurasi awal, _troubleshooting_ darurat, atau manajemen sehari-hari yang aman.

---

## Prinsip-prinsip Dasar RouterOS CLI

RouterOS CLI tidak hanya sekadar tempat untuk mengetik perintah. Ia memiliki serangkaian fitur bawaan yang dirancang untuk mempercepat dan mempermudah pekerjaan kamu.

#### `,` (Koma), `Double Tab` (Tombol Tab dua kali), `?` (Tanda Tanya), dan Navigasi

Fitur-fitur ini adalah kunci untuk berinteraksi dengan CLI secara efektif tanpa harus menghafal setiap perintah.

- **`,` (Koma): Mengakses Parameter Lanjutan**
    
    - Saat kamu berada di sebuah menu, misalnya `/ip address`, kamu bisa menggunakan tanda koma (`,`) untuk melihat parameter atau properti yang bisa diatur pada sebuah objek.
        
    - **Contoh**: Jika kamu ingin melihat semua _interface_ yang ada di router, kamu bisa mengetik `print`, dan CLI akan menampilkan daftar. Tapi, jika kamu ingin melihat informasi yang lebih detail tentang setiap _interface_, kamu bisa menambahkan koma: `/interface print ,`.
        
    - Ini sangat berguna untuk mendapatkan informasi yang tidak ditampilkan secara default dan membantu kamu menemukan properti yang spesifik.
        
- **`Double Tab` (Tombol Tab dua kali): Autokomplet dan Saran Perintah**
    
    - Ini adalah fitur paling penting untuk menghemat waktu dan mencegah kesalahan pengetikan. Ketika kamu mengetik perintah dan menekan tombol `Tab` dua kali, CLI akan menampilkan semua opsi yang tersedia.
        
    - **Contoh**: Jika kamu berada di root directory dan ingin tahu semua menu yang bisa diakses, ketik `t<double tab>`, dan CLI akan menampilkan: `telnet`, `terminal`, `tool`.
        
    - Jika kamu mengetik `/interface set` dan menekan `tab` dua kali, CLI akan menampilkan daftar semua parameter yang bisa diubah, seperti `name`, `mtu`, atau `comment`.
        
- **`?` (Tanda Tanya): Bantuan Langsung**
    
    - Sama seperti `double tab`, tanda tanya ( `?` ) juga berfungsi sebagai alat bantu, tetapi dengan format yang berbeda. Ia memberikan daftar parameter yang lebih terstruktur.
        
    - **Contoh**: Jika kamu mengetik `/ip address add ?`, CLI akan menampilkan daftar semua properti yang bisa ditambahkan, beserta penjelasannya.
        
- **Navigasi: Berpindah Menu**
    
    - **`/` (Garis Miring)**: Mengarahkan kamu ke root directory (direktori utama). Ini seperti tombol "Home" pada komputer.
        
    - **`..` (Dua Titik)**: Naik satu level direktori. Jika kamu berada di `/ip address`, mengetik `..` akan membawa kamu ke `/ip`.
        
    - **`up` dan `down` (Tombol panah atas dan bawah)**: Memungkinkan kamu untuk menelusuri riwayat perintah yang sudah pernah kamu ketik. Ini menghemat waktu karena kamu tidak perlu mengetik ulang perintah yang sama.
        

---

### Command History dan Manfaatnya

**Command History** adalah fitur yang merekam semua perintah yang pernah kamu ketik di CLI.

- **Apa itu Command History?**
    
    - RouterOS menyimpan catatan dari setiap perintah yang dieksekusi oleh pengguna. Catatan ini tersimpan di memori dan bisa diakses kapan saja selama sesi berjalan.
        
- **Manfaat Utama dari Command History**:
    
    1. **Re-eksekusi Perintah Cepat**: Kamu bisa menggunakan tombol panah `up` dan `down` untuk menelusuri dan menjalankan kembali perintah yang sudah kamu ketik sebelumnya tanpa harus mengetik ulang. Ini sangat berguna untuk menguji konfigurasi berulang kali.
        
    2. **Edit Perintah yang Sudah Ada**: Jika kamu ingin menjalankan perintah yang mirip dengan yang sebelumnya, kamu bisa memanggilnya dari _history_, mengedit bagian yang diperlukan, lalu menekan `Enter`. Misalnya, jika kamu sudah membuat IP address untuk _interface_ `ether1`, kamu bisa memanggil kembali perintah tersebut dan mengubah `ether1` menjadi `ether2` dengan cepat.
        
    3. **Belajar dari Kesalahan**: Dengan melihat riwayat perintah, kamu bisa melacak langkah-langkah yang sudah diambil dan menemukan kesalahan konfigurasi yang mungkin terjadi.
        
    4. **Membangun Script**: Sebagian besar skrip otomasi dimulai dengan mengumpulkan perintah-perintah yang benar dari _command history_ dan menyimpannya dalam satu file.
        

Dengan menguasai fitur-fitur seperti `double tab`, `?`, dan _command history_, kamu tidak perlu menjadi seorang ahli yang menghafal ratusan perintah. Kamu bisa mengandalkan CLI itu sendiri untuk memandumu dalam setiap langkah konfigurasi.

---

## Konfigurasi Awal (Akses Internet)

Untuk membuat router Mikrotik mendapatkan akses internet dan membagikannya ke perangkat lain, ada tiga langkah dasar yang harus kamu lakukan.

#### 1. WAN DHCP-Client

**WAN (Wide Area Network)** adalah "jaringan luar", yaitu koneksi yang datang dari penyedia layanan internet (ISP) kamu. Port WAN biasanya adalah port yang kamu hubungkan ke modem atau ONT fiber optik.

**DHCP-Client** adalah fitur di RouterOS yang bertindak seperti "peminta alamat". Ketika kamu mengaktifkan DHCP-Client pada sebuah port, port tersebut akan secara otomatis meminta alamat IP, subnet mask, gateway, dan DNS server dari server DHCP (Dynamic Host Configuration Protocol) yang ada di jaringan luar (yaitu modem atau server ISP kamu).

Penjelasan Lebih Dalam:

Bayangkan kamu pindah ke sebuah rumah baru dan perlu listrik. Kamu tidak perlu tahu alamat IP-nya, kamu hanya perlu mendaftar ke perusahaan listrik. DHCP-Client melakukan hal yang sama: ia menghubungi "perusahaan listrik" (server DHCP) di jaringan luar dan meminta informasi yang diperlukan agar bisa terhubung. Ini jauh lebih mudah daripada harus memasukkan semua data IP secara manual.

**Cara Konfigurasi (di CLI)**:

```
/ip dhcp-client add interface=ether1 disabled=no
```

_(Asumsi `ether1` adalah port WAN yang terhubung ke modem kamu)_

---

#### 2. LAN IP Address dan Default Gateway

**LAN (Local Area Network)** adalah "jaringan dalam", yaitu jaringan yang kamu buat sendiri untuk perangkat-perangkat di rumah atau kantor.

**IP Address dan Default Gateway** adalah alamat yang diberikan ke perangkat-perangkat di jaringan LAN.

- **IP Address**: Alamat unik untuk router di jaringan LAN kamu. Ini adalah alamat yang akan kamu ketik di _browser_ untuk mengakses WebFig (biasanya `192.168.88.1`).
    
- **Default Gateway**: Alamat router yang berfungsi sebagai "gerbang" untuk semua lalu lintas data yang ingin keluar dari jaringan LAN menuju internet. Setiap perangkat di jaringan LAN kamu (laptop, smartphone, dll.) akan mengirimkan data ke alamat ini jika mereka ingin terhubung ke internet.
    

**Cara Konfigurasi (di CLI)**:

```
/ip address add address=192.168.88.1/24 interface=bridge
/ip pool add name=dhcp_pool ranges=192.168.88.10-192.168.88.254
/ip dhcp-server add name=dhcp_server address-pool=dhcp_pool interface=bridge
```

_(Konfigurasi ini akan membuat IP Address `192.168.88.1` pada **bridge** dan mengaktifkan DHCP Server agar perangkat lain bisa mendapatkan IP otomatis)_

---

#### 3. Basic Firewall - NAT Masquerade

Ini adalah bagian terpenting dan sering membingungkan, jadi mari kita jelaskan secara rinci.

**Firewall** adalah program yang mengontrol lalu lintas data masuk dan keluar dari jaringan. Ia bertindak sebagai "penjaga gerbang" yang memastikan hanya data yang diizinkan yang bisa lewat.

**NAT (Network Address Translation)** adalah sebuah teknik yang memungkinkan banyak perangkat di jaringan lokal (LAN) untuk berbagi satu alamat IP publik dari ISP kamu.

**Masquerade** adalah salah satu jenis NAT yang paling umum dan mudah.

Penjelasan Lengkap tentang Masquerade:

Bayangkan sebuah kantor pos. Di dalam kantor, ada banyak orang (perangkat di LAN) yang ingin mengirim surat. Setiap orang punya alamat rumah masing-masing (IP privat). Namun, saat surat-surat itu keluar dari kantor pos, semuanya menggunakan alamat kantor pos (IP publik).

Ketika balasan datang, kantor pos (router Mikrotik) tahu surat mana yang harus diberikan ke orang yang mana, meskipun semua balasan datang ke alamat kantor pos yang sama.

**Masquerade** adalah proses di mana router Mikrotik secara otomatis:

1. **Mengubah Alamat Sumber**: Ketika paket data dari perangkat LAN (`192.168.88.10`) keluar menuju internet, Router Mikrotik akan mengganti alamat sumbernya dari `192.168.88.10` menjadi alamat IP publik yang didapatkan dari ISP.
    
2. **Mencatat Koneksi**: Router Mikrotik akan mencatat di "buku besar"nya (tabel koneksi) bahwa perangkat `192.168.88.10` memulai koneksi ke internet.
    
3. **Mengembalikan Alamat Tujuan**: Ketika ada balasan dari internet, Router Mikrotik melihat catatan di "buku besar"nya dan mengembalikan alamat tujuan dari IP publiknya kembali ke alamat IP pribadi `192.168.88.10`.
    

Tanpa **Masquerade**, perangkat-perangkat di jaringan lokal kamu tidak akan bisa mengakses internet karena alamat IP pribadi (`192.168.x.x`) tidak bisa dikenali di internet.

**Cara Konfigurasi (di CLI)**:

```
/ip firewall nat add chain=srcnat out-interface=ether1 action=masquerade
```

_(Perintah ini akan mengaktifkan NAT Masquerade pada lalu lintas yang keluar dari port `ether1` (port WAN) kamu.)_

Dengan tiga langkah ini, kamu sudah memiliki konfigurasi dasar yang memungkinkan router Mikrotik mendapatkan internet dan membagikannya ke semua perangkat di jaringan lokalmu.

---

## Upgrading RouterOS

### Jenis Paket RouterOS

RouterOS terdiri dari beberapa paket yang bisa diinstal secara terpisah. Ada dua jenis utama yang perlu Anda ketahui:

- **`routeros` (Main package):** Ini adalah paket utama yang berisi semua fungsionalitas inti dari RouterOS.1 Paket ini sudah mencakup fitur-fitur dasar seperti routing, firewall, DHCP, dan wireless. Jika Anda hanya ingin router berfungsi, paket ini sudah cukup.
    
- **`all_packages`:** Ini adalah paket komprehensif yang berisi paket utama (`routeros`) dan semua paket tambahan lainnya, seperti **PPP** (untuk VPN), **Hotspot**, **MPLS**, dan lain-lain. Menggunakan paket ini memastikan semua fitur tersedia, meskipun mungkin ada beberapa yang tidak Anda perlukan.
    

Sangat disarankan untuk mengunduh paket `all_packages` karena lebih mudah dan memastikan tidak ada kekurangan fitur yang mungkin Anda butuhkan di masa mendatang.

---

### Cara Melakukan Peningkatan (Upgrading) RouterOS

Ada beberapa cara untuk memutakhirkan RouterOS, masing-masing dengan keunggulan tersendiri:

1. **Menggunakan WinBox (Disarankan)**: Ini adalah cara paling mudah dan disarankan untuk pemula.2
    
    - Unduh paket `all_packages` dari situs resmi Mikrotik.
        
    - Buka WinBox dan masuk ke router Anda.
        
    - Tarik dan letakkan (drag and drop) file `.zip` yang sudah diunduh ke dalam jendela **Files** di WinBox.3 Router akan secara otomatis mengekstrak dan menempatkan paket di tempat yang benar.
        
    - Buka menu **System > Packages** dan klik tombol **`Check For Updates`**. 4Jika ada versi yang lebih baru, Anda bisa langsung mengunduhnya dari sini.
        
    - Setelah file berada di router, lakukan _reboot_ (mulai ulang).5 Router akan otomatis menginstal paket saat menyala kembali.
        
2. **Menggunakan CLI (Command Line Interface)**: Ini adalah cara yang lebih cepat untuk administrator yang terbiasa dengan baris perintah.
    
    - Masuk ke CLI melalui WinBox Terminal, SSH, atau WebFig Terminal.
        
    - Ketik perintah: `/system package update check-for-updates once`.
        
    - Jika ada versi baru, ketik `/system package update install` untuk memulai proses pembaruan dan _reboot_.
        
3. **Melalui Netinstall**: Ini adalah metode "pemulihan" atau "instalasi bersih" yang digunakan saat router bermasalah atau tidak bisa diakses sama sekali.6
    
    - Metode ini menghapus semua konfigurasi dan menginstal ulang RouterOS dari awal. Ini adalah solusi terakhir jika semua metode lain gagal.
        

---

### Pembaruan Firmware RouterBOOT

**RouterBOOT** adalah _bootloader_ atau firmware tingkat rendah yang berfungsi sebagai "BIOS" pada komputer. Ini adalah program yang berjalan pertama kali saat router dinyalakan.

Sangat penting untuk selalu memperbarui firmware **RouterBOOT** setelah Anda memperbarui RouterOS. Pembaruan ini memastikan kompatibilitas dan stabilitas antara perangkat lunak (RouterOS) dan perangkat keras (RouterBOARD).

- **Cara Memperbarui RouterBOOT**:
    
    - Setelah RouterOS berhasil diperbarui, buka menu **System > RouterBOARD**.7
        
    - Di sana, Anda akan melihat versi firmware saat ini (`Current Firmware`) dan versi firmware terbaru yang tersedia (`Upgrade Firmware`).
        
    - Klik tombol **`Upgrade`**. Router akan memuat firmware terbaru, tetapi belum menginstalnya.
        
    - Terakhir, lakukan _reboot_ router.8 Router akan menginstal firmware RouterBOOT saat proses _booting_ dan mengkonfirmasi pembaruan di log sistem.
        

Dengan melakukan pembaruan ini secara berkala, Anda tidak hanya mendapatkan fitur-fitur terbaru tetapi juga menutup celah keamanan yang mungkin ada. Pembaruan ini adalah bagian dari praktik terbaik dalam mengelola perangkat jaringan.

---

### Router Identity

**Router identity** adalah nama unik yang diberikan pada setiap perangkat router Mikrotik. Nama ini berfungsi sebagai pengenal utama untuk membedakan satu router dari router lainnya dalam jaringan. Ibaratnya, jika RouterOS adalah sistem operasi dan RouterBOARD adalah perangkat kerasnya, maka _router identity_ adalah nama panggilan atau label pada perangkat tersebut.

---

### Manfaat Mengatur Router Identity

Meskipun terlihat sederhana, mengatur _router identity_ memiliki banyak manfaat penting, terutama untuk administrasi jaringan:

1. **Identifikasi Mudah**: Di jaringan yang memiliki banyak router Mikrotik, seperti di lingkungan kantor atau ISP, _router identity_ membuat Anda bisa langsung mengenali perangkat mana yang sedang Anda akses. Misalnya, Anda bisa menamainya `Mikrotik-Kantor-Pusat` atau `AP-Lantai-2-Ruang-Meeting`.
    
2. **Manajemen Jarak Jauh (Remote)**: Ketika Anda mengelola router dari jarak jauh menggunakan WinBox atau SSH, nama identitas ini akan muncul di daftar perangkat. Ini mencegah Anda salah terhubung ke router yang berbeda.
    
3. **Logging dan Monitoring**: Log sistem dan notifikasi dari router akan menyertakan nama identitas ini. Ini sangat membantu saat Anda memantau log dari beberapa router secara terpusat, karena Anda akan tahu persis dari router mana pesan tersebut berasal.
    
4. **Skrip dan Otomatisasi**: Dalam skrip RouterOS, nama identitas sering digunakan sebagai variabel untuk mengotomatisasi tugas, memastikan bahwa skrip hanya berjalan di router yang benar.
    

---

## Cara Mengatur Router Identity

Anda bisa mengatur _router identity_ dengan mudah, baik melalui WinBox maupun CLI.

1. **Melalui WinBox**:
    
    - Masuk ke router Anda menggunakan WinBox.
        
    - Pilih menu **System > Identity**.
        
    - Ketik nama yang Anda inginkan di kolom `Name`.
        
    - Klik **Apply** atau **OK**.
        
2. **Melalui CLI (Command Line Interface)**:
    
    - Buka **New Terminal** di WinBox atau sambungkan melalui SSH.
        
    - Gunakan perintah berikut:
        
        ```
        /system identity set name="Nama_Router_Anda"
        ```
        
    - Misalnya, untuk menamai router dengan `router-utama-jakarta`, Anda akan mengetik:
        
        ```
        /system identity set name="router-utama-jakarta"
        ```
        
    - Setelah itu, Anda bisa memverifikasi nama baru dengan perintah `/system identity print`.
        

Mengubah nama identitas tidak akan memengaruhi konfigurasi atau fungsionalitas router, tetapi merupakan langkah penting dalam praktik terbaik manajemen jaringan.

---

## Mengelola Log masuk RouterOS

Mengelola log masuk (logins) pada RouterOS adalah langkah penting untuk menjaga keamanan perangkat Anda. Dengan mengelola pengguna, Anda dapat mengontrol siapa yang memiliki akses ke router dan apa saja yang bisa mereka lakukan. RouterOS memiliki fitur canggih untuk mengelola pengguna, termasuk pembuatan grup dengan hak akses yang berbeda.

---

### Prinsip Dasar Pengelolaan Pengguna

- **Pengguna (Users)**: Setiap orang yang ingin mengakses router harus memiliki akun pengguna.1 Setiap pengguna memiliki **nama (name)**, **kata sandi (password)**, dan **grup (group)**.2
    
- **Grup (Groups)**: Grup adalah kumpulan hak akses atau izin. Anda tidak memberikan hak akses langsung ke pengguna, melainkan ke grup. Kemudian, Anda memasukkan pengguna ke dalam grup yang sesuai. Cara ini mempermudah manajemen, terutama jika Anda memiliki banyak pengguna.
    
- **Hak Akses (Permissions)**: Hak akses menentukan apa yang bisa dilakukan oleh pengguna. RouterOS memiliki beberapa hak akses (permissions) bawaan, seperti:
    
    - **`full`**: Hak akses tertinggi.3 Pengguna dapat melihat dan mengubah semua konfigurasi, bahkan menghapus konfigurasi. Ini hanya disarankan untuk administrator utama.
        
    - **`read`**: Pengguna hanya dapat melihat konfigurasi, tidak bisa mengubah apa pun. Cocok untuk auditor atau pengguna yang hanya perlu memantau.
        
    - **`write`**: Pengguna dapat melihat dan mengubah konfigurasi, tetapi tidak bisa menghapus konfigurasi yang ada.
        
    - **`policy`**: Hak akses ini spesifik untuk mengelola kebijakan pengguna lain, seperti membuat atau menghapus pengguna.
        
    - **`test`**: Hak akses untuk menguji fitur tertentu tanpa mengubah konfigurasi yang sudah disimpan.
        

---

### Cara Mengelola Pengguna

Anda bisa mengelola pengguna melalui **WinBox** atau **CLI**.4

#### Melalui WinBox

1. Buka WinBox dan masuk ke router Anda.
    
2. Pilih menu **System > Users**.
    
3. Di sini, Anda dapat:
    
    - **Menambahkan pengguna baru**: Klik tombol **`+`** (plus), lalu masukkan nama, sandi, dan pilih grup untuk pengguna baru.5
        
    - **Mengubah pengguna yang sudah ada**: Klik dua kali pada nama pengguna, lalu ubah sandi atau grupnya.
        
    - **Menghapus pengguna**: Pilih nama pengguna dan klik tombol **`-`** (minus).
        

#### Melalui CLI (Command Line Interface)

1. Buka **Terminal** di WinBox atau sambungkan melalui SSH.
    
2. **Untuk melihat daftar pengguna**:
    
    ```
    /user print
    ```
    
3. **Untuk menambahkan pengguna baru**:
    
    ```
    /user add name=nama_pengguna group=grup_hak_akses password=sandi_aman
    ```
    
    - Contoh: `/user add name=admin_lokal group=full password=rahasia123`
        
4. **Untuk mengubah sandi pengguna**:
    
    ```
    /user set password=sandi_baru_aman [find name=nama_pengguna]
    ```
    
    - Contoh: `/user set password=sandi_baru [find name=admin_lokal]`
        
5. **Untuk menghapus pengguna**:
    
    ```
    /user remove [find name=nama_pengguna]
    ```
    
    - Contoh: `/user remove [find name=admin_lokal]`
        

### Praktik Terbaik untuk Keamanan

- **Ubah Kata Sandi Default**: Segera setelah Anda mengakses router Mikrotik untuk pertama kalinya, ubah kata sandi untuk akun `admin` yang kosong.
    
- **Buat Akun Administrator Baru**: Hapus akun `admin` bawaan dan buat akun administrator baru dengan nama yang unik.
    
- **Gunakan Kata Sandi yang Kuat**: Selalu gunakan kombinasi huruf besar, huruf kecil, angka, dan simbol untuk kata sandi.
    
- **Gunakan Grup dengan Bijak**: Jangan berikan hak akses `full` kepada semua orang. Berikan hak akses yang paling minimal yang dibutuhkan oleh seorang pengguna untuk menyelesaikan pekerjaannya.
    
- **Nonaktifkan Layanan yang Tidak Digunakan**: Nonaktifkan layanan akses seperti Telnet dan FTP jika Anda tidak menggunakannya. Ini mengurangi potensi serangan dari luar.
    

Dengan mengelola log masuk secara efektif, Anda dapat memastikan bahwa hanya orang yang berhak yang bisa mengubah konfigurasi router Anda, sehingga menjaga jaringan tetap aman dan stabil.

---

## Mengelola Layanan RouterOS

Mengelola layanan (services) pada RouterOS adalah langkah penting untuk menjaga keamanan dan efisiensi router Anda. Layanan-layanan ini adalah protokol yang digunakan untuk mengakses atau mengelola router, seperti WinBox, SSH, atau HTTP. Mengelola layanan berarti Anda bisa mengaktifkan atau menonaktifkan layanan tersebut dan mengontrol dari mana layanan itu bisa diakses.

---

### Layanan Penting di RouterOS

RouterOS menyediakan berbagai layanan yang dapat diaktifkan atau dinonaktifkan sesuai kebutuhan. Berikut adalah beberapa layanan yang paling umum:

1. **WinBox**: Layanan ini memungkinkan Anda terhubung ke router menggunakan aplikasi WinBox. Ini adalah cara paling populer untuk mengelola router secara grafis.
    
2. **API (Application Programming Interface)**: Layanan yang memungkinkan aplikasi pihak ketiga atau skrip khusus untuk berinteraksi dengan RouterOS.
    
3. **WWW/HTTP**: Layanan ini memungkinkan Anda mengakses antarmuka berbasis web (WebFig) melalui _browser_ Anda.
    
4. **SSH (Secure Shell)**: Layanan yang memungkinkan akses _command line interface_ (CLI) yang aman dan terenkripsi dari jarak jauh. Ini adalah metode yang direkomendasikan untuk administrasi jarak jauh.
    
5. **Telnet**: Layanan lama untuk mengakses CLI, tetapi tidak aman karena tidak ada enkripsi. Disarankan untuk dinonaktifkan.
    
6. **FTP (File Transfer Protocol)**: Layanan untuk mentransfer file ke dan dari router. Berguna untuk mengunggah atau mengunduh _backup_ konfigurasi atau file lain.
    

---

### Cara Mengelola Layanan

Anda dapat mengelola layanan ini dengan mudah melalui WinBox atau CLI.

#### Melalui WinBox

1. Buka WinBox dan masuk ke router Anda.
    
2. Pilih menu **IP > Services**.
    
3. Di sini, Anda akan melihat daftar semua layanan.
    
4. Anda bisa mengelola setiap layanan dengan cara berikut:
    
    - **Menonaktifkan/Mengaktifkan**: Klik pada layanan yang ingin diubah, lalu klik tombol **`Disable`** atau **`Enable`**. Menonaktifkan layanan yang tidak digunakan adalah langkah penting untuk meningkatkan keamanan.
        
    - **Mengubah Port**: Klik dua kali pada layanan, lalu ubah nomor **`Port`**-nya. Mengubah port default dapat mengurangi risiko serangan otomatis dari _bot_.
        
    - **Membatasi Akses**: Di kolom **`Available From`**, Anda dapat menentukan alamat IP mana saja yang diizinkan untuk mengakses layanan tersebut. Anda bisa memasukkan satu alamat IP (`192.168.1.10`) atau seluruh _subnet_ (`192.168.1.0/24`).
        

#### Melalui CLI (Command Line Interface)

1. Buka **Terminal** di WinBox atau sambungkan melalui SSH.
    
2. **Untuk melihat daftar layanan**:
    
    ```
    /ip service print
    ```
    
3. **Untuk menonaktifkan layanan Telnet**:
    
    ```
    /ip service disable telnet
    ```
    
4. **Untuk mengaktifkan layanan WinBox**:
    
    ```
    /ip service enable winbox
    ```
    
5. **Untuk mengubah port layanan SSH**:
    
    ```
    /ip service set ssh port=2222
    ```
    
6. **Untuk membatasi akses layanan WinBox hanya dari subnet `192.168.1.0/24`**:
    
    ```
    /ip service set winbox address=192.168.1.0/24
    ```
    

---

### Praktik Terbaik untuk Keamanan

- **Nonaktifkan Layanan yang Tidak Digunakan**: Matikan semua layanan yang tidak Anda perlukan, seperti Telnet dan FTP, untuk mengurangi potensi serangan.
    
- **Ubah Port Default**: Ubah nomor port default untuk layanan yang tetap aktif (seperti SSH) untuk mempersulit serangan otomatis.
    
- **Batasi Akses**: Gunakan opsi **`Available From`** untuk membatasi akses ke layanan-layanan penting hanya dari alamat IP yang Anda percaya. Ini adalah salah satu cara paling efektif untuk melindungi router Anda.
    

Dengan mengelola layanan secara proaktif, Anda tidak hanya meningkatkan keamanan, tetapi juga memastikan router Mikrotik Anda berjalan dengan lebih efisien dan terlindungi dari ancaman luar.

---

## Mengelola Pencadangan Konfigurasi

Mengelola pencadangan (backup) konfigurasi adalah praktik penting untuk melindungi router Mikrotik Anda dari kegagalan yang tidak terduga atau kesalahan konfigurasi. Dengan memiliki salinan cadangan, Anda dapat dengan cepat mengembalikan router ke kondisi kerja yang stabil jika terjadi masalah.

---

### Menyimpan dan Mengembalikan Pencadangan

Ada dua jenis file yang dapat Anda gunakan untuk pencadangan di RouterOS. Keduanya memiliki fungsi yang berbeda.

#### **File Backup (`.backup`)**

Ini adalah salinan biner (binary) dari seluruh konfigurasi router. File ini mencakup semua pengaturan, mulai dari IP address, aturan firewall, hingga kata sandi. File ini **hanya dapat dikembalikan ke router yang sama atau router dengan model dan versi RouterOS yang identik**.

- **Menyimpan File Backup**:
    
    - **Di WinBox**: Masuk ke menu **Files**, lalu klik **`Backup`**. Beri nama pada file, dan klik **`Backup`** lagi. File ini akan tersimpan di memori internal router. Anda harus mengunduhnya ke komputer Anda untuk disimpan dengan aman.
        
    - **Di CLI**: Gunakan perintah ``/system backup save name=nama_file_backup`misalnya:`/system backup save name=konfigurasi-aman`.
        
- **Mengembalikan File Backup**:
    
    - **Di WinBox**: Unggah file `.backup` ke folder **Files** di router. Lalu, klik **`Restore`** dan pilih file yang ingin Anda pulihkan. Router akan otomatis _reboot_ untuk menerapkan konfigurasi.
        
    - **Di CLI**: Gunakan perintah `/system backup load name=nama_file_backup`.
        

#### **File Ekspor (`.rsc`)**

File ekspor adalah salinan teks (text) dari konfigurasi router dalam format skrip yang bisa dibaca manusia. File ini berisi semua perintah CLI yang diperlukan untuk membangun kembali konfigurasi dari awal.

- **Menyimpan File Ekspor**:
    
    - **Di WinBox**: Masuk ke **New Terminal** dan ketik `export file=nama_file_ekspor`. File `.rsc` akan tersimpan di folder **Files**.
        
    - **Di CLI**: Gunakan perintah `export file=konfigurasi-ekspor-aman`.
        
- **Mengembalikan File Ekspor**:
    
    - Unggah file `.rsc` ke folder **Files** di router.
        
    - **Di CLI**: Ketik perintah `import nama_file_ekspor.rsc` di Terminal.
        

---

### Perbedaan Antara File Backup dan File Ekspor

|Fitur|File Backup (`.backup`)|File Ekspor (`.rsc`)|
|---|---|---|
|**Format**|Biner (Binary)|Teks (Text)|
|**Isi**|Seluruh konfigurasi, termasuk sandi dan identitas|Semua perintah CLI konfigurasi|
|**Portabilitas**|**TIDAK** portabel; hanya untuk model router dan versi RouterOS yang sama.|**Portabel**; dapat digunakan di model router yang berbeda atau diubah secara manual.|
|**Kemudahan Edit**|**TIDAK** bisa diedit secara manual.|**Bisa diedit** menggunakan editor teks.|

---

### Mengedit File Ekspor

Karena file ekspor (`.rsc`) adalah file teks, Anda dapat mengeditnya dengan mudah menggunakan editor teks apa pun (seperti Notepad, Notepad++, atau Visual Studio Code) di komputer Anda.

- **Skenario Penggunaan**:
    
    - **Migrasi Konfigurasi**: Anda dapat mengubah konfigurasi IP address atau nama antarmuka sebelum mengunggahnya ke router lain.
        
    - **Memperbaiki Kesalahan**: Jika ada kesalahan kecil dalam konfigurasi, Anda dapat mengedit file `.rsc` alih-alih mengetik ulang semua perintah.
        
    - **Otomatisasi**: File ini adalah skrip yang bisa Anda modifikasi untuk membuat konfigurasi dasar dan menggunakannya di banyak router.
        

Setelah Anda selesai mengedit file `.rsc`, Anda dapat mengunggahnya kembali ke router dan menjalankan perintah `import` untuk menerapkan perubahan. Ini memberikan fleksibilitas dan kontrol yang jauh lebih besar dibandingkan dengan file backup.

---

## Reset Prangkat RouterOS

Mereset perangkat RouterOS adalah langkah yang sering diperlukan, baik untuk mengembalikan konfigurasi ke pengaturan pabrik, mengatasi masalah yang tidak bisa diselesaikan, atau ketika Anda ingin memulai konfigurasi dari awal. Ada beberapa cara untuk mereset perangkat Mikrotik, dan setiap metode memiliki kegunaan yang berbeda.

---

### Metode Mereset Perangkat

Berikut adalah cara-cara umum untuk mereset perangkat RouterOS, dari yang paling sederhana hingga yang paling ekstrem:

#### 1. Melalui Perangkat Lunak (Software Reset)

Ini adalah cara yang paling sering digunakan dan disarankan jika Anda masih bisa mengakses router.

- **Tujuan**: Mengembalikan semua pengaturan ke kondisi awal pabrik, kecuali jika Anda memilih untuk tidak menghapus konfigurasi default.
    
- **Cara Reset**:
    
    - **Melalui WinBox/WebFig**: Buka menu **System > Reset Configuration**. Di sana, Anda bisa mencentang opsi **`No Default Configuration`** jika Anda ingin menghapus semua konfigurasi, termasuk yang bawaan. Setelah itu, klik **`Reset Configuration`**. Router akan secara otomatis memulai ulang.
        
    - **Melalui CLI**: Gunakan perintah berikut:
        
        ```
        /system reset-configuration
        ```
        
        Jika Anda ingin menghapus semua konfigurasi tanpa menyertakan konfigurasi bawaan, tambahkan opsi `no-defaults=yes`:
        
        ```
        /system reset-configuration no-defaults=yes
        ```
        

#### 2. Melalui Tombol Reset (Hardware Reset)

Jika Anda tidak dapat mengakses router secara fisik atau _software_ mengalami masalah, Anda bisa menggunakan tombol fisik yang ada pada RouterBOARD.

- **Tujuan**: Menghapus semua konfigurasi dan mengembalikan router ke pengaturan default pabrik.
    
- **Cara Reset**:
    
    1. Cabut kabel power dari router.
        
    2. Tekan dan tahan tombol **`Reset`** yang biasanya berada di bagian belakang atau samping perangkat.
        
    3. Saat tombol reset masih ditekan, sambungkan kembali kabel power.
        
    4. Tunggu hingga LED berkedip (sekitar 5-10 detik), lalu lepaskan tombol reset.
        

#### 3. Melalui Netinstall

Ini adalah metode terakhir dan paling ekstrem yang digunakan untuk menginstal ulang RouterOS dari awal. Ini berguna saat router mengalami masalah _firmware_, _bootloop_, atau ketika kedua metode di atas tidak berhasil.

- **Tujuan**: Menginstal ulang RouterOS dan _firmware_ RouterBOOT secara total, menghapus semua konfigurasi yang ada.
    
- **Cara Reset**:
    
    1. Unduh aplikasi **Netinstall** dan file RouterOS dari situs resmi Mikrotik.
        
    2. Hubungkan komputer ke router melalui kabel Ethernet.
        
    3. Jalankan Netinstall, dan Netinstall akan mendeteksi perangkat.
        
    4. Pilih file RouterOS yang ingin diinstal dan ikuti petunjuk yang ada di Netinstall.
        

### Peringatan Penting

Sebelum melakukan reset, sangat disarankan untuk membuat salinan cadangan konfigurasi Anda. Setelah reset, semua pengaturan, termasuk nama pengguna, kata sandi, dan IP address, akan hilang, dan Anda harus mengonfigurasi router dari awal.

---

## Menginstal Ulang Perangkat RouterOS (Netinstall)

**Netinstall** adalah utilitas Windows yang dirancang oleh Mikrotik untuk menginstal atau menginstal ulang RouterOS pada perangkat RouterBOARD melalui jaringan. Netinstall adalah "solusi terakhir" yang sangat berguna saat router tidak dapat diakses melalui WinBox atau metode lain, misalnya karena konfigurasi yang rusak, _firmware_ yang korup, atau _bootloop_.

---

### Kapan Menggunakan Netinstall?

Anda harus menggunakan Netinstall jika Anda menghadapi salah satu masalah berikut:

- **Router tidak bisa _boot_ dengan benar** dan terus-menerus _restart_.
    
- **Konfigurasi hilang atau rusak total** dan tidak bisa diperbaiki.
    
- **Tidak bisa mengakses router** melalui WinBox atau CLI karena kesalahan konfigurasi atau lupa kata sandi.
    
- **Melakukan instalasi bersih** (clean install) untuk memastikan tidak ada konfigurasi lama yang tersisa.
    

---

### Cara Menggunakan Netinstall

Berikut adalah langkah-langkah terperinci untuk menginstal ulang RouterOS menggunakan Netinstall:

#### 1. Persiapan

- **Unduh Netinstall**: Unduh aplikasi Netinstall dari situs resmi Mikrotik. Pastikan versi Netinstall yang Anda unduh sesuai dengan versi RouterOS yang ingin Anda instal.
    
- **Unduh File RouterOS**: Unduh file paket utama (`.npk`) dari situs Mikrotik. Jika Anda ingin menginstal ulang, sebaiknya unduh paket `all_packages` untuk memastikan semua fitur tersedia.
    
- **Siapkan Komputer**: Atur IP address statis pada komputer Anda, misalnya `192.168.88.2`. Pastikan tidak ada firewall yang memblokir Netinstall di komputer Anda.
    

#### 2. Menghubungkan Perangkat

- Hubungkan kabel Ethernet dari komputer Anda langsung ke port **`ether1`** (port pertama) pada RouterBOARD. Jangan hubungkan kabel internet atau perangkat lain.
    
- Tekan dan tahan tombol **`reset`** atau **`reset` + **`boot`** (tergantung model) pada RouterBOARD, lalu sambungkan kabel power.
    
- Tunggu sampai Netinstall mendeteksi perangkat. Jika berhasil, perangkat akan muncul di daftar perangkat Netinstall.
    

#### 3. Proses Instalasi

- Di Netinstall, Anda akan melihat perangkat RouterBOARD yang terdeteksi.
    
- Klik tombol **`Browse`** dan arahkan ke folder tempat Anda menyimpan file `.npk` RouterOS yang sudah diunduh.
    
- Pilih perangkat RouterBOARD di daftar, lalu klik tombol **`Install`**.
    
- Netinstall akan mengirim file RouterOS ke perangkat dan memulai proses instalasi. Ini akan memakan waktu beberapa menit.
    
- Setelah instalasi selesai, perangkat akan _restart_ secara otomatis.
    
- Setelah router berhasil menyala, Anda bisa mencabut kabel power, lalu menghubungkannya lagi. Sekarang, router sudah bersih dan siap untuk dikonfigurasi ulang.
    

Netinstall adalah alat yang sangat penting dalam "senjata" seorang administrator Mikrotik. Ini memungkinkan Anda untuk mengatasi masalah yang paling parah dan mengembalikan perangkat Anda ke kondisi yang berfungsi dengan cepat.

---

## Lisensi RouterOS

RouterOS menggunakan skema lisensi yang berbeda-beda untuk mengontrol fitur dan kemampuan perangkat.1 Lisensi ini terikat pada perangkat keras dan biasanya bersifat **seumur hidup** dan tidak perlu diperbarui.

---

### Tingkat Lisensi RouterOS

Secara umum, ada enam tingkat lisensi RouterOS, dari Level 0 hingga Level 6.2 Perbedaan utama antara setiap level adalah batasan pada fitur-fitur tertentu.

- **Level 0 (Trial)**: Ini adalah lisensi uji coba yang didapat saat Anda pertama kali menginstal RouterOS pada PC x86 atau virtual machine. Semua fitur tersedia, tetapi lisensi ini hanya berlaku selama **24 jam**.3 Setelah itu, Anda harus membeli lisensi atau menggunakan Level 1 (demo).
    
- **Level 1 (Free Demo)**: Lisensi ini gratis, tetapi sangat terbatas.4 Anda bisa menggunakannya tanpa batas waktu, tetapi fitur-fitur penting seperti wireless AP, routing, dan Hotspot tidak tersedia. Ini cocok untuk sekadar pengujian dasar atau demo.
    
- **Level 3 (WISP CPE)**: Lisensi ini biasanya sudah terpasang pada perangkat RouterBOARD yang berfungsi sebagai _wireless client_ atau CPE (Customer Premise Equipment).5 Fitur utamanya adalah kemampuan untuk bertindak sebagai _wireless client_ dan _bridge_, tetapi tidak dapat menjadi _wireless Access Point_ (AP).6
    
- **Level 4 (WISP)**: Ini adalah lisensi yang paling umum untuk perangkat router Mikrotik kelas bawah dan menengah.7 Dibandingkan dengan Level 3, Level 4 menambahkan kemampuan untuk beroperasi sebagai **Wireless Access Point (AP)** dan mendukung jumlah pengguna Hotspot yang lebih banyak (hingga 200 pengguna aktif).8
    
- **Level 5 (WISP)**: Lisensi ini meningkatkan batasan dari Level 4, terutama untuk jumlah pengguna Hotspot (hingga 500 pengguna aktif) dan sesi VPN.9 Biasanya digunakan untuk perangkat kelas menengah ke atas yang menangani jaringan dengan skala lebih besar.10
    
- **Level 6 (Controller)**: Ini adalah lisensi tertinggi dengan semua fitur dan batasan **tidak terbatas**.11 Lisensi ini biasanya ada pada perangkat _high-end_ Mikrotik, seperti seri CCR (Cloud Core Router), dan cocok untuk penggunaan pada skala besar seperti di Internet Service Provider (ISP) atau pusat data.12
    

Setiap RouterBOARD Mikrotik yang Anda beli sudah dilengkapi dengan lisensi bawaan (biasanya Level 4 atau lebih tinggi).13 Jika Anda ingin menggunakan RouterOS pada PC biasa atau virtual machine, Anda perlu membeli lisensi secara terpisah.

---

## Bonus

Mikrotik menawarkan berbagai sumber daya untuk membantu pengguna, dari pemula hingga ahli, dalam mempelajari dan memecahkan masalah. Sumber-sumber ini sangat penting untuk memaksimalkan penggunaan perangkat Mikrotik Anda.

### Sumber Informasi Tambahan

- **wiki.mikrotik.com**: Ini adalah ensiklopedia online resmi yang berisi dokumentasi lengkap tentang semua aspek RouterOS, RouterBOARD, dan fitur-fitur lainnya. Wiki ini adalah sumber daya paling utama untuk mencari informasi teknis, panduan konfigurasi, dan contoh-contoh skrip.
    
- **forum.mikrotik.com**: Forum ini adalah tempat komunitas pengguna Mikrotik berinteraksi. Anda dapat mengajukan pertanyaan, berbagi pengetahuan, dan mencari solusi untuk masalah yang dihadapi. Forum ini sangat aktif dan seringkali menjadi tempat yang baik untuk mendapatkan bantuan dari sesama administrator jaringan.
    
- **mum.mikrotik.com**: MUM, singkatan dari **Mikrotik User Meeting**, adalah acara konferensi resmi yang diadakan oleh Mikrotik di berbagai negara. Situs web ini berisi jadwal acara, materi presentasi, dan video dari MUM sebelumnya. Menghadiri MUM adalah cara yang bagus untuk belajar langsung dari para ahli dan mendapatkan informasi terbaru tentang produk Mikrotik.
    
- **Distributor dan Dukungan Konsultan**: Di setiap negara, Mikrotik memiliki distributor resmi dan konsultan tersertifikasi. Mereka dapat memberikan dukungan teknis, pelatihan, dan layanan konfigurasi. Ini adalah opsi yang bagus jika Anda membutuhkan bantuan yang lebih personal dan profesional.
    
- **support@mikrotik.com**: Untuk masalah teknis yang spesifik dan tidak dapat diselesaikan melalui forum atau wiki, Anda dapat menghubungi tim dukungan resmi Mikrotik melalui email ini. Pastikan untuk memberikan informasi yang sejelas mungkin, termasuk versi RouterOS, model perangkat, dan deskripsi masalah secara rinci.
    

Dengan memanfaatkan sumber-sumber ini, Anda dapat memperluas pengetahuan Anda tentang Mikrotik dan memastikan perangkat jaringan Anda beroperasi dengan optimal.