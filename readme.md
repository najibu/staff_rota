# Instaliation guide

1. Rename .env.example file  to .env and set DB_DATABASE, DB_USERNAME, DB_PASSWORD.
2. Switch to project directory.
3. Run in your terminal:  ``` composer install ```
4. Run:  ``` php artisan key:generate ```
5. Run the migrations and seed the table:
``` php artisan migrate ``` and ``` php artisan db:seed ```
6. Run: ``` npm install ```
7. Run: ``` bower install ```.
8. Run: ``` gulp ``` 
9. Run: ``` php artisan serve ``` and visit localhost:8000. 
 
 
 #### Some explanations
 
* In Staff shift times table days are translated to human readable. Assumed day 0 is sunday.
* If some case 'daynumber' is not representing a day of week, days are displayed as numbers in pie charts.
* The task is done how I understood it. It is quite confusing.