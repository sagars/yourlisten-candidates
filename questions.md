Personal details

Name: Sagar Sapkota

Country: Nepal

Hourly Rate: $7

Timezone: UTC+05:45

Skype Id: sagar.sapkota068
Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability? yes, I am!
Tech Skills

Assing yourself a score in the following technologies:

Object Oriented Programming (OOP) -

Git - 5

PHP 5 - 8

CakePHP framework - 9

MySQL - 8

Javascript - 7

jQuery - 9

HTML - 9

CSS - 9
Questions About OOP:

    How do you declare a function or method that you want to be accessed without instantiate the class?
    Answer: require('information.php'); echo 'Hello ' . StudentInfo::name();
    How do you create a child class of BaseClass ? 
    Answer: extenidng the BaseClass example: class CommentsController extends AppController

Questions about GIT:

    If you accidentally add the wrong files to be commited using git add, how do you unstage them? 
    Answer: I can use git reset. This will 'unstage' all the files I've added after my last commit.

If you want to unstage only some files, use git reset -- .

Also it's possible to unstage some of the changes in files by using git reset -p.

    If you want to switch to another branch, what command you need to execute? 
    Answer: To create a branch and switch to it at the same time, you can run the git checkout command with the -b switch:

$ git checkout -b issue36 Switched to a new branch "issue36"

This is shorthand for:

$ git branch issue36 $ git checkout issue36
Questions about PHP 5:

    Please write a conditional block of code that check if the variable $var exists, is not null and it's a number. 
    Answer: -exists -> isset($var) -is not null->!empty($var); -it's a number->is_numeric($var);
    Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"

Questions about CakePHP

    Which is the default path where you set up the configuration for the database? 
    Answer: for may pos application:- E:\webroot\pos\app\Config\database.php

    How you can get the value of a session variable with key "foo" using CakePHP ? 
    Answer-> $this->Session->read('foo');
    Questions about MySQL

    Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID. 
    Answer: select * from users u left join users_data d on u.ID = d.USER_ID

    Write a single query to retrieve all the queries that are currently running on the server . 
    Answer: mysql>SHOW FULL PROCESSLIST;

Questions about Javascript

    How do access to the alt attribute of the following image element using javascript? 
    Answer: document.getElementById('some_img').attr('alt');

    What is the protocol name behind ajax? 
    Answer: XMLHttpRequest (XHR)

Questions about jQuery

    Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
    Answer:- $(document).ready(function(){ $('#someElement').show(); });

    How do you remove an element from the DOM using jQuery? 
    Answer: $(document).ready(function(){ $('#someElement').remove(); });

Questions about HTML

    Which is the doctype syntax for HTML5? 
    Answer: <!DOCTYPE html>

    Which is the attribute and value required on forms to allow file uploads? 
    Answer: enctype="multipart/form-data" =>

Questions about CSS

    Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
    Answer: overflow-y: hidden

    If you have two div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one? Answer: position: relative; clear:right;

Questions about Linux / Unix based OS

    Which protocol(s) you could use to connect to a server SHELL remotely?
    Answer: ssh

    Write a command to look for the word "ads" on all files with .ctp extension in the same directory 
    Answer: $ find . -name 'ads' f -name '*.ctp'
