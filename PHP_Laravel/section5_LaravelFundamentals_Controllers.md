# Section 5  Laravel Controllers

**Controllers**
- In Laravel, controllers are used to handle user requests and generate responses.

- Can be used as a controller namespaces to organize your controllers into subdirectories.

- Can be used to resource controllers to automatically generate `CRUD` routes and corresponding controller methods for a specific model.

`Creating Controller`

- php artisan make:controller 'Name_of_The_Controller' :: This is the recommended rather than creating it manually meaning right clicking and creating new file.

- php artisan make:controller --resource 'Name_of_The_Controller' :: with the resource it automatically creates a CRUD functionalities.

`CRUD - Create , Read , Update , Delete`

**use**
- Is to import specific class to use its functionality
Resources

**Resource**
- Is a special static function that will automatically gives us access to different types of routes.

**Commands**
- Route::get('/post', 'Postscontroller@index');

