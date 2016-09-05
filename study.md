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
A SPA is an application that only loads/refreshes the page one time, at the
start of the application. There is only one call to the server to fully render
the HTML of the page. Every other action can modify the application in some
way, and it may even call the server multiple times, but a full page reload is
never made.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users say "page", they typically mean "views" or "states"; essentially what
an application looks like with one set of content on a screen. I had the same
definition before this study.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A view essentially matches the definition of "page" given above. It's what the
user can see at a given time on a webpage. A single page application can have
many views/view-states that can give the same feel as a multi-page application
without the need for a page refresh. Routers help manage view-states by
showing the view-state that corresponds to a particular menu item when that menu
item is clicked.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
One of the most important advantages is the reusability of both the client side
and server side codebases. Because the front end is only making making calls for
data from the API after the initial page load, both the front end and the back
end can be used with other back ends and front ends, provided the essential
function calls exist. This can lead to very maintainable code, as well as
potential for greater reusability.

The absence of full page reloads also gives the app a more native feel, which
leads to a more enjoyable user experience and greater performance, as round-trip
server requests are not necessary with every click.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AJAX, jQuery, and frameworks like Angular.js and Ember.js are often used to
create single page applications.
```
