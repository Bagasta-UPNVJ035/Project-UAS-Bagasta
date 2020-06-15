Nama : Bagasta
NIM : 1910512035
Email : upnvjbagasta@gmail.com

project ini berisi tentang pengimplementasian dari konsep binary search tree (BST). Binary tree merupakan salah satu struktur data mana struktur dari datanya beruapa akar, dengan masing-masing akarnya memiliki cabang dua (oleh karena itu disebut sebagai “binary”). Hal pertama yang perlu diketahui adalah apa itu struktur data ? Struktur data adalah cara bagaimana cara menyusun suatu data, agar saat mengakses data tersebut dapat dilakukan dengan lebih efisien. Dari definisinya sendiri kita sudah dapat lihat bahwa struktur data memiliki tujuan untuk mengefesiensikan pengaksesan data. Nah, lalu yang menjadi pertanyaan adalah apa binary tree ? Binary tree adalah salah satu struktur data yang berbentuk akar, dengan tiap akarnya memiliki 2 cabang. Yang perlu menjadi catatan disini adalah bagaimana cara menyusun binary tree ini. dalam program ini terdapat beberapa fitur, yaitu insert, yang fungsinya untuk memasukkan data baru. jika kita memasukkan data yang belum terdapat dalam tree, maka data akan diinput, jika kita memasukkan data yang sudah terdapat dalam tree, juga tetap akan diinput. "fitur selanjutnya adalah search, yang memiliki fungsi untuk mencari data di dalam tree. jika data yang dicari terdapat dalam tree, maka akan muncul tulisan simpul yang dilewati : searched note = . Jika kita mencari data yang tidak terdapat di dalam tree, maka akan muncul tulisan Simpul yang dilewati : Data Not found in tree. fitur selanjutnya adalah delete, yang dimana kegunaannya adalah menghapus data yag terdapat di dalam tree. fitur berikutnya adalah reset, kegunaannya adalah untuk menghapus seluruh data yang terdapat di dalam tree. kemudian terdapat fitur show pre order, yang memiliki fungsi untuk menampilkan data dalam tree secara pre order. selain show pre order, ada fitur show in order, yang memiliki fungsi untuk menampilkan data dalam tree secara in order. yang lainnya ada fitur show post order, yang memiliki fungsi untuk menampilkan data dalam tree secara post order. setelah itu terdapat fitur show max number, fitur ini memiliki kegunaan untuk menampilkan data terbesar dalam Binary Search Tree. Yang terakhir terdapat fitur Show Min Number, kegunaannya adalah untuk menampilkan data terkecil dalam Binary Search Tree.

Aturan saat “insert” kedalam binary tree ini adalah dengan membandingkan data yang akan dimasukkan dengan kondisi root saat itu. Ok, mari kita telaah ! angka pertama yang akan menjadi “root” adalah 4, maka angka tersebut akan menjadi paling atas. Lalu berikut nya 2, nah disini kita akan membandingkan 2 dengan 4, 2 lebih kecil dibanding 4, maka dia akan diletakkan dikir. Lalu 7, karena 7 lebih besar dari 4, maka 7 diletakkan disebelah kanan. Lalu 1, 1 lebih kecil dibandingkan 4 maka akan masuk ke sebelah kiri, namun karena sebelah kiri sudah memiliki “root” yaitu 2, maka 1 akan dibandingkan kembali dengan 2, karena 1 lebih kecil dibandingkan dengan 2, maka 1 diletakkan disebelah kiri dari 2. Begitu juga berlaku dengan 3. Dari, penjelasan diatas, dapat disimpukan bahwa binary tree saat “insert” data mengurutkan datanya terlebih dahulu. Lalu apa hubungannya dengan kegunaan binary tree dalam pemrograman ? ”. Kita ambil kasus simple saja, kita diminta untuk menangani deretan angka yang tidak berurutan, lalu diminta untuk menentukan manakah angka yang terbesar, dengan mudah kita akan langsung mengambil data yang paling kanan sampai tidak memiliki cabang lagi. Kenapa bisa seperti itu ? karena otomatis angka yang memiliki posisi paling kanan dan sudah tidak memiliki cabang dialah angka yang paling besar. Mungkin kita terbiasa dengan struktur data array , lalu saat kita ingin menentukan mana angka yang paling besar, kita akan membandingkan satu demi satu terlebih dahulu dari banyaknya larik yang ada dalam array tersebut. Lalu baru kita mendapatkan angka yang paling besar. Bayangkan jika hal ini dilakukan dengan deretan angka yang sangat banyak, butuh waktu berapa lama yang akan dihabiskan hanya untuk menentukan manakah angka yang paling besar.
