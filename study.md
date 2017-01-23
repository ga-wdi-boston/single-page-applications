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
A Single Page Application is a web app that only loads the page once.  Any changes to the page are made using javascript and web requests with AJAX, instead of refreshing the page.  This gives the application a better user experience; it would be annoying if the page refreshed every time a change was made.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users mean that if they click something and it opens up a window with new content, the new window is a page.  A Single Page Application is called single page because it doesnt ever refresh the page, so it appears to the user as a single page.  It can actually reference many pages, but the content from them is dynamically loaded onto the page so it does not refresh.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The 'view' is one of the pages referenced by an SPA.  The page can switch between many views, and the one that is currently in use is called the 'view-state'.  A router helps by loading the correct view-state based on user action.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPA's don't need to make as many requests to the server as traditional apps because they don't refresh the page.  This will decrease data usage and increase loading time of the app.  Also, the user will have a more pleasent experience because the app will feel more polished.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Javascript, AJAX, and JSON are used to help the browser communicate with the server and asynchronously make web requests.
```
