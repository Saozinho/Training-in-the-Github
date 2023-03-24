# Section 18 Forms and validation

 **Forms**
- allow users to input data into a web application through a user-friendly interface. Laravel provides a range of form-building tools to make it easy to create forms and handle form submissions. You can use Laravel's built-in form helpers to generate form HTML, including input fields, labels, and buttons.

**Validation**

- is the process of ensuring that the data submitted through a form meets certain criteria or requirements. Laravel provides a powerful validation system that makes it easy to define validation rules for form inputs. You can define rules to check if the input is required, if it meets certain length or format criteria, and if it matches certain values. Laravel's validation system provides a variety of built-in validation rules, as well as the ability to create custom validation rules.


```PHP
//OLD Syntax:
Route::resource('/posts','PostsController');

//NEW Syntax:

Route::resource('/posts',PostsController::class);

```

**CSRF PROTECTION**

- Cross-site request forgeries are a type of malicious exploit whereby unauthorized commands are performed on behalf of an authenticated user.
Preventing CSRF Requests

- Laravel automatically generates a CSRF "token" for each active user session managed by the application. This token is used to verify that the authenticated user is the person actually making the requests to the application. Since this token is stored in the user's session and changes each time the session is regenerated, a malicious application is unable to access it.
///The current session's CSRF token can be accessed via the request's session or via the csrf_token helper function:


```PHP
use Illuminate\Http\Request;

Route::get('/token', function (Request $request) {
    $token = $request->session()->token();

    $token = csrf_token();

    // ...
});

```