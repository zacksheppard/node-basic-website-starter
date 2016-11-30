# Basic Website template

This is a template to help me create a basic website that will only need HTML, CSS, and JS. It's goal is to reduce time starting a project but also to encourage using babel, SASS, grunt and other helpful tools as well as best practices. I also get tired of tracking down references to all my favorite best practices so a subgoal is to use and reference those here.

## Setup

1. Fork this repo
2. `npm install`
3. `git init`

### Serving up pages

To serve pages you can use [http-server](https://github.com/indexzero/http-server) as this does not have an http server installed currently. 

## Tools used

* [Grunt](http://gruntjs.com/): Uses grunt watch, cssmin, uglify (for JavaScript), and jshint
* [SASS](http://sass-lang.com/guide)
* [Babel](http://babeljs.io/)

## Best Practices referenced

* [The SASS Way](http://thesassway.com/beginner/how-to-structure-a-sass-project)
* [Scalable and Modular Architecture for CSS (SMACSS)](https://smacss.com/book/categorizing)

To fascilitate sticking to the SMACSS principlies, SASS files point to the reference material and summarize some of the common rules that it's good to have on hand. These are in SASS comments that don't get compiled.