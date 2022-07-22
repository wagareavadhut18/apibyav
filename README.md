# Lumen PHP Framework

1)  For supporting key:generate command package installed from :
    - https://github.com/flipboxstudio/lumen-generator
    - After this package installation application key generated using command :

    ```sh
    php artisan key:generate
    ```
2) For seeding make UserSeedr and enter the commands for adding 5 dummy records
     ```sh
    php artisan tinker
    App\Models\User::factory()->count(5)->create()
    ```

3) Integrate passport authentication :
    - https://packagist.org/packages/dusterio/lumen-passport
    - https://github.com/dusterio/lumen-passport
    - https://www.youtube.com/watch?v=g_22EUfibJ8

    - After adding configuration code run the following commands for to migrate and install:
    ```bash
    # Create new tables for Passport
    php artisan migrate
    # Install encryption keys and other stuff for Passport
    php artisan passport:install
    ```