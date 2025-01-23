# Solusi

Pada soal Two Sum ini, saya mengerjakan dengan terlebih dahulu membaca komentar dan artikel.

## Kamus
### HashMap
Ada satu metode pada python bernama hash untuk menyimpan dan mengakses data, namanya [Hashmap](https://medium.com/edureka/hash-tables-and-hashmaps-in-python-3bd7fc1b00b4).
Di python, hashmap diimplementasikan pada sebuah tipe data bernama dictionary, yang dapat diubah-ubah. Dictionary akan menyimpan sebuah key dengan value-nya. Dengan demikian kita dapat menyimpan angka1 dengan indeksnya untuk mencari angka2 (target - angka1) agar menghasilkan indeks dari angka yang menghasilkan angka1 + angka2 = target.

### enumerate
Untuk menyimpan dictionary pada python yang berisi indeks dan valuenya, dapat digunakan function enumerate.

## Langkah
- Buat set (agar tidak duplikat) yang akan menyimpan hashmap angka yang ada di list.
- Lakukan perulangan pada setiap array.
- Lakukan pengecekan angka1 dengan melakukan pengecekan: jika angka1 ada di hashmap, perulangan selesai dengan mengembalikan indeks angka1 dan angka2 (i saat ini). Jika angka1 belum ketemu, masukkan angka ke hashmap.
