# Resources
Resources for HTML / CSS / SASS / JS / Python / Django

# Starting from Zero / Little Programming Experience
[CodeSchool](http://codeschool.com) is an excellent all around resource ($29/month as of this writing) with PDFs, video lectures and interactive quizes. Here's my suggested foundational courses:
* [Git / Github](https://www.codeschool.com/learn/git) - do all the courses there. It won't seem important at first but once you get going using Git for verson control is going to make life so much easier for you. And once you get some other skills under your belt you're going to want to be checking out other people's code on github and pulling it down and trying it out, etc. This is also a gentle introduction to becoming comfortable using the command line which will quickly become your new best friend.
* [HTML / CSS](https://www.codeschool.com/learn/html-css) - do all HTML, CSS and SASS courses (skip bootstrap, SVG and design unless you want more). After completing these you should feel comfortable making a simple web page and viewing it in a browser as well as viewing source in the web inspector and modifying code on other sites.
* [Javascript](https://www.codeschool.com/learn/javascript) - do all Javascript and jQuery course (skip front end frameworks, NodeJS and Coffeescript unless you want more (then check out Node first)). After this you should feel comfortable adding some JS to your HTML pages to build out dynamic elements and should know how to select any element in the DOM via jQuery (or regular JS) - and you should actually know what DOM stands for and how it works. You should be able to open up the JS console in web inspector and really mess with sites now.
* [Python / Django](https://www.codeschool.com/learn/python) - do all courses here. At the end of this you should be able to dive into the official [Django tutorial](https://docs.djangoproject.com/en/1.10/intro/tutorial01/) and begin reallying getting into things.
* [SQL](https://www.codeschool.com/courses/try-sql) - do all courses here. At the end you should be able to write select statements with joins across tables and be ready to try more advanced queries.
	* [Postgresql](https://pgexercises.com/questions/basic/) - do at least "basic" and "joins and subqueries" sections - this will be a good test to make sure you absorbed everything from the code school course and will introduce some of the differences in Postgresql vs other SQL languages (we'll be using Postgres with Django)
* [BASH](http://guide.bash.academy/) - do chapters 1 and 2 (rest is bonus if you really want to dive in). This is to get you familiar with the command line and basic BASH scripting. This comes in handy not only when developing locally but when setting up and configuring servers (which will likely be running Ubuntu linux which you'll interact with entirely via command line).

# General
* [Pycharm (free community edition)](https://www.jetbrains.com/pycharm/download/) Best python IDE (fully support all front end coding as well)
* [Git / Github](http://github.com) Become familiar with git and github. You should be comfortable forking a repo, cloning it locally, working on feature branches for each task you work on, pushing up to your forked repo, rebasing and making pull requests
	* [Intro to git](https://try.github.io/levels/1/challenges/1)
	* [Official Git docs](https://git-scm.com/documentation)
* [Gulp](http://gulpjs.com/) front end build system


# HTML

## Basics
* [MDN HTML reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* [MDN HTML5 Reference](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
* [HTML5 Boilerplate](https://html5boilerplate.com/) a look at best practices for a modern HTML page - good to look at when setting up the base templates for a project


# CSS / SASS

## Basics
* [Official SASS Docs](http://sass-lang.com/documentation/file.SASS_REFERENCE.html)
* [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
* [What are EMs?](http://zellwk.com/blog/media-query-units/) - we'll be using `em` units (instead of `px`) almost everywhere so become familiar with how they work and why we'd use them

## Style / Syntax
* when in doubt follow the [AirBnb CSS / SASS Styleguide](https://github.com/airbnb/css) which the exception that we'll always use 4 spaces as indentation *everywhere*

## Misc
* [CSS Tricks Blog](https://css-tricks.com/) great blog with answers to a lot of common questions
* [Font Awesome](http://fontawesome.io/) we'll use this icon font for most of our icons


# Javascript

## Basics
* [Official JS reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript) (protip: add `MDN` to your google searches about JS questios to make sure you get links to the offical docs vs w3 schools or other sources of varying quality)
* [Understanding JS Closures](https://javascriptweblog.wordpress.com/2010/10/25/understanding-javascript-closures/) understanding this is fundamental to JS otherwise you'll be battling scope issues with keyword `this`
* [Eloquent Javascript](http://eloquentjavascript.net/) - book that will introduce you to JS

## Style / Syntax
* when in doubt follow the [AirBnb JS Style Guide](https://github.com/airbnb/javascript) - our style will match very closely (major exceptions being we'll use 4 spaces as tabs *everywhere*)


## Revealing Module Pattern
* This whole book is worth reading but we make use of the revealing module pattern in all of our JS so be sure to read up on it specifically [Revealing Module Pattern](https://addyosmani.com/resources/essentialjsdesignpatterns/book/#revealingmodulepatternjavascript)

## Misc
* [List of free JS books](http://jsbooks.revolunet.com/)
* [Can I Use?](http://caniuse.com/) - check browser compatibility for newer js, css and html
* [ES6 Compatability Table](https://kangax.github.io/compat-table/es6/) what ES6 (latest JS standard) features are supported by what browsers?
* [JS resources and podcast](https://www.javascript.com/resources)
* [Udacity JS Course](https://classroom.udacity.com/courses/ud015/lessons/2593668697/concepts/29558186840923)


# Python

## Basics
* [Official Docs](https://docs.python.org/3/) (make sure to choose the version of python 2.7 / 3.x as appropriate)
* [Using pip](https://docs.python.org/3/installing/index.html) the official python package manager. Be comfortable looking up pacakges on [pypi](https://pypi.python.org/pypi)
* To isolate python environments between projects (so project A can have v1.5 of a package and project B can use v3.2, etc) see [Virtualenv](https://virtualenv.pypa.io/en/stable/) and [Virtualenvwrapper](http://virtualenvwrapper.readthedocs.io/en/latest/) (also note that in python 3 `venv` is now a part of the language so if using python 3 see [venv](https://docs.python.org/3/library/venv.html))
* [Classes in python](https://docs.python.org/2.7/tutorial/classes.html)
* "Magic Methods" e.g. `__init__`, `__new__`, etc (have double underscores by convention) here's a list of all the major ones and explaination of them: [Python Magic Methods](http://www.rafekettler.com/magicmethods.html)
* [Anonymous functions](http://www.diveintopython.net/power_of_introspection/lambda_functions.html) (lambda functions) 
* [Python 2 vs 3](https://wiki.python.org/moin/Python2orPython3)

## Style / Syntax
* [The Zen of Python (PEP 20)](https://www.python.org/dev/peps/pep-0020/) a good primer on the philosophies behind python
* Python's official style guide [PEP 8](https://www.python.org/dev/peps/pep-0008/)

## Misc
* [List of free python / django books](http://pythonbooks.revolunet.com/)


# Django

## Basics
* [Django philosophies](https://docs.djangoproject.com/en/1.10/misc/design-philosophies/) Django is an opinionated framework so it's import to understand it's viewpoint on development.
* [Official Django Docs](https://docs.djangoproject.com/en/1.10/) Bookmark this as you'll be coming back to it all the time. Each section of django from models to views to the admin panel has a section here with basic details and advanced info as well (always note what version of docs you're viewing vs what we're using in a project as things can change)
* Work through the [official tutorial](https://docs.djangoproject.com/en/1.10/intro/tutorial01/) to get a feel for the major pieces of django and how they work together

## Cookiecutter Django
* Once you get the hang of django from the above tutorials and begin to wonder "what's the best practice for X?" look here. Created by one of the core django developers, this is a quick and easy way to get a django project started with a bunch of best practice settings and configurations already in place [Cookiecutter Django](https://github.com/pydanny/cookiecutter-django) - try making a new project with it and explore the settings and structure - there's a ton of really helpful comments in there to help you understand why they made the choices they did. 

## Django Rest Framework (DRF)
* We'll use this to make our REST APIs - go through the tutorial and get a feel for all the nice options this gives us for making APIs easily [DRF](http://www.django-rest-framework.org/)
