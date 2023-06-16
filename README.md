# PPBO-UAS
V3922048 Winasis Widya Wisesa TIE

Kelas Main:

1. Pada main method, objek Mobil dengan merk "Honda", warna "Biru", dan tahun produksi 2005 dibuat menggunakan konstruktor Mobil.
2. Selanjutnya, objek Pengemudi dengan nama "Winasis", umur 23, dan objek Mobil sebelumnya dikaitkan dengan menggunakan konstruktor Pengemudi.
3. Melalui objek Pengemudi, fitur mobil diakses dengan memanggil method nyalakanMobil() untuk menyalakan mobil, kemudian getStatusMobil() digunakan untuk mendapatkan status mobil dan mencetaknya.
4. Kemudian, method ubahWarnaMobil("Putih") dipanggil untuk mengubah warna mobil menjadi "Putih" dan kembali mencetak status mobil.
5. Akhirnya, method matikanMobil() dipanggil untuk mematikan mobil dan mencetak status mobil terakhir.

Kelas Pengemudi:

1. Kelas ini memiliki atribut nama (nama pengemudi), umur (umur pengemudi), dan mobil (objek mobil yang dikemudikan).
2. Terdapat konstruktor Pengemudi yang digunakan untuk menginisialisasi atribut-atribut tersebut.
3. Method nyalakanMobil() digunakan untuk menyalakan mobil melalui objek Mobil yang terkait.
4. Method matikanMobil() digunakan untuk mematikan mobil melalui objek Mobil yang terkait.
5. Method getStatusMobil() mengembalikan status mobil yang dikemudikan oleh pengemudi.
6. Method ubahWarnaMobil(String warnaBaru) digunakan untuk mengubah warna mobil melalui objek Mobil yang terkait.

Kelas Mobil:

1. Kelas ini memiliki atribut merk (merk mobil), warna (warna mobil), tahunProduksi (tahun produksi mobil), dan menyala (status apakah mobil menyala atau tidak).
2. Terdapat konstruktor Mobil yang digunakan untuk menginisialisasi atribut-atribut tersebut.
3. Method nyalakan() digunakan untuk menyalakan mobil dengan mengubah nilai atribut menyala menjadi true.
4. Method matikan() digunakan untuk mematikan mobil dengan mengubah nilai atribut menyala menjadi false.
5. Method getStatus() mengembalikan status mobil, yaitu jika mobil menyala maka mengembalikan status menyala, dan jika mobil mati maka mengembalikan status mati.
6. Method ubahWarna(String warnaBaru) digunakan untuk mengubah warna mobil dengan mengubah nilai atribut warna.
