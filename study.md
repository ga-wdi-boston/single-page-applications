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
An SPA is a single page application, which is built on the premise that application logic will be performed on the client side instead of the server side.  The server acts to send data while the client side compiles, which allows for the page to continually update without the page reloading.  AJAX or client side frameworks will be used to send requests to the server, and the raw data will be returned and updates to the DOM will occur from the client side.
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
https://en.wikipedia.org/wiki/Single-page_applicatio
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
To a non-developer, a webpage would be a static page that does not fundamentally change, apart from simple on screen changes.
https://johnpapa.net/pageinspa/)
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Developers refer to a view as a point that commands the entire view of the screen.  The view-state is just one point in the viewing of a page that can have many different states.  The SPA only means that only one page is loaded from the server, and from that point onwards, the server acts to provide data while the client makes view changes.
Front-end routers allow the user to switch between views, with arrows, menu option, buttons, scrolling, etc.
https://johnpapa.net/pageinspa/)
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
An SPA allows for complex and rich view changes on a webpage without any page reloading neccessary.  This allows for seamless changes to the view-states.
https://johnpapa.net/pageinspa/
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
<AJAX, Anglular.JS, Ember.JS.
https://en.wikipedia.org/wiki/Single-page_application
```
