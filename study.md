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
A single-page app at the highest level is a single HTML page that is updated
as the user interacts with the page. Javascript and CSS handle refreshing the
page as well as talking to the back end server. All this is seamless to the user,
where the page is updated(via DOM) only as needed with the help of javascript and css,
front end has no dependency on the back end for how the UI acts.
The communication to the backend is typically done with the jquery library using
ajax and json objects. Javascript passes json objects to ajax, which then sends
the request to the backend server.  Reponses are sent back via another json object.
Javascript then acts on this return object and updates the client as required. This
has a side affect of separating the client from being dependent on backend. The
backend can change(api stays the same) and the client still works as expected. This
also works the other way as well, the backend does not depend on the front end.
The designer can change the front end and this has no impact on the backend.

https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
http://singlepageappbook.com/goal.html
https://en.wikipedia.org/wiki/Single_responsibility_principle
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users I believe think of a website as a collection of pages, which is what the
boat I was in before reading these articles.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The view is what the user sees. The view state is contained in withing the
DOM.
FE-routers update the URL as the user nagivates in a SAP. The router manages
the state of the app, where each feature of the app is defined as a state. The
router managers the transitions between states.

https://ui-router.github.io/about/
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The main advantage SPA has over traditional apps is the whole page is not refreshed
each time a change is made. SPA only updates those parts of the page that
require updating, by manipulating the DOM. It also separates the client from
the backend, either can be changed and work as expected.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
JQuery, Angular, Ember, JSON, HTML5, CSS, RAILS
```
