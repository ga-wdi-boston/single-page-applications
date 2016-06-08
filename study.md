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

## Define "single-page application" (SPA)

In your own words, define what a SPA is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
A SPA is a web application designed to be loaded a single page, in order to
reduce the need for page reloads client-side, and allow for many variations on
ui presentation and manipulation without requiring a multitude of urls
server-side. It also allows the entire front or back end to be refactored
without requiring new changes to the other end. Sources: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx,
http://singlepageappbook.com/goal.html
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Typically I think most people just refer to a stable display of information as a
single "page", even though their multiple pages might just be a single page web
application displaying different states.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A developer would use view as a rendering of the underlying information from the
model. This use would allow view-states to mean multiple interpretations of the
model, and the front-end router would be the means by which to navigate through
these states. The key point is that the model should rule over the views.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
No page reloads needed, able to refactor client and server separately, easily
control all presentations of the controlling model.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
HTML, CSS, JavaScript, JSON, JQuery, AJAX, server architecture.
```
