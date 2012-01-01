Complete Google App Engine + Backbone.js + Require.js Todo list Web App Example
===============================================================================

Based on the work of Thomas Davis (http://backbonetutorials.com/) and Jérôme Gravel-Niquet (http://jgn.me).

Presentation and a code walkthrough can be found here: http://www.slideshare.net/ronreiter/writing-html5-web-apps-using-backbonejs-and-gae

### Introduction

Here you can find a fully working example of a Todo list web app which uses REST API to communicate with its back end. The app uses:

* Google App Engine (Python) for its back end
* Backbone.js for the MVC framework
* Underscore.js for templating and Backbone.js
* Require.js for modularization

This web app can teach you a lot just by reading the source code. It's a great boilerplate to start heavy web apps, which require a back end and modularization. For example:

* How to implement a simple Todo model, and a REST API interface using Google App Engine in Python
* How to configure Backbone.js to sync with a back-end
* How to configure Require.js and use Backbone/Underscore/jQuery as AMD modules
* Templating using underscore.js - conditionals and HTML escaping
* Loading text files and using them as templates using Require.js
* MVC programming using Backbone.js
