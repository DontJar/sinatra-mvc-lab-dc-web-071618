# Sinatra MVC Lab - Pig Latinizer

In this lab, you'll be building a **Pig Latinizer** using Sinatra and the MVC paradigm of app development. Your app will take in a string from a user through a form, convert it to pig latin, and return the string to the user. Using the previous code-along as a guide, get the tests to pass by building out this application. Use the guide below to get you started!

## Instructions

1. Build a form to take user input in user_input.erb. Show that form using a `GET` request at `/`.

2. Create a `POST` method in your controller (`app.rb`) to receive your form's `params`.

3. Build a `PigLatinizer` model (in your models directory) that converts a string into pig latin.

4. In your application controller, create an instance of the `PigLatinizer` class to convert your user input to Pig Latin.

5. Use ERB within a new view to display the final pig latin string to the user.



<a href='https://en.wikipedia.org/wiki/Pig_Latin'>Pig Latin on wikipedia</a>

<p class='util--hide'>View <a href='https://learn.co/lessons/sinatra-mvc-lab'>Sinatra MVC Lab</a> on Learn.co and start learning to code for free.</p>
_____________________________________________________________________
class PigLatinizer
  can create a new instance of a class (FAILED - 1)
  piglatinizes an individual word (FAILED - 2)
  has a method splits the sentence to piglatinize each word (FAILED - 3)

Pig Latinizer App
  GET '/'
    returns a 200 status code (FAILED - 4)
    renders the instructions (FAILED - 5)
    renders a new form element on the page (FAILED - 6)
    renders the form directions on the page (FAILED - 7)
    renders the input field for the phrase (FAILED - 8)

  POST '/piglatinize'
    returns a 200 status code (FAILED - 9)
    displays the pig latinized phrase upon form submission (FAILED - 10)
  POST '/piglatinize' again

    returns a 200 status code (FAILED - 11)
    displays the pig latinized phrase upon form submission (FAILED - 12)
