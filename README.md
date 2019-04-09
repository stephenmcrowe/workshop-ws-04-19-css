# CS52 Workshops:  Introduction to Bootstrap

![](http://i.giphy.com/eUh8NINbZf9Ys.gif)

Brief motivation here as well as in presentation

## Overview

We're going to show you how to quickly put together a website with basic components using the component library Bootstrap. After completing this tutorial, you should have a working, locally hosted website with…
* A Nav Bar
* Jumbotrons
* Buttons
* Column based text
* A carousel of images
* Responsive design
* Minor customization


## Part 1: Setup + Creating a Locally Hosted Webpage

Create a new folder. Locate that folder, and create empty HTML and CSS files in it using your text editor or the command line:
```
touch index.html styles.css
```
Open these files in a text editor. Just like Short Assignment 1, fill ```index.html``` with some basic HTML content.
```
<!DOCTYPE html>
<html>
   <head>
       <title>Bootstrap Demo</title>
   </head>
   <body>
       <h1>Hello, World!</h1>
   </body>
</html>
```
Next, locally test the mini web page you just created.
For Python 2:
```
python -m SimpleHTTPServer
```

For Python 3:
```
python -m http.server
```

Visit http://localhost:8000 to see your page running. Your code should look something like this:
![screen shots are helpful](images/basic-webpage)

## Part 2: Build Using Bootstrap
Great ~ now that you have a basic webpage hosted, let’s get building! :sunglasses:

### A little background on Bootstrap (optional):
Bootstrap is a component library, which is an awesome tool because it performs a lot of styling work for you. Instead of having to build components like full-screen background images and image carousels using all kinds of nested divs and spans, Bootstrap does the work for you in pre-set classes! Some useful classes to know about include:
```jumbotron```
```btn```
```.btn-group```
```glyphicon```
```dropdown```
```collapse```
```navbar```
```form-group```
```modal```
(See [here](https://www.w3schools.com/bootstrap/bootstrap_get_started.asp) for more information).

Additionally, (as we discussed) Bootstrap operates on a 12 column grid system. Using Bootstrap, you can use classes to define the space you want a component to take on the screen.
```
class=“col-[device size]-[number of columns]”
```
where ```device size``` is ```xs, sm, md,``` or ```lg``` depending on the device, and ```number of columns``` is a number. A caveat here is that the number of columns for every horizontal row should always add up to 12 maximum or else elements will stack.

You can define that space to be different on multiple devices using a class definition like this:
```class=“col-sm-[number of columns] col-lg-[number of columns]”```
This is awesome because it makes responsive design way easier!

### A little background on Bootstrap (optional):



## Step by Step

* Explanations of the what **and** the why behind each step. Try to include:
  * higher level concepts
  * best practices

Remember to explain any notation you are using.

```javascript
/* and use code blocks for any code! */
```

![screen shots are helpful](img/screenshot.png)

:sunglasses: GitHub markdown files [support emoji notation](http://www.emoji-cheat-sheet.com/)

Here's a resource for [github markdown](https://guides.github.com/features/mastering-markdown/).


## Summary / What you Learned

* [ ] can be checkboxes

## Reflection

*2 questions for the workshop participants to answer (very short answer) when they submit the workshop. These should try to get at something core to the workshop, the what and the why.*

* [ ] 2 reflection questions
* [ ] 2 reflection questions


## Resources

* cite any resources
