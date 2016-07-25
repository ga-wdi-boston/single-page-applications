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
SPA is single page application, which means only change a small part of the UI instead of refreshing the whole page.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
an Application that only has one page.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
view means the other pages except the first page rendered from the server.
Every time we get a page it's a new page so we use view-state to preserve the value of tha page and controls.
Router allow the user to navigate different views. If the view has been seen before, router will not make the request to retrieve HTML.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPA is faster and more security because it separates the UI and data.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
JavaScript frameworks, Ajax, JSON and XML
```
