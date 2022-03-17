**SehatinAja**

SehatinAja dapat diakses pada link berikut: <http://sehatinaja.herokuapp.com>

![Graphical user interface, application Description automatically
generated](media/cbe222d62fc6722427cf2eca09bebdde.jpeg)Prosedur penggunaan dan
cara kerja aplikasi berbasis *website* untuk menjual produk gaya hidup sehat
“SehatinAja” adalah sebagai berikut:

###### **Tampilan Aplikasi Halaman Register**

Untuk melakukan transaksi pembelian produk di situs web SehatinAja, *customer*
wajib melakukan registrasi akun terlebih dahulu di halaman *register* apabila
belum memiliki akun. Pada halaman *register* ini, pengguna diminta untuk
memasukkan nama pengguna, nomor telepon, *email*, *password,* konfirmasi
*password*, alamat dan kota pengguna. Pendaftaran akun pada halaman *register*
ini hanya berlaku untuk pendaftaran akun *customer*, sedangkan untuk pendaftaran
akun *supplier* dilakukan oleh pihak admin SehatinAja. Setelah pengguna berhasil
melakukan registrasi akun sebagai *customer*, pengguna secara automatis akan
diarahkan menuju halaman verifikasi *email*. Sistem akan mengirimkan *link*
verifikasi ke *email* yang telah didaftarkan dan pengguna harus melakukan
verifikasi *email* agar akun tersebut dapat terverifikasi. Setelah pengguna
melakukan verifikasi *email*, pengguna akan diarahkan ke halaman utama situs web
SehatinAja.

![Graphical user interface, application Description automatically
generated](media/8c7bb6e4c1ab3885b9145ce6ee1e02ed.jpeg)

###### **Tampilan Aplikasi Halaman Login**

###### 

Apabila pengguna sudah memiliki akun pada situs web SehatinAja, pengguna dapat
melakukan *login* agar dapat mengakses fitur pembelian produk. Pada halaman
*login* ini, pengguna diminta untuk memasukkan *email* dan *password* yang telah
didaftarkan sebelumnya. Untuk pengguna dengan *role supplier* yaitu pihak yang
melakukan penjualan produk, data *email* dan *password* akan diberikan oleh
pihak admin SehatinAja sesuai dengan data yang telah didaftarkan. Setelah
pengguna berhasil *login*, maka secara automatis sistem akan mengarahkan ke
halaman verifikasi email jika akun belum terverifikasi. Apabila email sudah
terverifikasi sebelumnya, sistem akan mengarahkan ke halaman utama situs web
SehatinAja.

![Graphical user interface, application Description automatically
generated](media/2780dd963a1a892e741b2c79d9ea1190.jpeg)

###### **Tampilan Aplikasi Halaman Lupa Password**

Ketika *user* tidak dapat mengingat *password* pada akun yang telah didaftarkan,
situs web SehatinAja memiliki fitur lupa *password* untuk menghapus *password*
lama dan membuat *password* baru. Untuk mengakses fitur tersebut, pengguna dapat
menekan tombol “Lupa kata sandi?” pada halaman *login*. Ketika pengguna menekan
tombol tersebut, sistem akan mengarahkan pengguna ke halaman lupa *password*.
Pengguna akan diminta untuk memasukkan *email* yang terdaftar. Setelah pengguna
berhasil memasukkan *email*, sistem akan mengirimkan *email* berisi *link* untuk
mengubah *password*.

![Graphical user interface, text, application, chat or text message Description
automatically generated](media/f122a139e9f3183878cdaf33eeca079e.jpeg)

###### **Tampilan Aplikasi Halaman Ubah Password**

