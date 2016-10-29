# Single-Page Applications Study

Use your favorite search engine to research and answer the following questions
(no prior knowledge is expected). Strive for understanding the definitions
themselves, since you may be asked in an interview to define "single-page
applications" (SPAs) in your own words.

All your projects in this program will be SPAs, so you'll likely internalize
this defintion over time.

It might be a good idea to come back to this later and see if you'd still answer
in the same way! If you have a blog you're using to journal your experience
becoming a web developer, this might make a good article.

## Readings

-   [MSDN Single Page Applications](https://msdn.microsoft.com/en-us/magazine/dn463786.aspx) (Stop at 'Creating the Visual Studio Project')
-   [Modern Web applications overview](http://singlepageappbook.com/goal.html)
-   [Wikipedia](https://en.wikipedia.org/wiki/Single-page_application)
-   [SPA and the Single Page Myth](https://johnpapa.net/pageinspa/)

## Define "single-page application" (SPA)

In your own words, define what a SPA is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
SPA stands for 'single-page application' and it's functionality is contained
in it's name: a SPA loads a single HTML page with AJAX used to get info from the
server. If a user interacts with the page, the HTML and CSS are changed
dynamically by Javascript. Thus, only a single 'page' is ever loaded, and no
new HTML pages are used to refresh the website/are requested from the server.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
A page to a non-developer typically refers to the state of an app at a particular
time or a website on the screen. Using Twitter as an example, even though it is
a SPA, a standard non-developer user would refer to each link on the navbar
(once they click it) as a seperate 'page'.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The view is what a user of a website can see visually see and interact with
on a particular website at the current moment they are using it. View-state,
however, is the current 'state' of the web application with regards to all past
events and past data that have been modified and passed to the web application.
Front-end routers help manage the view-state by allowing the user to go from
one particular view to another by interacting with the webpage.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
One large benefit of an SPA is not requiring frequent page loads and refreshes.
The less code and data that is being loaded/requested/presented the better, as it
improves the speed of a website. Further, a SPA is typically easier for a user
to interact with as it's functionality is much more like a desktop application.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Tools frequently used to make SPA's include AngularJS, Ember.js, Meteor.js,
React.js, Ajax, and websockets. There is an ever increasing amount of new tools
available for this kind of developing as well.
```
