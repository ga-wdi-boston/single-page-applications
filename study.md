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
A Single-Page Application (SPA) loads only 1 HTML page. We'll make one trip between the client and server to get the only HTML page necessary. That HTML page will update as the user interacts with the web application. SPAs are more fluid and responsive than applications that require reloading/re-rendering.
Source: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx,
https://johnpapa.net/pageinspa/
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Before I began reading these articles, I thought of a website as a book. Everything that I could scroll through on the screen was part of a page. I could get between pages by clicking buttons.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A view reflects the content of a model. View are HTML fragments that ontain everything a user can see and touch (buttons, display boxes, text).

The view-state refers to what a view looks like at any particular point in time (which objects/methods are present at that moment and what kind of information do they contain).

Front-end "routers" let a user go from view A to view B by clicking on some kind of menu item. These routers will let the user navigate between pages without posting to the server again.

Sources:
http://whatis.techtarget.com/definition/model-view-controller-MVC,
https://johnpapa.net/pageinspa/
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs are quicker and more responsive than traditional applications. Interaction with the application results in an immediate impact on the UI.
Source: https://www.toptal.com/react/managing-view-state-with-react
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Angular, Durandal, Ember
Source: https://johnpapa.net/pageinspa/
```
