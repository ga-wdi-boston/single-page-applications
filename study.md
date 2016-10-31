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
A SPA is a website based application that relies on AJAX calls to fetch new
information or submit user information.  As a result, the page does not
reload or refresh each time information is updated.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
In laymans terms, I would think of a page as what ever is loaded when I
load a web address.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A view is the part of the application that translates models into displayed content
via a rendered template.  A view-state is the current render state of the
application, including both user-interactions (whether a
a given dropdown has been toggled, for example) and model information
(whether a given collection item has contains new infromationl)
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs give developers freedom to create more dynamic, richer user experiences.
Because the developer need not reload the entire page each time new information
needs to be rendered, the developer can create more complex, "heavier" user
interfaces. Moreover, The developer can create UIs that keep the user engaged
by providing infromation about the state of asynchonous operations.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AJAX, JSON, Web Storage, front end JS Frameworks (Ember, angular).
```
