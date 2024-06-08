# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# my_app


* 1. kerangka management artikel

atributnya adalah 
1. user > full_name, email, password
2. Article > user_id, title, description, created_at, update_at
3. comment > article_id, comment, created_at

    langkah 
    1. generate scaffold model user
    2. generate scaffold article
    3. generate model comment (untuk user dan article membuduhkan halaman dimana bisa memodifikasi record dari database yang disimpan dan dikoneksikan ke model untuk comment generatornya model saja, tanpa views, controller, dll)

2. melakukan konversi dari data yang dipetik generator menjadi data yang akan disimpan pada database.
3. membuat halaman publik
4. membuat halaman index
5. membuat list article di halaman index
6. membuat halaman baca
7. routing halaman baca
8. membuat untuk menambahkan komentar
9. menampilkan hasil koment pada halaman baca
10. evaluasi, navigasi dan perapihan
11. membuat halaman about
12. membuat halaman searching
13. membuat berdasarkan keyword
14. membuat berdasarkan potongan keyword

