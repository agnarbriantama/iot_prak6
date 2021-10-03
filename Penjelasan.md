Pada praktikum kali ini, kita belajar keamanan data iot. untuk mengamankan data kita menggunakan wpa2 enterprise.
device yang saya gunakan yaitu 1 server,1 switch,1 router, 1 sensor motion, 1 pc,1 kipas, 1 garasi dan 1 jendela.
Untuk mengkoneksikan iot dengan router , kita setting di router ip addressnya sebagai gateway yaitu 192.168.0.1 alu psetting pada wireless ssid nya dan security modenya menggunakan wpa2 enterprise.
kemudian pada server kita ke ip config masukkan ip addres 192.168.0.10 dan gateway nya yang seperti di router.
kemudian kita masuk ke service lalu ke AAA lalu setting client name,secret dan client ip
kemudian masukkan username dan password untuk masing-masing device. Ini untuk keamanan wifi tiap iot
lalu masuk ke device dan ke wireless lalu pilih wpa2 kemudian masukkan username password yang telah dibuat tadi.
Setelah terhubung kita masuk ke web browser dari pc lalu masukkan ip addres server dan login.
setting home device di condition
untuk hasil running, jika sensor motion mendeteksi  ada gerakan maka jendela akan terbuka,kipas menyala dan garasi terbuka
