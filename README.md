Analisis Praktikum 1

Jika menggunakan NumPy array, operasi harga * 0.9 dapat langsung dilakukan pada seluruh elemen array. Sedangkan jika menggunakan list Python biasa seperti [5000,7000,3000] * 0.9, akan menghasilkan error karena list tidak dapat dikalikan langsung dengan bilangan desimal. NumPy array dapat melakukan operasi matematika pada seluruh elemen secara langsung.

Analisis Praktikum 2

Data kosong terdapat pada kolom menu dan terjual. Jika data langsung dianalisis tanpa dibersihkan, hasil analisis dapat menjadi kurang tepat karena terdapat data yang kosong.

Analisis Praktikum 3

Dari hasil df.info(), kolom yang jumlah non-null-nya lebih sedikit daripada jumlah baris total berarti terdapat data kosong atau missing value pada kolom tersebut. Data tersebut perlu diperiksa sebelum dilakukan analisis lebih lanjut.

Analisis Praktikum 4

Kolom terjual diisi dengan 0 menggunakan fillna() karena data kosong pada jumlah penjualan dapat diartikan sebagai tidak ada penjualan. Sedangkan baris dengan menu kosong dihapus menggunakan dropna() karena nama menu diperlukan untuk mengidentifikasi data.

Analisis Praktikum 5

drop_duplicates() digunakan untuk menghapus baris yang sama agar data tidak dihitung lebih dari satu kali. Tipe data juga perlu dipastikan sesuai agar proses perhitungan dan analisis dapat dilakukan dengan benar. Kolom harga menggunakan tipe integer karena berisi nilai angka.

Analisis Praktikum 6

Menu dengan total pendapatan tertinggi dapat diketahui dari hasil groupby() pada kolom total_pendapatan. Informasi tersebut dapat membantu pihak kantin mengetahui menu yang menghasilkan pendapatan lebih besar sehingga dapat menjadi bahan pertimbangan dalam mengatur persediaan dan penjualan.
