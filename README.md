Run without docker
Create file env

cp .env.example .env
Install package
composer install

Create key application
php saya key

Execute migration database
php saya migrasi --gen

Run in development server
php saya coba
