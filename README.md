Kripikku is a website where you can put your "Kripik" product on the website and then sell it.

Web Programming Project (Lecturer)
Group Members:
1. Tantowi Putra Agung Setiawan - 2440063271
2. Fisalma Maradita - 2440110311
3. Angelique Aurielle Alpaullivarez - 2440122564
4. Salsabila Adrian - 2440112033 
5. Raden Akira Ziyad Asqar - 2440045325 

-- How to Install

Method 1:
1. Download and extract the project that is still in zip format.
2. Open the Command Prompt.
3. Type "code ." in the terminal.
4. Open the terminal in Visual Studio Code.
5. Type composer update.
6. Turn on XAMPP.
7. Create a database named "kripikku."
8. In the .env file, change the database_name to the one you created.
9. Open the terminal in Visual Studio Code.
10. Enter php artisan migrate:fresh --seed.
11. Type php artisan serve.

Method 2:
1. Download and extract the project that is still in zip format.
2. Open the Command Prompt.
3. Type "code ." in the terminal.
4. Open the terminal in Visual Studio Code.
5. Type composer update.
6. Turn on XAMPP.
7. Import kripikku.sql in phpMyAdmin.
8. Open the terminal in Visual Studio Code.
9. Type php artisan serve.
    
If some assets such as images do not appear, follow these steps in the terminal:
1. php artisan storage:link (If it still doesn't work, follow the steps below)
2. cd public
3. rm storage
4. cd ..
5. php artisan storage:link
