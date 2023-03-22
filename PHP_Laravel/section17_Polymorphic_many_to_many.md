# Section 17 Polymorphic Many to Many

**Laravel 8 Accessing Controller:Class**

```PHP 
//OLD:
Route::resource('/posts','PostsController');

//NEW:

Route::resource('/posts',PostsController::class);
```

**CSRF (Cross-Site Request Forgery)** is a type of web security vulnerability that allows an attacker to execute unwanted actions on a web application on behalf of an authenticated user.
-  CSRF attacks can be prevented by implementing CSRF protection measures in the web application.

- Laravel automatically generates a CSRF "token" for each active user session managed by the application. This token is used to verify that the authenticated user is the person actually making the requests to the application. Since this token is stored in the user's session and changes each time the session is regenerated, a malicious application is unable to access it.

```PHP
//The current session's CSRF token can be accessed via the request's session or via the csrf_token helper function:

use Illuminate\Http\Request;

Route::get('/token', function (Request $request) {
    
    $token = $request->session()->token();

    $token = csrf_token();
});
```