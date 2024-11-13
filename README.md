Create registration form that allows user to sign up to site. After successful registration user
will be signed in automatically. System will display current user email, name and ‘logout’ link.
User can log out by clicking on link. Create “sign in” form. User can sign in with their login +
password OR email + password pairs.

Functional requirements

# Registration form fields:
- email;
- login;
- real name;
- password;
- birth date;
- country (drop down list taken from database);
- agree with terms and conditions (checkbox, must be checked by user).
  
# Sign in form fields:
- login or email;
- password.

- All fields should be validated before saving to DB;
- Form should remain filled (except password field) in case of validation errors;
- Email and login must be unique;
- List of countries should be stored in DB;
- Add user registration Unix timestamp to DB (field type - integer).
- Routing have to work not only in the root of domain, it will be tested on our dev server
in separate folder, example:
http://site.com/test-task100500/{your routing}
!Please check this before sending ready task.

Development requirements

- Should work on PHP 7.0.6+ / MariaDB 10+ / HTML5;
- Don’t use frameworks, off-the-shelf registration/login libs;
- You can use 3rd-party mysql libs, validation libs;
- Character encoding is UTF-8 everywhere: MySQL, HTML, PHP;
- Try to keep your code well structured;
- Save your code on Github, provide us with link and readme.
