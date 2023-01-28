Project Web Programming (Lecturer)
Anggota Kelompok:
1. Tantowi Putra Agung Setiawan - 2440063271
2. Fisalma Maradita - 2440110311
3. Angelique Aurielle Alpaullivarez - 2440122564
4. Salsabila Adrian - 2440112033 
5. Raden Akira Ziyad Asqar - 2440045325 

-- Cara Instalasi Project

Cara 1: 
1. Download dan Extract project yang masih di zip
2. Buka Command prompt
3. Ketik "code ." pada terminal
4. Buka terminal pada visual studio code
5. ketik composer update
6. Nyalakan xampp
7. Buat database dengan nama "kripikku"
8. Pada file .env, ubah database_name sesuai dengan yang sudah dibuat
9. Buka terminal pada visual studio code 
10. Ketikan php artisan migrate:fresh --seed 
11. ketik php artisan serve

Cara 2: 
1. Download dan Extract project yang masih di zip
2. Buka Command prompt
3. Ketik "code ." pada terminal
4. Buka terminal pada visual studio code
5. ketik composer update
6. Nyalakan xampp
7. Import kripikku.sql pada php MyAdmin
8. Buka terminal pada visual studio code 
9. ketik php artisan serve

Apabile beberapa asset seperti gambar tidak muncul, maka lakukan langkah-langkah berikut pada terminal:
1. php artisan storage:link (Jika masih tidak bisa, maka lakukan langkah-langkah di bawah)
2. cd public
3. rm storage
4. cd ..
5. php artisan storage:link
