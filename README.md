<p align="center"><a href="https://github.com/TonyOsadolor/laravel11-breeze" target="_blank"><img src="https://raw.githubusercontent.com/laravel/breeze/b3500ea6513e0b04edfe0bf949eac66280436e59/art/logo.svg" width="200" height="auto"></a></p>

## Introduction

Breeze provides a minimal and simple starting point for building a Laravel application with authentication. Styled with Tailwind, Breeze publishes authentication controllers and views to your application that can be easily customized based on your own application's needs.
<br>
Laravel Breeze is powered by Blade and Tailwind.
<br>
In this project, I hope to put to practice my skills, as I integrate also with Social Authentications using Laravel Socialite.
<br>
Collaborators, Contributions and Corrections are welcome, I am just a young coder, hoping to learn even more advanced ways of coding... Thanks.

## How it works

<ol>
    <li>Open the website</li>
    <li>If you are a 'New User' click on 'Sign Up' to sign up with your credentials,</li>
    <li>Or Select any of the Listed Social Media Account to Auto-Sign Up with your Details.</li>
    <li>No specific Dashboard desires added for now, but hopefully, in time....</li>
</ol>

## Project Sponsors

No project Sponsors for now.

### Stacks

- **Backend : PHP / Laravel**
- **Frontend : Breeze - TTailwind**

## Contribution Guide
##### Setting up your workspace
Before running this app, locally make sure you have the following software installed:
<ul>
    <li>XAMPP/WAMP/LAMP or it's equivalent</li>
    <li>NPM</li>
    <li>Composer</li>
    <li>A Web Browser</li>
</ul>
Now, follow this steps to start contributing:
<ol>
    <li>Go to https://github.com/TonyOsadolor/laravel11-breeze and fork the repo.</li>
    <li>After forking, go to your github page. Clone your forked repo. Navigate to your desired folder in your local machine using your favourite CMD terminal. Run: <code>git clone https://github.com/< your github-username >/laravel11-breeze</code>.</li>
    <li>Run <code>cd laravel11-breeze</code></li>
    <li>Run <code>composer install</code></li>
    <li>Run <code>npm install</code></li>
    <li>Copy all the contents of the <code>.env.example</code> file. Create <code>.env</code> file and paste all the contents you copied from <code>.env.exmaple</code> file to your <code>.env</code> file.</li>
    <li>Run <code>php artisan key:generate --show</code> to retrieve a base64 encoded string for Laravel's APP_KEY in <code>.env</code></li>
    <li>Set your DB_DATABASE = <code>laravel11_breeze</code></li>
    <li>If you are using XAMPP , run it as an administrator. Start Apache and Mysql. Go to <code>localhost/phpmyadmin</code> and create new database and name it <code>laravel11_breeze</code>.</li>
    <li>When that is done, run <code>php artisan migrate</code> in your terminal to migrate all the necessary database tables into your local database.</li>
    <li>Run php artisan serve from your terminal and the app will be running on <code>http://127.0.0.1:8000/</code> on your browser</li>
</ol>
##### REMINDER on contributing:
<ol>
    <li>Always create branch for your contributions <code>git checkout -b &lt;branchname&gt;</code>.</li>
    <li>After you make changes:</li>
    <ul>
        <li><code> git add .</code></li>
        <li><code> git commit -m "some comments"</code></li>
        <li><code> git push origin < name of your branch > </code></li>
    </ul>
    <li>Create PR.</li>
</ol>

## Code of Conduct

In order to ensure that the Project is used for it rightful existence, please review and abide by the [Code of Conduct](#).

## Security Vulnerabilities

If you discover a security vulnerability within Project, please send an e-mail to Anthony Osadolor via [tonyentertain@gmail.com](mailto:tonyentertain@gmail.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
