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
<!-- a SPA is a Single Page Application.  The app is confined to one web page, however, it can have different
views within that page (log in, order form, etc...).  The word 'page' needs to be defined correctly, because it can mean
different things to different people.  For a developer, a SPA may have different "views", but they're all
occuring on a single "page", according to the user (single web page).  So, while the application may have different views, it really is only on one page, and does not need to refresh because the app downloads the HTML on the first call to the web server.

sources: http://singlepageappbook.com/goal.html, wikipedia, https://johnpapa.net/pageinspa/
-->
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
<!-- when users say "page", they mean the content contained in a box on the screen in front of them.
if they have to navigate to another box with content, then the user would believe they were looking
at a different "page"
i thought the same thing until i read these articles. i had not heard the term "views" used in the
context that it was used in the readings.  So, when i used a SPA in the past, i probably would
have assumed that when the screen changed, i was navigating to a different page. -->
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
<!-- when developers say "view", they mean the form or "page" that the user is looking at.
"view-state" seems to mean the current state of the page when the SPA is initially loaded.
the view-state needs to be preserved as is, in order for the app to be considered a SPA.
so, the page can't be reloaded/the view state cannot be changed.  the "router" helps in
this situation, which loads and maintains the page at its current state, so the user can move between
views without the page reloading and degrading performance.   -->
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
<!-- SPAs seem to have better performance, and they can be accessed in a browser, which means they
can be accessed on nearly any device at any time, without needing to be installed.  this is very
convenient to the consumer, since traditional apps need to be downloaded, and might only be available
on a specific device (smart phone, PC, tablet)
it also puts some of the work on the client, since they'll be downloading the SPA and running some of it
locally. -->
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
<!-- JavaScript, ASP.NET, AJAX, jQuery, web servers, HTML, CSS, JSON -->
```
