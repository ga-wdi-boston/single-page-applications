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
A Single Page application is only ever served one html file from the backend server. That file is consumed by the DOM.  All subsequent changes to the page are made by injecting new html and css (via front-end javascript) into the existing page. Only data (usually JSON by way of ajax calls) passes back and forth from the server after the initial html file is served.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
I think when users refer to a 'page' they mean web-content with a unique url.  Or if they aren't paying attention to url, maybe they simple mean differentiated web-content (new html structure, etc.) that they can navigate between by clicking a button or link, etc.  Traditionally, each different page was a unique html file served from the backend. Now I think of a page as more of an abstract concept. A page, now, is probably more differentiated by where it fits into the user experience.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
I think of a view as representing the state of the server-side model, which each view handling a different part of the user experience. Front end routes mimic changing urls (which used to occur as different html files were served), to ground the user as they 'navigate'. I could use more clarification on this.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
A single page application provides a fluid user experience, without the jarring experience of refreshing a page. It also seems more elegant and less tedious for a developer, because javascript does more of the work for you, and you avoid the repitiion of creating a bunch of potentially similar static html pages.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
React.js, Ember, Angular
```
