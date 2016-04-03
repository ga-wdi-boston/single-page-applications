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
A SPA is a web application that runs off a single HTML page and is dynamically updated (without the page reloading) as the user interacts with it, using AJAX and JavaScript.
Source: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users (including me before I started this study) think about 'pages', they likely assume that every time the page looks different, they are seeing a different HTML page.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
"View" is the only part of the application that the user interacts with. It is an interactive UI that contains data bindings, events, and behaviors. "View state" refers to the method used by ASP.NET applications to preserve page and control values between page reloads.
Sources: https://msdn.microsoft.com/en-us/library/bb386448.aspx,
https://webcache.googleusercontent.com/search?q=cache:mswFIHcHRIMJ:https://masteringmean.com/lessons/636-Understanding-the-Singlepage-Application+&cd=1&hl=en&ct=clnk&gl=us

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs make for a more fluid and responsive UI since the page never has to reload and re-render. Using a SPA also allows a separation between the HTML and application logic, making it easier to edit each layer.
Source: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
* JavaScript libraries:
  - Knockout.js
  - Ember.js
  - Angular.js
  - Meteor.js
* Ajax
Sources: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx, https://en.wikipedia.org/wiki/Single-page_application
```
