a. Untuk perancangan aplikasi antar makanan dimana hanya melayani pemesanan melalui mobile apps saya memilih untuk menggunakan restful api-based web service, karena menurut saya restful-api sangat flexible dalam artian dengan restful api kita bisa menggunakan format response sesuai kebutuhan(XML, JSON, dll)

sedangkan untuk stacknya saya akan menggunakan:
- Programming language: Python, python sudah terbukti sangat baik untuk digunakan sebagai backend, selain itu python memiliki komunitas yang sangat baik serta dukungan banyak modul serta library yang telah tersedia.
- framework: django, django merupakan salah satu web framework python yang paling terkenal disamping flask. django dilengkapi amunisi komplit, sehingga memudahkan developer saat melakukan development.
- database: postgreSQL, saya memilih untuk menggunakan RDBMS daripada noSQL karena menurut saya untuk permasalahan ini kita membutuhkan relational database.


b. Untuk masalah keamanan dalam pengiriman data saya memilih untuk menggunakan JWT(JSON web tokens). Dengan menggunakan JWT maka setiap mobile apps akan melakukan request ke backend akan selalu mengirimkan token pada request tersebut, dari token ini akan dapat memvalidasi suatu request.