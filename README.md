## Bookshelf API Submission Dicoding

Terdapat 7 Kriteria utama yang harus dipenuhi dalam membuat proyek Bookshelf API.

### Kriteria 1 : Aplikasi menggunakan port 9000
Dalam file ```server.js``` port disetting dengan nilai 9000, apabila komputer tidak dapat menggunakan port tersebut dapat digunakan port sementara, namun ketika submission dirubah dengan port 9000.

### Kriteria 2 : Aplikasi dijalankan dengan perintah npm run start
Dalam file ```Package.json``` diberikan perintah ```"script":{
"start" : "node src/server.js", }``` apabila ingin menggunakan nodemon bisa ditambahkan ```"start-dev":"nodemon src/server.js"```. untuk menjalankan node menggunakan baris perintah ```npm run start```, sedangkan menjalankan nodemon dengan perintah ```npm run start-dev```.

Untuk mengerjakan kriteria 3 - 7 dibuat file routes.js untuk menyimpan Method, URL, dan Body Request. file handler.js menyimpan fungsi untuk body request. untuk menyimpan data dibuat file books.js yang berisi variabel yang menampung data array.

### Kriteria 3 : API dapat menyimpan buku
Untuk menyimpan buku menggunakan method : POST.

### Kriteria 4 : API dapat menampilkan seluruh buku
Untuk menampilkan seluruh buku menggunakan metode GET

### Kriteria 5 : API dapat menampilkan detail buku
Untuk menampilkan detail buku menggunakan method GET yang mengambil data sesuai dengan id, sehingga ```path: "/books/{id}"```.

### Kriteria 6 : API dapat mengubah data buku
Untuk mengubah data buku menggunakan method : PUT.

### Kriteria 7 : API dapat menghapus buku
Untuk menghapus buku menggunakan method : DELETE
