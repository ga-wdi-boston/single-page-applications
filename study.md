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
An SPA is a Single Page Application. It means that the page dynamically updates itself
without reloading the HTML "framework".
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Page means each instance of a website reload and every page that is loaded when they click
a link to non-developers. What it means in a SPA is the page that
is initialy loaded from the single round trip to
the server, it is the framwork.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views are anything the user sees. These can change when users click links, but the page does not do a
full HTML reload. Only the chunk of data that is needed is sent between servers. Routers manage this chunking
of HTML and even store and load views from a local cache.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Because the app only loads the data it needs to load it reduces round trip data transmissions between servers.
It also offers the smoother more "modern" experience of todays apps. Also, using the dom and jquery to manipulate
nodes makes it easier for developers to make pages more dynamic. 
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Jquery, api's frameworks and AJAX, so far as I can tell, are the main tools used to create SPA's.
Perhaps HTML5 and CSS3 can also be included in this toolbox?
```
