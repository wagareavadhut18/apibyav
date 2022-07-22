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

