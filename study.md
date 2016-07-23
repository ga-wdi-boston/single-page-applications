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
A single page application is a web app which loads a single HTML page initially,
then updates that page using AJAX to create multiple views without refreshing the
page. I referenced the readings.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users say page they mean the unique view that is currently shown in the
browser window. It is often assumed that this is a separate HTML page loaded by
the browser. This is how I thought of pages for the most part before these readings.
I was aware of SPAs and even had some understanding of views, but I was confused
what the difference between a page and a view was exactly.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
When developers say "views", they mean the "other pages" on the site, or at least
how a user would think of it. The different views are the different things the user
sees. View-state is whether a certain view is currently visible or not.
Routers help manage view-state by allowing users to navigate between views.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs do not need to make a call to the server for every action the user takes,
which allows the back-end to focus on storing, updating and providing data.
This allows the creation of web applications that do not need to constantly
reload the browser.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AJAX is the most commonly used technique in creating single page apps.
WebSocket is a protocal that is also used, which offers superior performance to
AJAX. Front-end frameworks such as Angular, Ember and React simplify the development
and testing of SPAs by providing a Model-View-Controller or Model-Vew-Viewmodel
architecture.  
```