Pada halaman ubah *password*, pengguna harus mengisi *form* untuk mengubah
*password*. Pengguna akan diminta untuk memasukkan *email, password* baru dan
konfirmasi *password* baru. Untuk *password* yang dimasukkan harus berisi 1
huruf kecil dan besar, 1 angka, 1 karakter spesial (seperti !@\#\$%&\*()?) dan
minimal 8 karakter. Apabila data yang dimasukkan valid, pengguna akan diarahkan
ke halaman utama situs web SehatinAja.

![](media/f197a59cf6ee434a3e51c105af883ae7.jpeg)

###### **Tampilan Navigation Bar Aplikasi (Guest)**

Gambar diatas merupakan tampilan dari *navigation bar* situs web SehatinAja
apabila pengguna belum melakukan *login* atau disebut sebagai *guest.* Pada
aplikasi ini, *guest* dapat mengakses fitur lihat produk dan artikel tetapi
tidak dapat melakukan transaksi pembelian produk. *Guest* juga dapat melakukan
pencarian produk.

![](media/1c66ecd9f4ae37f602a39871aab146f7.jpeg)

###### **Tampilan Navigation Bar Aplikasi (Customer)**

Gambar diatas merupakan tampilan dari *navigation bar* situs web SehatinAja
apabila pengguna sudah melakukan *login* untuk *role customer.* Pada aplikasi
ini, *customer* dapat mengakses fitur lihat produk dan artikel dan juga dapat
melakukan transaksi pembelian produk. Selain pembelian produk, *customer* juga
dapat melihat riwayat transaksi pada *icon shopping-bag* dan keranjang pada icon
troli.

![Graphical user interface, text, application, chat or text message Description
automatically generated](media/8236859cd3103529251b302674805fd0.jpeg)

###### **Tampilan Menu Dropdown Profile (Customer)**

Gambar diatas merupakan tampilan menu *dropdown* profil untuk *customer* yang
berisi tombol untuk ke halaman ubah profil dan keluar dari akun di situs web
SehatinAja.

![Graphical user interface, text, application, chat or text message Description
automatically generated](media/f98fa0c4de1f3a131bcbc4b0de73f247.jpeg)

###### **Tampilan Menu Dropdown Profile (Supplier)**

Gambar diatas merupakan tampilan menu *dropdown* profil untuk *supplier* yang
berisi tombol edit profil dan melihat profile dari *supplier* tersebut. Selain
itu, juga terdapat tombol untuk keluar dari akun *supplier* di situs web
SehatinAja.

![Graphical user interface, application Description automatically
generated](media/fac46d6b6764037b4e9b8167ddbaff1a.jpeg)

###### **Tampilan Aplikasi Halaman Mengubah Profil (Customer)**

Gambar di atas merupakan tampilan dari halaman untuk mengubah profil *customer*.
Pada halaman ini, *customer* dapat mengubah nama pengguna, nomor telepon, hingga
foto. Untuk mengubah alamat dan *email*, *customer* dapat menekan tombol ubah
yang terletak di samping *field* alamat dan *email*. Apabila *customer* telah
selesai melakukan pengubahan data profil, *customer* dapat menekan tombol simpan
agar sistem dapat menyimpan perubahan data tersebut ke database.

![Graphical user interface Description automatically generated with medium
confidence](media/7b8557c4047bfeff7de0ad6f6184c677.png)

###### **Tampilan Aplikasi Halaman Mengubah Profil (Supplier)**

Gambar di atas merupakan tampilan dari halaman untuk mengubah profil *supplier*.
Pada halaman ini, *supplier* dapat mengubah nama toko, nomor telepon, deskripsi,
alamat, kota, hingga foto. Untuk mengubah domain toko dan *email*, *supplier*
dapat menekan tombol ubah yang terletak di samping *field* domain toko dan
*email*. Apabila *supplier* telah selesai melakukan pengubahan data profil,
*supplier* dapat menekan tombol simpan agar sistem dapat menyimpan perubahan
data tersebut ke database.

![Graphical user interface, application Description automatically generated with
medium confidence](media/0ac3d7ab30b9fa0a52059bb3773bd309.jpeg)

###### **Tampilan Aplikasi Footer**

Gambar di atas merupakan tampilan dari *footer* situs web SehatinAja. Pada
*footer* tersebut terdapat beberapa *link* untuk ke halaman tentang kami,
bantuan *customer*, syarat dan ketentuan, kebijakan dan privasi, hingga
pengiriman. Selain itu, juga terdapat *list* *supplier* yang terdapat pada situs
web SehatinAja, nomor *customer service*, alamat hingga media sosial yang
dimiliki oleh SehatinAja. *Footer* tersebut digunakan di seluruh halaman situs
web SehatinAja agar dapat memudahkan *customer* maupun *supplier* dalam beberapa
hal seperti jika ingin menghubungi *customer service* ataupun bantuan
*customer.*

*![Graphical user interface, application, website Description automatically
generated](media/542a896f89f6b27d76b87cc7ef00e00e.png)*

###### **Tampilan Aplikasi Halaman Utama (Guest)**

Gambar diatas merupakan tampilan dari halaman utama untuk pengguna yang tidak
melakukan *login*. Pada halaman tersebut memiliki *carousel* yang berisi
*banner* untuk iklan, hingga promosi, *list* dari kategori produk, *list* produk
terbaru, dan yang terlaris. Apabila pengguna ingin melihat detail dari produk
terkait, pengguna dapat menekan tombol lihat detail dan pengguna akan diarahkan
ke halaman produk detail.

![Graphical user interface, application, website Description automatically
generated](media/f1c3a2bcc49d3e934d0f6684aa2cc62f.png)

###### **Tampilan Aplikasi Halaman Utama (Customer)**

Gambar diatas merupakan tampilan dari halaman utama untuk *customer*. Pada
halaman tersebut memiliki *carousel* yang berisi *banner* untuk iklan, hingga
promosi, *list* tombol untuk menuju ke halaman riwayat transaksi dengan status
menunggu pembayaran, transaksi berlangsung dan semua transaksi, *list* dari
kategori produk, *list* produk terbaru, dan yang terlaris. Apabila pengguna
ingin melihat detail dari produk terkait, pengguna dapat menekan tombol lihat
detail dan pengguna akan diarahkan ke halaman produk detail.

![Graphical user interface, table Description automatically generated with
medium confidence](media/965b058bbdd5c7f69a2d587beac984d4.png)

###### **Tampilan Aplikasi Halaman Dashboard Supplier**

Ketika *supplier* berhasil melakukan *login*, sistem akan menampilkan halaman
*dashboard* seperti pada gambar di atas. Pada halaman tersebut berisi diagram
yang menampilkan total penjualan produk per bulan di tahun 2022, dan daftar
transaksi yang sedang berlangsung hingga telah selesai. Pada tabel daftar
transaksi tersebut terdapat id transaksi, barang yang dibeli beserta harga dan
kuantitas, pendapatan dari transaksi tersebut, status pembayaran, status
transaksi, nomor resi, tanggal pembelian dan kolom yang berisi beberapa tombol
untuk mengubah status dari transaksi yang dilakukan. Pada kolom atur terdapat
beberapa tombol diantaranya untuk mengubah status transaksi menjadi dikemas dan
dikirim, pembatalan transaksi dan tombol untuk memasukkan nomor resi. *Supplier*
juga dapat melakukan *filtering* untuk status transaksi dengan menekan dan
memilih status pada tombol *dropdown* disamping teks “Daftar Transaksi”. Ketika
*supplier* melakukan *filtering¸* tabel hanya akan menampilkan data dengan
status transaksi yang dipilih.

![Graphical user interface, application Description automatically
generated](media/6a318299deb968f1f540ea0af0020966.jpeg)![Graphical user
interface, application, Teams Description automatically
generated](media/8c4291c01b510c112c4857fdfc8c5455.png)

###### **Tampilan Aplikasi Halaman Pencarian Produk dan Filtering**

Ketika pengguna melakukan pencarian produk pada kolom *search* yang terletak di
*navigation bar* situs web SehatinAja dan menekan “Enter” pada *keyboard* atau
tombol *search*, sistem akan menampilkan *list* produk yang dicari pengguna dan
kolom *filtering*. Pada halaman tersebut juga memiliki kolom *filtering* untuk
mencari produk dengan kondisi tertentu. *Filter* tersebut diantaranya nutrisi,
penyakit, kategori, lokasi, harga, hingga *rating*. Apabila pengguna ingin
melakukan *filtering,* pengguna dapat menekan *checkbox* yang terletak disamping
list dari *filter* yang diinginkan. Kemudian, pengguna dapat menekan tombol
tambah. Sistem akan menampilkan *list* produk dengan *filter* yang dimasukkan
pengguna. Apabila pengguna ingin melihat detail dari produk terkait, pengguna
dapat menekan tombol lihat detail dan pengguna akan diarahkan ke halaman produk
detail.

![Graphical user interface, text, application, chat or text message Description
automatically generated](media/c94ef7de46c13850fb081e8586e5677b.jpeg)

###### **Tampilan Aplikasi Menu Dropdown Kategori Produk**

Gambar di atas merupakan tampilan dari menu *dropdown* yang berisi tombol list
kategori produk. Kategori yang terdapat pada situs web SehatinAja yaitu
diantaranya alat kesehatan, makanan dan minuman, olahraga, perawatan diri,
vitamin dan herbal. Ketika pengguna menekan salah satu tombol, pengguna akan
diarahkan ke halaman kategori detail yang dipilih.

![Graphical user interface, application Description automatically
generated](media/7dcd944fb924962fcd1dd71927c20da7.png)

###### **Tampilan Aplikasi Halaman Kategori Produk**

Gambar diatas merupakan tampilan halaman kategori produk. Pada halaman ini
berisi foto, deskripsi singkat dan *list* produk yang termasuk dalam kategori
tersebut. Apabila pengguna ingin melihat detail dari produk terkait, pengguna
dapat menekan tombol lihat detail dan pengguna akan diarahkan ke halaman produk
detail.

###### ![Graphical user interface Description automatically generated](media/3ec0ef0c2f600acdb72c2d6c4f45e7aa.png)**Tampilan Aplikasi Halaman Detail Produk serta Penilaian dan Ulasan Produk**

Gambar diatas merupakan tampilan dari halaman detail produk yang berisi foto,
nama, kategori, harga, deskripsi, berat, kandungan gizi, jumlah ulasan, dan
total penjualan produk. Selain itu juga terdapat detail *supplier* diantaranya
nama, alamat, nomor telepon dan *email* *supplier* terkait. Pada halaman ini
juga terdapat tampilan penilaian dan ulasan yang diberikan oleh *customer* yang
pernah membeli produk tersebut. Pada kolom penilaian terdapat nama, penilaian
dalam bentuk ikon bintang dan teks, tanggal pembelian, dan ulasan yang
diberikan. Lalu, untuk melakukan *filtering* dengan penilaian tertentu, pengguna
dapat menekan salah satu tombol pada list tombol yang terdapat diatas kolom
penilaian. Apabila pengguna ingin melakukan pengubahan penilaian dan ulasan,
pengguna dapat menekan tombol ubah di kolom penilaian dan ulasan terkait.
Penilaian dan ulasan hanya dapat diubah satu kali. Sehingga apabila penilaian
dan ulasan sudah diubah, tombol ubah akan hilang dari kolom. Selain itu, apabila
pengguna ingin membeli produk terkait, pengguna dapat memasukkan jumlah produk
yang diinginkan dan menekan tombol keranjang. Kemudian produk akan masuk ke
dalam keranjang.

![Graphical user interface, text, application, chat or text message Description
automatically generated](media/a822c895ca3edfd4b3d3a23290c8e591.jpeg)

###### **Tampilan Aplikasi Ubah Penilaian dan Ulasan**

Kemudian, untuk mengubah penilaian dan ulasan, pengguna dapat menekan tombol
ubah pada kolom penilaian dan ulasan, dan sistem akan menampilan *pop-up* berisi
*form* pengubahan penilaian dan ulasan untuk produk terkait. Pengguna wajib
menekan ikon bintang yang tertera, dan mengisi ulasan produk. Pengguna juga
dapat menambahkan foto produk dalam *form* ini sebanyak tiga foto. Apabila
seluruh kolom sudah diisi, pengguna dapat menekan tombol kirim ulasan.

![Graphical user interface, text Description automatically
generated](media/f00f27dc24a6357e6208d0a0f2a6a4a5.png)

###### **Tampilan Aplikasi Halaman Artikel**

Gambar diatas merupakan tampilan halaman artikel. Pada halaman ini terdapat list
kategori dan artikel yang dibuat oleh pihak admin dan *supplier*. Terdapat dua
list artikel yang diantaranya yaitu artikel terbaru dan terlaris. Untuk kolom
artikel terdapat foto, judul, kategori, deskripsi, dan nama penulis artikel.
Jika pengguna ingin melihat detail dari artikel, pengguna dapat menekan tombol
lihat detail dan sistem akan menampilkan halaman detail artikel terkait.

![Text Description automatically
generated](media/8799aa32539ac97a2a3d4f93b00ff3f0.png)

###### **Tampilan Aplikasi Halaman Detail Artikel**

Gambar diatas merupakan tampilan dari halaman detail artikel. Pada halaman ini
memuat judul, kategori, nama pembuat, tanggal pembuatan, foto terkait, deskripsi
dan produk terkait artikel yang dimuat. Apabila pengguna ingin melihat detail
dari produk terkait, pengguna dapat menekan tombol lihat detail pada list produk
terkait dan pengguna akan diarahkan ke halaman produk detail.

![Graphical user interface, text, application, email Description automatically
generated](media/afd75d4d506875fd41cc6c61d3c10c34.png)

###### **Tampilan Aplikasi Halaman Keranjang**

Gambar diatas merupakan tampilan halaman keranjang. Halaman tersebut memuat
nama, harga, kuantitas, total harga produk dan penjual atau *supplier* dari
produk tersebut. Apabila pengguna ingin mengubah kuantitas dari produk tersebut,
pengguna dapat memasukkan jumlah yang diinginkan dan menekan tombol ubah. Dan
juga apabila pengguna ingin menghapus produk dari keranjang, pengguna dapat
menekan ikon sampah. Apabila ingin melanjutkan pemesana, pengguna dapat
mencentang *checkbox*, lalu menekan tombol *checkout.*

![Graphical user interface Description automatically
generated](media/3ef0eb1fd2b0173101167eac2664eecb.png)

###### **Tampilan Aplikasi Pesan Error pada Halaman Keranjang**

Ketika pengguna melakukan *checkout* dan tidak menekan *checkbox*, sistem akan
menampilkan pesan *error* berupa instruksi untuk mencentang *checkbox* pada
transaksi yang diinginkan.

![Graphical user interface, application Description automatically
generated](media/722122633cf1843c9e4ac3a79e6d2c7e.png)

###### **Tampilan Aplikasi Halaman Checkout**

Pada halaman ini memuat detail pengiriman seperti alamat dan nomor telepon
pengguna, daftar pembelian produk dan metode pembayaran. Apabila pengguna ingin
mengubah alamat utama, pengguna dapat menekan tombol ubah alamat. Sedangkan
apabila pengguna ingin mengubah layanan kurir, pengguna dapat menekan tombol
ubah kurir. Pada halaman ini, pengguna juga dapat memilih metode pembayaran yang
dapat dipilih pada menu *dropdown* dikolom metode pembayaran. Apabila data yang
terisi sudah benar dan sesuai, pengguna dapat menekan tombol buat pesanan untuk
melanjutkan pembayaran produk yang dibeli.

![Graphical user interface Description automatically
generated](media/da2b64f6fa02c895218f3fd1ca97bb32.png)

###### **Tampilan Aplikasi Halaman Manajemen Alamat (Customer)**

Apabila pengguna ingin menambahkan atau mengubah alamat utama, pengguna dapat
menuju ke halaman manajemen alamat. Pada halaman ini, pengguna dapat mengubah
alamat utama, mengubah detail alamat, menambahkan alamat hingga menghapus
alamat. Untuk mengganti alamat utama, pengguna dapat menekan ikon rumah,
sedangkan untuk menghapus alamat pengguna dapat menekan ikon sampah. Kemudian,
sistem akan menampilkan *pop-up* konfirmasi pengubahan atau penghapusan alamat.
Dan untuk mengubah alamat, pengguna dapat menekan ikon *edit* dan pengguna akan
diarahkan ke halaman ubah alamat.

![Graphical user interface, text, application Description automatically
generated](media/3e1c69cb196997b314c32e321a1a27c9.jpeg)

###### **Tampilan Aplikasi Halaman Pilih Kurir dan Layanan (Customer)**

Gambar diatas merupakan tampilan halaman pilih kurir dan layanan. Pada halaman
tersebut menampilkan pilihan kurir yang disediakan oleh situs web SehatinAja
beserta pilihan layanan yang diberikan kurir. Pada setiap pilihan layanan
diberikan keterangan harga dan estimasi produk sampai. Apabila pengguna telah
memilih kurir dan layanan yang diinginkan, pengguna dapat menekana tombol ubah
layanan.

![Graphical user interface, text, application, Teams Description automatically
generated](media/1596b6b37cf736d812bd04b714fb0259.jpeg)

###### **Tampilan Aplikasi Halaman Informasi Pembayaran (Customer)**

Gambar diatas merupakan tampilan halaman informasi pembayaran untuk *customer*.
Pada halaman tersebut memuat kode pembayaran, batas waktu pembayaran berupa
tanggal dan waktu, nomor rekening metode yang dipilih dan jumlah yang harus
dibayar. Pengguna dapat langsung menyalin nomor rekening dengan menekan tombol
salin tanpa harus mengetik nomor yang tertera. Apabila pengguna telah melakukan
pembayaran dan ingin mengunggah bukti pembayaran, pengguna dapat menekan tombol
*upload* bukti pembayaran.

![Graphical user interface, text, application, email Description automatically
generated](media/40de4e2ba50140b24ca3712566016367.jpeg)

###### **Tampilan Aplikasi Halaman Mengunggah Bukti Pembayaran (Customer)**

Gambar diatas merupakan tampilan dari halaman mengunggah bukti pembayaran untuk
*customer*. Halaman tersebut memuat kode pembayaran, bukti pembayaran berupa
file dengan jenis .jpg, .jpeg, .svg atau .png. Ketika pengguna telah memilih
foto bukti pembayaran, sistem akan menampilkan foto tersebut pada halaman ini.
Apabila file yang dimasukkan sudah benar dan sesuai, pengguna dapat menekan
tombol upload bukti pembayaran. Jika file valid, sistem akan menampilkan pesan
sukses berisi “Bukti pembayaran Anda telah berhasil diupload. Mohon menunggu
untuk dikonfirmasi oleh tim kami.”

![Graphical user interface, website Description automatically
generated](media/9ef7bedbe30c4ba974119c7b29c9f06d.png)

###### **Tampilan Aplikasi Halaman Riwayat Pembelian (Customer)**

Gambar diatas merupakan tampilan halaman riwayat pembelian yang dilakukan oleh
*customer*. Pada halaman ini memuat list riwayat pembelian dengan beberapa
status. Pada bagian atas halaman ini terdapat tiga kolom berisi jumlah transaksi
yang belum dibayar, berlangsug dan telah selesai untuk memudahkan penggunanya.
Selain itu, terdapat list tombol untuk *filtering* list riwayat transaksi
berdasarkan statusnya. Ketika pengguna menekan salah satu tombol, list riwayat
transaksi akan berubah berdasarkan status yang dipilih. Pada setiap list
terdapat status transaksi, tanggal pembelian, id transaksi, nama *supplier,*
nama, kuantitas, stok dan harga produk, hingga total pembayaran. Untuk melihat
detail transaksi, pengguna dapat menekan tombol lihat detail transaksi dan
sistem akan menampilkan halaman detail riwayat transaksi.

![Graphical user interface Description automatically
generated](media/5ba221fc731e03d8e94ef1c2a0bcb59b.png)

###### **Tampilan Aplikasi Halaman Detail Pembelian Jika Belum Bayar (Customer)**

Gambar diatas merupakan tampilan halaman detail pembelian jika *customer* belum
melakukan pembayaran. Pada halaman ini menampilkan status transaksi, tanggal
pembelian, info pengiriman berupa order id, kurir, berat, nomor resi, alamat
penerima dan pengirim. Selain itu, juga terdapat detail produk seperti nama
*supplier* atau penjual produk, nama produk, kuantitas dan harga produk, dan
juga terdapat total harga, ongkos kirim dan total keseluruhan pembayaran.
Apabila pengguna ingin melakukan pembayaran, pengguna dapat menekan tombol bayar
sekarang untuk menuju ke halaman pembayaran. Jika pengguna ingin membatalkan
pesanan, pengguna dapat menekan tombol batalkan pesanan.

![Graphical user interface Description automatically
generated](media/24a2a1bc665b7705300a2b1ecbb930ed.png)

###### **Tampilan Aplikasi Halaman Detail Pembelian Jika Sudah Bayar, Dikemas, Dibatalkan, atau Dikirim (Customer)**

Gambar diatas merupakan tampilan halaman detail pembelian jika *customer* sudah
melakukan pembayaran, produk telah dikemas, dibatalkan atau dikirim. Pada
halaman ini menampilkan status transaksi, tanggal pembelian, info pengiriman
berupa order id, kurir, berat, nomor resi, alamat penerima dan pengirim. Selain
itu, juga terdapat detail produk seperti nama *supplier* atau penjual produk,
nama produk, kuantitas dan harga produk, dan juga terdapat total harga, ongkos
kirim dan total keseluruhan pembayaran. *Customer* tidak dapat membatalkan
transaksi dengan status sudah bayar, dikemas, ataupun dikirim, sehingga pada
halaman ini tidak memiliki tombol batalkan pesanan.

![Graphical user interface Description automatically
generated](media/d8d031475386897f98fad1478df7cbff.png)

###### **Tampilan Aplikasi Halaman Detail Pembelian Jika Selesai (Customer)**

Gambar diatas merupakan tampilan halaman detail pembelian jika *customer* sudah
melakukan pembayaran, produk telah dikemas, dibatalkan atau dikirim. Pada
halaman ini menampilkan status transaksi, tanggal pembelian, info pengiriman
berupa order id, kurir, berat, nomor resi, alamat penerima dan pengirim. Selain
itu, juga terdapat detail produk seperti nama *supplier* atau penjual produk,
nama produk, kuantitas dan harga produk, dan juga terdapat total harga, ongkos
kirim dan total keseluruhan pembayaran. *Customer* dapat memberikan penilaian
dan ulasan produk yang dibeli dengan menekan tombol beri penilaian untuk menuju
ke halaman ulasan produk.

![Graphical user interface, application, table Description automatically
generated](media/3d2590eac692c5b6a4ebe012f20e9d34.png)

###### **Tampilan Aplikasi Halaman Manajemen Akun (Admin)**

Gambar diatas merupakan tampilan dari halaman manajemen akun oleh admin. Pada
halaman ini, admin dapat menonaktifkan akun, melihat list pengguna baik peran
*customer* maupun *supplier* dan juga dapat menambahkan akun dengan menekan
tombol tambah akun untuk menuju ke halaman tambah akun *supplier*. Halaman ini
juga memiliki *filtering* nama, peran dan juga dapat diurutkan sesuai abjad.
Pada tabel akun tersebut berisi nama akun, peran dan tanggal pembuatan akun,
alamat, nomor telepon, email, dan status keaktifan akun. Untuk menonaktifkan
akun, admin dapat menekan ikon sampah pada kolom atur. Kemudian sistem akan
menampilkan *pop up* konfirmasi nonaktifkan akun. Apabila admin ingin
mengaktifkan kembali akun, admin dapat menekan tombol *undo* pada kolom atur dan
sistem akan menampilkan *pop up* konfirmasi aktifkan kembali akun.

![Graphical user interface, text, application, email Description automatically
generated](media/d235d117b2c944447ad025db8973f304.png)

###### **Tampilan Aplikasi Halaman Manajemen Produk oleh Admin**

Gambar diatas merupakan tampilan dari halaman manajemen produk oleh admin. Pada
halaman ini, admin dapat menonaktifkan produk, melihat list produk dari seluruh
*supplier*. Halaman ini juga memiliki *filtering* nama, kategori produk dan juga
dapat diurutkan sesuai abjad. Pada tabel akun tersebut berisi nama produk,
deskripsi singkat dan tanggal pembuatan produk, penilaian, jumlah produk
terjual, harga, stok dan status keaktifan produk. Untuk menonaktifkan produk,
admin dapat menekan ikon sampah pada kolom atur. Kemudian sistem akan
menampilkan *pop up* konfirmasi nonaktifkan produk. Apabila admin ingin
mengaktifkan kembali produk, admin dapat menekan tombol *undo* pada kolom atur
dan sistem akan menampilkan *pop up* konfirmasi aktifkan kembali produk.

![Graphical user interface, text, application Description automatically
generated](media/ce9db04bbe930fb1e3739b285bda428c.jpeg)

###### **Tampilan Aplikasi Halaman Manajemen Artikel oleh Admin**

Gambar diatas merupakan tampilan dari halaman manajemen artikel oleh admin. Pada
halaman ini, admin dapat menonaktifkan artikel, melihat list artikel dari
seluruh pengguna dan juga dapat menambahkan artikel dengan menekan tombol tambah
artikel untuk menuju ke halaman tambah artikel. Halaman ini juga memiliki
*filtering* judul, kategori dan juga dapat diurutkan sesuai abjad. Pada tabel
artikel tersebut berisi judul, tanggal pembuatan artikel, jumlah klik yang
dilakukan pengguna, cuplikan isi artikel, kategori, dan status keaktifan
artikel. Untuk menonaktifkan artikel, admin dapat menekan ikon sampah pada kolom
atur. Kemudian sistem akan menampilkan *pop up* konfirmasi nonaktifkan artikel.
Apabila admin ingin mengaktifkan kembali artikel, admin dapat menekan tombol
*undo* pada kolom atur dan sistem akan menampilkan *pop up* konfirmasi aktifkan
kembali artikel. Admin juga dapat mengubah artikel yang admin buat dengan
menekan ikon *edit* pada kolom atur untuk menuju ke halaman ubah artikel.

![Graphical user interface, text, email Description automatically
generated](media/017de56f40a23543c841fc382d3c5f10.png)

###### **Tampilan Aplikasi Halaman Manajemen Pembayaran (Admin)**

Gambar diatas merupakan tampilan dari halaman manajemen pembayaran. Pada halaman
ini, admin dapat mengkonfirmasi apakah bukti pembayaran yang diberikan
*customer* valid atau tidak. Halaman ini juga memiliki *filtering* berdasarkan
kode pembayaran dan juga dapat diurutkan sesuai abjad. Pada tabel pembayaran
tersebut berisi nama penjual, pembeli, id, kode, status, jumlah, metode, dan
tanggal pembayaran transaksi. Apabila bukti yang diunggah *customer* valid,
admin dapat melakukan validasi dengan menekan tombol centang. Kemudian sistem
akan menampilkan *pop up* konfirmasi validasi pembayaran, sedangkan apabila
bukti tidak valid, admin dapat menekan tombol batalkan dan sistem akan
menampilkan *pop up* konfirmasi batalkan transaksi.

![A picture containing graphical user interface Description automatically
generated](media/a472e4ecf5f639f9cf7aac785c7d6cf8.jpeg)

###### **Tampilan Aplikasi Halaman Menambah atau Memperbarui Resi (Supplier)**

Ketika *supplier* telah memperbarui status menjadi dikemas, *supplier* harus
menambah atau memperbarui nomor resi pada halaman menambah atau memperbarui
resi. Apabila *supplier* telah mengisi kolom nomor resi, *supplier* dapat
menekan tombol tambah resi untuk melanjutkan ke Proses berikutnya.

![Graphical user interface, text, application Description automatically
generated](media/ce9db04bbe930fb1e3739b285bda428c.jpeg)

###### **Tampilan Aplikasi Halaman Manajemen Artikel oleh Supplier**

Gambar diatas merupakan tampilan dari halaman manajemen artikel oleh *supplier*.
Pada halaman ini, *supplier* dapat menonaktifkan artikel, melihat list artikel
yang pernah dibuat dan juga dapat menambahkan artikel dengan menekan tombol
tambah artikel untuk menuju ke halaman tambah artikel. Halaman ini juga memiliki
*filtering* berdasarkan judul, kategori dan juga dapat diurutkan sesuai abjad.
Pada tabel artikel tersebut berisi judul, tanggal pembuatan artikel, jumlah klik
yang dilakukan pengguna, cuplikan isi artikel, kategori, dan status keaktifan
artikel. Untuk menghapus artikel, *supplier* dapat menekan ikon sampah pada
kolom atur. Kemudian sistem akan menampilkan *pop up* konfirmasi penghapusan
artikel. *Supplier* juga dapat mengubah artikel yang dibuat dengan menekan ikon
*edit* pada kolom atur untuk menuju ke halaman ubah artikel.

![Graphical user interface, text Description automatically generated with medium
confidence](media/08f287af2fcbc6adf94243f0930c52bb.png)

###### **Tampilan Aplikasi Halaman Manajemen Produk oleh Supplier**

Gambar diatas merupakan tampilan dari halaman manajemen produk oleh *supplier*.
Pada halaman ini, *supplier* dapat menambahkan, menghapus, dan melihat list
produk. Halaman ini juga memiliki *filtering* berdasarkan nama, kategori produk
dan juga dapat diurutkan sesuai abjad. Pada tabel produk tersebut berisi nama
produk, deskripsi singkat dan tanggal pembuatan produk, penilaian, jumlah produk
terjual, harga, stok dan status keaktifan produk. Untuk menghapus produk,
*supplier* dapat menekan ikon sampah pada kolom atur. Kemudian sistem akan
menampilkan *pop up* konfirmasi penghapusan produk. Apabila *supplier* ingin
mengubah detail produk tertentu, *supplier* dapat menekan tombol *edit* untuk
menuju ke halaman pengubahan produk.

![Graphical user interface, application Description automatically
generated](media/e90a0baad7fa28ca5b89be9a0b95c9bc.png)

###### **Tampilan Aplikasi Halaman Tambah Produk**

Gambar diatas merupakan tampilan halaman tambah produk oleh *supplier*. Untuk
menambahkan sebuah produk, *supplier* harus mengisi seluruh kolom yang tertera
pada *form* penambahan tersebut. Kolom tersebut diantaranya kategori, nama,
deskripsi, harga, stok, dan berat produk, juga beberapa foto dan *filter*
seperti kandungan. Jika *supplier* telah mengisi seluruh kolom dengan benar dan
sesuai, *supplier* dapat menekan tombol simpan. Apabila data yang dimasukkan
valid, sistem akan menampilkan pesan sukses bahwa data berhasil tersimpan,
sedangkan jika data tidak valid, sistem akan menampilkan pesan *error* pada
kolom yang salah.

![Graphical user interface, application Description automatically
generated](media/ab13eff44cf884b24a9fda2577083a35.png)

###### **Tampilan Aplikasi Halaman Tambah Artikel**

![Graphical user interface, application Description automatically
generated](media/9b58d0dd3dc16cd1bf52ee5c9bb6d52e.png)Gambar diatas merupakan
tampilan halaman tambah artikel oleh *supplier* dan admin. Untuk menambahkan
sebuah artikel, pengguna harus mengisi seluruh kolom yang tertera pada *form*
penambahan tersebut. Kolom tersebut diantaranya judul, kategori dan isi artikel
beserta foto artikel tersebut. Jika pengguna telah mengisi seluruh kolom dengan
benar dan sesuai, pengguna dapat menekan tombol simpan. Apabila data yang
dimasukkan valid, sistem akan menampilkan pesan sukses bahwa data berhasil
tersimpan, sedangkan jika data tidak valid, sistem akan menampilkan pesan
*error* pada kolom yang salah.

###### **Tampilan Aplikasi Halaman Tambah Akun oleh Admin**

Gambar diatas merupakan tampilan halaman tambah akun *supplier* oleh admin.
Untuk menambahkan sebuah akun, admin harus mengisi seluruh kolom yang tertera
pada *form* penambahan tersebut. Kolom tersebut diantaranya nama, peran,
*email*, nomor telepon, kata sandi, domain, deskripsi, alamat, kota hingga foto
profil. Jika admin telah mengisi seluruh kolom dengan benar dan sesuai, admin
dapat menekan tombol simpan. Apabila data yang dimasukkan valid, sistem akan
menampilkan pesan sukses bahwa data berhasil tersimpan, sedangkan jika data
tidak valid, sistem akan menampilkan pesan *error* pada kolom yang salah.

![Graphical user interface, application Description automatically
generated](media/a6a2317f6479f0c17e54feba1ea6a2a0.png)

###### **Tampilan Aplikasi Halaman Ubah Produk**

Gambar diatas merupakan tampilan halaman ubah produk oleh *supplier*. Pada
halaman ini terdapat *form* berisi beberapa kolom yang diantaranya kategori,
nama, deskripsi, harga, stok, dan berat produk, juga beberapa foto dan *filter*
seperti kandungan. Jika *supplier* telah mengubah data kolom dengan benar dan
sesuai, *supplier* dapat menekan tombol simpan. Apabila data yang dimasukkan
valid, sistem akan menampilkan pesan sukses bahwa data berhasil tersimpan,
sedangkan jika data tidak valid, sistem akan menampilkan pesan *error* pada
kolom yang salah.

![Graphical user interface, text, application Description automatically
generated](media/818afeba86504ab54602fc9efc759a3c.png)

###### **Tampilan Aplikasi Halaman Ubah Artikel**

Gambar diatas merupakan tampilan halaman tambah ubah oleh *supplier* dan admin.
Pada halaman ini terdapat *form* berisi beberapa kolom yang diantaranya judul,
kategori dan isi artikel beserta foto artikel tersebut. Jika pengguna telah
mengubah data kolom dengan benar dan sesuai, pengguna dapat menekan tombol
simpan. Apabila data yang dimasukkan valid, sistem akan menampilkan pesan sukses
bahwa data berhasil tersimpan, sedangkan jika data tidak valid, sistem akan
menampilkan pesan *error* pada kolom yang salah.

![A picture containing graphical user interface Description automatically
generated](media/7d72df47684926545392990e8512e5e4.png)

###### **Tampilan Aplikasi Halaman Tentang Kami**

Halaman ini merupakan halaman yang berisi deskripsi singkat mengenai situs web
SehatinAja seperti apa itu SehatinAja, hingga visi dan misi.

![Text Description automatically generated with medium
confidence](media/01cae3c2a844f83671a7ef39aebed6a3.png)

###### **Tampilan Aplikasi Halaman Syarat dan Ketentuan**

Halaman ini merupakan halaman yang berisi list syarat dan ketentuan ketika
mengakses fitur-fitur yang terdapat pada situs web SehatinAja seperti ketentuan
ketika melakukan transaksi pembelian oleh *customer* dan penjualan oleh
*supplier.*

![Text Description automatically
generated](media/fe78993e84b0ce217321e7dbbf2f7c2a.png)

###### **Tampilan Aplikasi Halaman Kebijakan dan Privasi**

Halaman ini merupakan halaman yang berisi list kebijakan dan privasi bahwa data
pengguna yang terdaftar adalah benar dan merupakan tanggung jawab pengguna itu
sendiri*.*

![Text Description automatically
generated](media/913ffe860ff8e48c0a8179a637605ec0.png)

###### **Tampilan Aplikasi Halaman Kebijakan Pengiriman**

Halaman ini merupakan halaman yang berisi list kebijakan pengiriman bahwa
*customer* berhak memilih kurir yang akan mengantarkan produk ke alamat
*customer* sesuai dengan daftar kurir yang disediakan situs web SehatinAja.
