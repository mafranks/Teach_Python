# Variable Types

In Lesson 1, we printed out some strings.  Some of those were typed by us and some of them were stored in variables.
Printing is useful for displaying information to the user and also for providing some quick feedback while troubleshooting.
We can see that our variables are strings by using the type() function.

![Screenshot](./type_screenshot.png)

> NOTE: In IDLE, you could just use ```type(name)``` but I want to get in the habit of using ```print(type(name))``` because I'll shortly be transitioning to the Visual Studio Code IDE where using ```type(name)``` will produce an error.

As you can see, our variable has a type of string.  What other variable types are there?  Python has five standard data types.  Let's take a quick look at all five. We'll cover them all over the course of the next few lessons.

* Strings
* Lists
* Dictionaries
* Tuples
* Numbers (more in depth below)


Demonstration:

Show examples of strings, lists, dictionaries and tuples and use ```type()``` to prove it.

"Michael Scott"

["Michael Scott", "Dwight Schrute", "Angela Martin"]

{"name": "Michael Scott", "title": "Regional Manager", "branch": "Scranton"}

("Michael Scott", "Dwight Schrute")

# Numbers

There are three different types of numbers:

* int (integers)
* float (floating point numbers)
* complex (complex numbers)

> NOTE: long was a number type in Python2 but has been deprecated in Python3
