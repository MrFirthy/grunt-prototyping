Grunt Prototyping
=================  

A grunt project for rapid prototyping using serve, less watch, and live reload.


PLEASE NOTE: This project is based on Tangent Snowball's house styles repo which you can find HERE. The project uses LESS as it's pre-processor of choice. If you would like to remove this (or switch to SASS/Stylus), simply update the Grunfile accordingly.  

## Setup  
  
The following needs to be completed before you can use this repository:

+ Install Node ([Direct download](http://nodejs.org/download/))  
+ Install Grunt `npm install -g grunt-cli` 

Once these have been installed, clone the repository and `cd` into it. Then run:  

`npm install`  

A node_modules folder will be created. (**Please Note:** It is advised that the _node_modules_ folder be added to the `.gitignore` of any project you create using Grunt as it will be created by each user individually via `npm install`)  

You're good to go! Just run:

`grunt`  

and you're golden.    

---
  
Once Grunt is running, it will automatically open a tab in your default browser, and from this point on changing any LESS, JS, or HTML files will results in:  
  
+ Recompiling and compressing of styles  
+ Refreshing of the page to show changes  

**Side note:** This project uses LESS as it's CSS preprocessor. If you would like to remove it, or replace it with an alternative like SASS or Stylus, update `Gruntfile.js` to reflect this (documentation is too long to list for every possible alternative, but [NPM](https://www.npmjs.com/) will contain instructions on adding each).

---

## Questions  

If you find anything wrong with the plugin, have issues getting it working, or think of something cool it could do, feel free to submit an issue.