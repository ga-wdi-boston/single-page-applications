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
A SPA is a web app that follows a certain look and feel throughtout different
client/server interactions and data exchanges. Parts an pices will be dynamically
updated during user interaction, but the majority of the neccassary data is
loaded to the client's browser when they first visit the app.

(https://developers.google.com/analytics/devguides/collection/analyticsjs/single-page-applications)
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
A page will look static to a user viewing it on a browser. To them, a page is
the entierity of the webpage. A SPA page is a container for the HTML, CSS,
javascript, JQuery, etc. that the user interacts with.

Before my search to define SPAs I viewed pages as a middleground between the two;
a mostly static but updatable web app.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
To a developer, a view is how the is how the end applications looks.
View-state is a saved record of the page at the time of communication
with the server. This allows the client to maintain a coherent page during data exchange.
Routers are interactions that the user maked (like 'forward' and 'backward')
that change the state of the web page. Routers also allow the browser to maintain
a coherent page during data exchange.

(http://www.c-sharpcorner.com/uploadfile/de41d6/view-state-vs-session-state-vs-application-state/)
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
A SPA is easier on the end user. SPAs allow for high interaction with mminimal
visual change. Many complex processes can be executed without a constant update
to the view, and without massive amounts of data being exchanged between server and client.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AngularJS
EmberJS
ajax
JQuery
Meteor.js

(https://en.wikipedia.org/wiki/Single-page_application)
```
