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
Used the links provided and watched https://www.youtube.com/watch?v=pNDDf-yh2bE
this interview with john papa about SPAs. A SPA is a web app that does not
require refreshing in the browser to update the page after user interaction
occurs. Code can be delivered and shown as a 'view' instead of actually going to
the url, and the server can even cache these resources temporarily instead of
having to make multiple requests for the same data if the user wants to close
and reopen a certain portion of the page.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before you started
your search to define SPAs?

```md
When non-developers use the word 'page' they are usually referring to a portion
of a web site. They may mean the FAQ page or Help page, when they think of the
collection of pages as the whole site. This is how I would have referred to it
as well before the past week or two.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views represent the chunks of HTML that can be requested from the server and
delivered to the client without refreshing the entire application. These can be
thought of as sections of a page but more than one can also be visible at the
same time. Each view has a view-state meaning that it may or may not be
visible to the user at any given time. Routers take the input from the user and
route it to the resource attached to it. If the information hasn't been
requested it will do so with HTTP, or if it has already it can route it to that
memory that was saved from the previous call.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The most obvious advantage is that your app doesn't need to completely refresh
to update with a response to user input. Another advantage is that it allows you
to keep your code separated which makes it easier to re-use and debug.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AJAX is a great tool in building SPAs because it allows you to request data
from the server and get it back without having to refresh the page entirely.
Javascript with Jquery makes this easy to implement with HTML5.
```
