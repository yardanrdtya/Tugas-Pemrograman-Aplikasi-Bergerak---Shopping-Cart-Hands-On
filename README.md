# Tugas-Pemrograman-Aplikasi-Bergerak-Shopping-Cart-Hands-On
Yardan Raditya Rafi' Widyadhana | 2409116037 | Sistem Informasi A 2024

Mini E-Commerce Shopping Cart dengan Provider

# Antarmuka Awal

<img width="504" height="873" alt="image" src="https://github.com/user-attachments/assets/21a20cff-6c54-481a-bb65-7fe7c6c8846a" />

Antarmuka awal di aplikasi ini menampilkan daftar produk dalam bentuk grid dua kolom. Setiap kartu produk menampilkan ikon produk, nama, harga dalam Rupiah, dan tombol Add untuk menambahkan barang ke keranjang.

# Tampilan Keranjang

<img width="506" height="873" alt="image" src="https://github.com/user-attachments/assets/05ed9155-a636-4de2-8d4c-ddc08cf162df" />

Setelah menambahkan barang ke keranjang, dihalaman ini menampilkan daftar produk yang telah ditambahkan ke keranjang dalam bentuk kartu. Setiap item menampilkan ikon produk, nama, harga satuan, jumlah barang (dengan tombol tambah/kurang), total harga per item, serta tombol hapus. Di bagian bawah terdapat total keseluruhan belanja dan tombol Checkout untuk melanjutkan proses pembelian.

<img width="509" height="875" alt="image" src="https://github.com/user-attachments/assets/acc719d2-47f8-41a4-92e8-fbbd9ae1a238" />

Jika ingin mengurangi atau menghapus produk yang ada dikeranjang, bisa menggunakan tombol +/- atau menggunakan fitur clear cart seperti gambar diatas. Fitur Clear Cart digunakan untuk menghapus seluruh produk yang ada di keranjang belanja sekaligus. Ketika pengguna menekan ikon hapus pada AppBar keranjang, sistem menampilkan dialog konfirmasi bertuliskan “Clear Cart?” untuk memastikan tindakan tidak dilakukan secara tidak sengaja.

<img width="511" height="875" alt="image" src="https://github.com/user-attachments/assets/29951e0e-f10a-4f08-922f-d7cbe57799d7" />

Jika pengguna memilih Clear, maka semua item di keranjang akan dihapus dan keranjang kembali kosong. Jika memilih Cancel, maka data keranjang tetap tersimpan. Setelah itu halaman keranjang kemudian menampilkan ikon keranjang kosong, dengan pesan “Your cart is empty”, dan tombol Continue Shopping.

# Tampilan Akhir

<img width="506" height="870" alt="image" src="https://github.com/user-attachments/assets/8ca70aa5-3573-4306-aeb7-18536f839a44" />

Ketika pengguna menekan tombol Continue Shopping pada kondisi keranjang kosong, aplikasi akan mengarahkan kembali ke halaman Products. Halaman ini menampilkan daftar produk dalam bentuk grid sehingga pengguna dapat memilih dan menambahkan barang kembali ke keranjang.






