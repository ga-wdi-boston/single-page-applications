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
Using the above listed sources as a guide, an SPA is an web-based app where the initial HTML
load is dynamically updated on the client side as users interact with it. While the app relies on the server to pass resources at different points, most of the heavy lifting (running JavaScript to dynamically update views etc.) is managed on the client side.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users talk about a "page", they typically mean a view that takes up most/all of the browser window and allow a user to see/do different things. Before reading about SPAs in more detail, my definition would have been similar. Now I understand that what developers refer to as "views" is consistent to what a user may call a "page".
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A view is an HTML fragment that presents specific information/functionality to a user. If a view commands the user's full attention, a developer may call that a "page", but there can be multiple views visible at one time. A view-state is what a particulr view looks like at a point in time in your browser. A router assists with loading the correct state of a view when a browser is refreshed, or when a view is bookmarked.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPA's provide a more seamless user experience with few, if any, page refreshes. All functionality of an SPA is idependent from the technology used for the backend. The service technology could be swapped out with no impact to the SPA as long as the API remains the same.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
JavaScript, HTML, CSS, Ajax, AngularJS, Ember.js, APIs, JSON
```
