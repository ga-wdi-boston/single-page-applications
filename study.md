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
According to the Microsoft Dev Network, a single page application is one that uses only a single page of HTML and dynamically updates that page as the user interacts with it.  The webpage uses AJAX requests to get new information from the server without refreshing the webpage.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users generally mean whatever is on the screen at a given point when they say page.  When that information changes, that means a new page has opened.  To me, I generally called one profile on facebook or one entry on wikipedia a page.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views are what the users in the previous question meant when they said "pages".  They are the different ways that a SPA can present data or inputs to the user.  A view-state is one of these views, and needs to be defined because the dev needs to model each view-state so that they can program it properly.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
One of the biggest advantages of a SPA is that most of the work is handled client-side.  The server will still provide resources to the client in the form of JSON strings or objects or something else, but it won't need to provide HTML or CSS like it did traditionally.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
One of the most important tools used to create a single page application is the DOM.  The DOM allows the HTML on the page to be modified by Javascript and CSS which allows the SPA to look drastically different in different view-states even though the core HTML remains the same.  Ajax requests are another important tool because they can obtain the resources from the server that the client needs in order to make the changes the app needs for each view-state.  Ember.js and Angular.js are other JS frameworks that allow the dev further ability to make effective and functional SPAs.
```
