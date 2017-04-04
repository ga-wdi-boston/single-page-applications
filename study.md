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
A single page application is an application that uses only one markup page and has no page refreshes.  The idea behind this is that the user can seamlessly do everything the app does all on one page with no interruptions, refreshes or reloads.  For this to work, there has to be a large emphasis on client side functionality and a wide use of AJAX to handle any server-related requests.  According to the Single Page App Book, SPAs can redraw any part of the UI without a server roundtrip to get new HTML pages.  They also separate data from presentation by "having a model layer that handles data and a view layer that reads from the models."
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users say "page", they usually mean whatever UI they are seeing.  If there is a transition to a different function (i.e. browsing to a sale), that would be considered a new page.  I thought of pages in a similr way before this course.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Developers define 'views' as individual HTML fragments that perform certain functions.  Users might see them as separate pages, like an order entry screen or a product search page.  Multiple views can exist on one HTML page.  The 'view-state' refers to the view(s) that are currently showing up on the UI for the user.  Routers are mechanism that changes views, thus allowing users to change views while not leaving the page
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Some of the advantages of an SPA over a traditional web application are
more fluid functionality, getting ride of many page reloads, and transferring data rather than pages or markup.  With AJAX and JSON,
actions that would normally require multiple different html pages and many different page reloads and changes could all be completed on one single markup page.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AJAX and JSON are the primary tools behind SPAs.  AJAX sends requests to get data in JSON format from the server, essentially treating the server like an API.  This is the mechanism that allows us to change views on the same page.  Other JavaScript frameworks like angular are commonly used in SPAs as well.
```
