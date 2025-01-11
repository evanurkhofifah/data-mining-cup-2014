# Data Mining Cup 2014
Pengembalian barang merupakan faktor biaya yang sangat signifikan bagi retail online. Rata-rata setengah dari semua pesanan pelanggan adalah pengembalian barang. Topik ini akan menjadi semakin penting dengan diperkenalkannya petunjuk perlindungan konsumen. Oleh karena itu, tingkat pengembalian yang lebih rendah akan menjadi faktor utama dalam keunggulan kompetitif dalam ritel online.

Berdasarkan data pembelian historis dari sebuah toko online, sebuah model harus dipelajari untuk menghasilkan prediksi probabilitas bahwa pembelian tertentu dikonversi menjadi pengembalian berdasarkan data pembelian baru dari toko tersebut. Untuk tujuan ini, data historis juga berisi data pembelian dan pengiriman sebagai atribut produk dan pelanggan yang berbeda. Informasi "return yes/no" juga diketahui dari data historis. Data historis berisi data pembelian dan pengiriman toko online 2014.

* orderItemID: Nomor barang pesanan
* orderDate: Tanggal pemesanan
* deliveryDate : Tanggal pesanan dikirim
* itemID: ID barang
* size: Ukuran barang
* color: Warna barang
* manufacturerID: ID manufaktur/pabrik
* price: Harga barang
* customerID: ID pelanggan
* salutation: Salutation pelanggan
* dateOfBirth: Tanggal lahir pelanggan
* state: Negara pelanggan
* creationDate: Tanggal pembuatan akun

Target: returnShipment | returnShipment: Pengembalian (1=ya/dikembalikan, 0=tidak/disimpan). Memprediksi apakah ada pengembalian barang pada pembelian berdasarkan data pembelian baru toko tersebut. Atribut target "returnShipment" dari item pesanan. Nilai "0" berarti "barang disimpan" dan nilai "1" berarti "barang dikembalikan".
