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
A SPA is a web page where all resources used for a web app are loaded during the
use of a single web page. This single web page serves as an application similar
to apps installed on an OS.

Source: Wikipedia.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
In the web context, a page contains everything a user can explore (by scrolling,
 etc) without following a link to another page. By page, most users mean
 everything they can explore by vertically scrolling through a page, without
 following any links.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
View: what the user see on their screen. It is "stateless" after its already
loaded.

View-state and the router: The view-state is the state of page during page
loading that is true at a given point in time. The router reads the view state
and judges what needs to be loaded.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
No page loading is required during the use of an SPA. Once the page is loaded
the first time, the user experience is seemless as far as not having to load
pages to see different content or perform tasks.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
HTML, JS, Jquery, JSON.
```
