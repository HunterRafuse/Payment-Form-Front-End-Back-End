# Payment-Form-Front-End-Back-End
Little payment form created with Stripe API, PHP and MySQL


## To begin
this little project is heavily PHP orientated. If you don't know too much about PHP I recommend beginning with functions, loops and
object coding. 

Functions & Arrays:
http://php.net/join

Classes:
http://php.net/dir

While and For loops:
http://php.net/while

OOP, Object Oriented Programming:
http://php.net/oop

# Now that we covered the basics:
Make sure you have PHP 7 installed.


<details>
  Now we need to make sure we have PHPMyAdmin installed as well which should come with the XAMPP or WAMPP or whatever you use for PHP testing and rendering of your .php files and make sure you do that before going any further.
</details>


## Stripe & Paypal APIs 
We are going to use Stripe and or Paypal as those are the most commonly used and more reliable payment APIs to work with. I recommend creating a "work" or "developer" email that is only for signing up for APIs and other things related to development and your projects as that helps to keep things organized on a very basic level.

# Downloading or Cloning:

Since we're using composer, it's kind of like Node.js in where we have to install dependencies. So if you clone, or download, this repository, just initialize this command within the directory:
```
composer install

```
Then enter your API keys from your stripe account in the charge.js file as well as the charge.php and your database information in the db.php file. You're all set!
