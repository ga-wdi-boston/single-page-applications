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
A SPA is a single-page application that allow for a better user experience
by having an updated page without refreshing. This is done by getting all
the necessary resources in a single page load - rather than incremental
post requests. Page updates are requested by the client using AJAX calls
and returned by server with JSON (as opposed to HTML).

Source: https://en.wikipedia.org/wiki/Single-page_application
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users say page, they often are referring to functionality. For example,
the order entry screen or the customer search page. My own definition
prior was based on individual html files.

Source: https://johnpapa.net/pageinspa/
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views are the html fragments that get loaded in the SPA approach - often
referred to as pages by the user. In SPA, there is a diminished role in
maintaining the view-state. The client maintains the initial HTML for the
page, HTML fragments (if requested by HTTP request), JSON data, or other
on-demand JS/CSS. The routers support the user moving between states
via browser buttons or menu items given a specific URL without a post.

Source: https://johnpapa.net/pageinspa/
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The advantages include allowing for a responsive experience for the user
without forcing page reloads to change the page as well as reducing queries
that are sent from the client to the server.

Source: http://stackoverflow.com/questions/21862054/single-page-application-advantages-and-disadvantages
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
HTML
JavaScript
CSS
JavaScript Frameworks
AJAX
Websockets

Source: https://en.wikipedia.org/wiki/Single-page_application
```
