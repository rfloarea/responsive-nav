# How to Create a Responsive Navigation Bar

## Tools and Resources
Used [this tutorial](https://www.freecodecamp.org/news/how-to-build-a-responsive-navigation-bar-with-dropdown-menu-using-javascript/) by [Vistor Eke](https://github.com/Evavic44/responsive-navbar-with-dropdown) as a guide.

Used [boxicons](https://github.com/atisawd/boxicons).

## Overview
This project will guide you through the steps to *learn* how to create your own responsive navigation bars. I will not focus on making things too pretty. That will be your job. Something you can do to take this project further and make it your own. I'll also keep the complexity to minimum where ever I can.

Important note, this is a work in progress.

That's all! Let's make this thing!

## Phase One: HTML
**Step 1**
Let's just generate some basic boiler html. Might as well make a css file and link that in the head. Your html file should look like this.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Nav Bar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
</body>
</html>
```
**Step 2**
Now let's make create some html elements. I'm going to create sections or containers for our nav bar. Three of them actually. Between our `body` element tags, let's add some stuff.
```
<header>
    <div class="left-nav"></div>
    <div class="mid-nav"></div>
    <div class="right-nav"></div>
</header>
```
The reason for this will become apparent as we go.
By the way, if you're using some version control system, this would be a good time to commit.