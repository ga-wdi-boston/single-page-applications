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
A SPA is a website where one HTML page is updated dynamically in response to user actions, rather than one in which user actions transfer control from one page to another. (MSDN article, Wikipedia)
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
"Page" can mean a variety of things in different contexts, but I think generally when people say "page" they're referring to one generally-coherent-looking state of a given web application. If the appearance or function changes significantly, people will consider it a different page even if it's technically the same HTML file. This is more or less how I used the word page as well.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The view or view state in a web app is the current set of elements and data and properties to be displayed. In a SPA, the view state is a manifestation of the model, and is updated after the model is updated. Front-end routers are scripts that respond to user actions by updating the model and view state.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs allow you to more easily create a natural and fluid user experience that feels more like a native application, without frequent, jarring page switches. It also makes it easier to separate functional modules or layers for independent testing and refactoring.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
JavaScript frameworks like AngularJS and Ember.js; and jQuery, AJAX, and JSON for making server requests and transferring data.
```
