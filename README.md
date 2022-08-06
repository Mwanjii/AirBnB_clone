# AirBnB clone - The console

![hbnb-screenshot](https://github.com/lroudge/AirBnB_clone/blob/master/img/hbnb_screenshot.png)

## Description
This is the first step towards building your first full web application: the *AirBnB clone*. This project will be augmented with the following projects: HTML/CSS templating, database storage, API, front-end integration…

## Usage
The command interpreter works both in interactive mode and non-interactive mode, much like a Unix Shell.

Interactive mode
`
    $ ./console.py
    (hbnb) help

    Documented commands (type help <topic>):
    ========================================
    EOF  help  quit

    (hbnb) 
    (hbnb) 
    (hbnb) quit
    $
`


Non-interactive mode
`
    $ echo "help" | ./console.py
    (hbnb)

    Documented commands (type help <topic>):
    ========================================
    EOF  help  quit
    (hbnb) 
    $
    $ cat test_help
    help
    $
    $ cat test_help | ./console.py
    (hbnb)

    Documented commands (type help <topic>):
    ========================================
    EOF  help  quit
    (hbnb) 
    $
`