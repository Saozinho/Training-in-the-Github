# Section 6 Laravel Views

- In Laravel, views are used to generate the HTML that is sent to the user's web browser.


**BLADE** 

- Blade is the default templating engine used in Laravel. It is a simple and powerful templating language that allows developers to write clean, concise, and maintainable PHP code in their views.


**Passing Data to View**

```PHP
- public function show_post($id)
    {
        return view('post')->with('id',$id);
  }
  > can be messy use compact instead for multiple parameters.
- {
  return view('post',compact('id'));
  };
  ```

**Commands**

```PHP
 {{}} use this instead of <?php echo " ">
 ```