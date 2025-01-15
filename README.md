# SIMULASI_UAS
Elemen Utama dalam Topologi
Router Utama:

Terdapat tiga router utama di tiga lokasi berbeda yang dihubungkan ke internet melalui jalur WAN.
Router ini bertindak sebagai gateway untuk masing-masing jaringan lokal.
Switch:

Switch digunakan untuk mendistribusikan koneksi jaringan di dalam bangunan, termasuk ke perangkat seperti PC, server, dan access point.
Access Point:

Digunakan untuk memberikan konektivitas nirkabel (Wi-Fi) kepada perangkat pengguna, seperti laptop dan smartphone.
Lab Switch dan PC Lab:

Setiap lokasi memiliki switch khusus untuk jaringan laboratorium komputer, yang menghubungkan PC di lab.
Firewall dan Core Switch:

Firewall digunakan untuk melindungi jaringan dari ancaman eksternal.
Core Switch adalah pusat distribusi utama untuk seluruh koneksi dalam bangunan.
Rincian Koneksi
Bangunan KCR:

IP jaringan lokal: 10.2.10.0/24.
Terdapat Lab Switch yang menghubungkan PC di laboratorium.
Access point memberikan konektivitas Wi-Fi di area ini.
Bangunan KBJ:

IP jaringan lokal: 10.1.10.0/24.
Dilengkapi dengan DMZ-Switch untuk server.
Firewall melindungi jaringan lokal sebelum data diteruskan ke Core Switch.
Bangunan KHI:

IP jaringan lokal: 10.3.10.0/24.
Memiliki Lab Switch untuk PC di laboratorium.
Access point menyediakan akses Wi-Fi.
Koneksi Antar Bangunan
Ketiga bangunan terhubung melalui router masing-masing menggunakan jaringan WAN.
Jalur koneksi antar router menggunakan subnet khusus (10.254.254.0/30) untuk komunikasi antar lokasi.
Fungsi Utama Elemen
Core Switch: Mengelola lalu lintas jaringan internal setiap bangunan.
Firewall: Menjaga keamanan jaringan lokal dari ancaman eksternal.
Access Point: Memungkinkan pengguna mengakses internet melalui jaringan Wi-Fi.
Router WAN: Menghubungkan jaringan lokal (LAN) ke internet dan jaringan bangunan
