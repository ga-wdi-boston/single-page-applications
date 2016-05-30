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

## Define "single-page application" (SPA)

In your own words, define what a SPA is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
An SPA is a single page application, where all resources are retrieved by a
single page load and the page does not refresh everytime a user action is taken.
This makes the experience more fluid, data can be retrieved or sent to the
server without reloading the page.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
A user might consider a page to be a particular view that they are seeing, when
the view changes they assume it is a different page. This is what I considered
a page before my search into SPAs, but now I understand that the application
may be one page that is manipulated and changed based on user actions.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
View is a representation of the current model that a user is interacting with
in our application, it 'observes' the model and then changes the DOM and renders
a reflection of the new state. The view state can hold information and we can
move between different views on the front end.

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional application?

```md
Single page apps separate the data from the presentation of data, and can change
the UI without reloading the HTML everytime we can to change view state. They
are more fluid than a tradition application and don't need to query the server
over and over again throughout use.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Javascript frameworks like AngularJS, ember.js, meteor.js
Ajax is used to query the server

```
