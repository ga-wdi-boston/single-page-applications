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
An SPA is an application that consists of a single html page that is updated via the client side for changes, and as a result never refreshes even as elements on the page may change.
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx,
http://singlepageappbook.com/goal.html
https://en.wikipedia.org/wiki/Single-page_application
google "single page application"
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Before this search, I considered a "page" to be a single rendered page, the layout and styles, so if the layout of styles changed, it was a new page, in my mind. (So a "SPA" would have actually had several pages in my non-developer-mind.)
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
View seems to mean something like what I thought "page" was. It's the way a rendered page looks in a specific instance. Front-end "routers" manage this view-state by hiding and showing certain elements of the html at times to change the look of the page without refreshing and re-rendering the full code.
http://singlepageappbook.com/goal.html
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Applications are more fluid and responsive--there is no need to reload pages every time a change is made. It also separates back-end and front-end work so that it's easier to completely change one without needing to change the other.
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx,
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Javascript (especially AJAX) and related libraries (jquery) and frameworks(ember.js, AngularJS),
CSS
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx,
https://en.wikipedia.org/wiki/Single-page_application
```
