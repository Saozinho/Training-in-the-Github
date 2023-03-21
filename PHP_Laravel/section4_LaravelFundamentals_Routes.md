# Section 4 Laravel Routes

**Serving**

- php artisan serve : this is using the built in server in php.
 
- Laravel Homestead : is a virtual environment using vagrant & VirtualBox.

- Valet : this is for MAC.

**Routes**
- Routes are defined in the routes/web.php file for web routes and routes/api.php for API routes.

`Named routes allow the convenient generation of URLs or redirects for specific routes. You may specify a name for a route by chaining the name method onto the route definition:!!Route names should always be unique.`
- The HTTP methods that can be used in a route are: get, post, put, patch, delete, options, and any.




**Laravel is a PHP web application framework that follows the Model-View-Controller (MVC) architectural pattern.**

- The root directory of a Laravel application contains various subdirectories and files, such as app, config, database, public, resources, routes, storage, and vendor.

- The app directory contains the core code of your application, including the controllers, models, middleware, and other classes.

- The config directory contains configuration files for your application, such as the database configuration, app settings, and logging settings.

- The database directory contains database migrations, seeders, and factories.

- The public directory contains the publicly accessible files for your application, such as the index.php file that serves as the entry point to your application.

- The resources directory contains non-PHP resources such as views, JavaScript, CSS, and language files.

- The routes directory contains the route definitions for your application.

- The storage directory contains files that need to be stored but should not be publicly accessible, such as log files and user-uploaded files.

- The vendor directory contains the third-party packages installed via Composer.

- Laravel also comes with a built-in command-line interface called Artisan, which provides various helpful commands for managing your application, such as generating boilerplate code, running database migrations, and clearing caches.

- In addition to its core features, Laravel has a robust ecosystem of packages and libraries that can be easily integrated into your application using Composer.

- Laravel also provides a comprehensive testing suite, including unit tests, feature tests, and browser tests, which makes it easy to ensure that your application is functioning correctly.

**Files in Laravel**
- app/: This directory contains the core code of your application, including controllers, models, middleware, and other classes.

- bootstrap/: This directory contains the files needed to bootstrap your application, including the app.php file that sets up the service container and application configuration.

- config/: This directory contains configuration files for your application, such as the app.php file that contains the basic configuration options, as well as other files for various components such as database, mail, and cache.

- database/: This directory contains database-related files, including migration files to create and modify database tables, seed files to populate the database with sample data, and factories to generate fake data for testing purposes.

- public/: This directory contains the publicly accessible files for your application, including the index.php file that serves as the entry point to your application.

- resources/: This directory contains non-PHP resources for your application, such as views (in the views/ directory), JavaScript and CSS files (in the js/ and css/ directories), and language files (in the lang/ directory).

- routes/: This directory contains the route definitions for your application, which determine how incoming requests should be handled.

- storage/: This directory contains files that need to be stored but should not be publicly accessible, such as log files and user-uploaded files.

- tests/: This directory contains the tests for your application, including unit tests, feature tests, and browser tests.

- vendor/: This directory contains the third-party packages installed via Composer.

- composer.json: This file contains the dependencies for your application, which are managed by Composer.

- package.json: This file contains the dependencies for your front-end assets, which are managed by NPM or Yarn.

- .env: This file contains environment variables that are used to configure your application, such as database credentials and app-specific settings.