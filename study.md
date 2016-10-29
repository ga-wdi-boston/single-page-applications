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
A Single Page App basically allows for an html page to be loaded once and for all further action
to occur without having to refresh the page.  And example would be in a web page that is served up
once to the client and all interactions after its initial load to be handled by AJAX requests and JSON
responses.

RESOURCE: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
To a User A page typically refers the web page as rendered.  Multiple page sites require multiple calls to the server.
This was also my understanding and when I heard the term SPA I visuallized one single long page that
contained all of the data a User wished to view or interact with.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
To developers a 'view' can still entertain the concept of different pages but not in practice.  Instead
of entire html pages that delivered constantly by a web server they are html fragments that may be presented on the client side. A view can be handled by a router as a 'view state' so that when a User visits a 'view' and navigates away it can be returned by the router without having to initiate another call to the server.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
An SPA delivers its resources (i.e. css and html) may be delivered once to the client and all further interactions are data driven. It is faster and is less taxing on the server side. After delivering the initial page load it only needs to be concerned with handling the JS requests and JSON responses.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Some common tools are Angular JS, Ember JS, and Meteor.js.  
```
