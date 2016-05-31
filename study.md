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
A single-page application is essentially what the name implies. There is no change in
URL, and the page does not refresh to accommodate a new rendering of the HMTL. All
interaction with the back-end server happens through AJAX requests, and this creates
a more fluid, responsive application.  
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
A "page" to users simply meant a specific URL. Before defining SPAs I thought a web
page was just a standalone web page with not much to offer. 'Oh, it doesn't have multiple
pages? I guess there's not much to do here.' The complexity between server and client interactions
was beyond my thinking. 
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The view is the only part of the application users actually interact with. It is an
interactive user interface that represents the state of the view. The view state
indicates the status of the page when submitted to the server. Front-end routers
can help manage the view state by loading the correct state.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
There is no need to reload or re-render the web page. Another benefit lies in the
architecture of the web application. Because we're sending app data in JSON format,
we have a distinction between the look of the page and its logic. It allows for easy
adjustments to either without affecting the totality of the web page.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
After the single web application loads, all the necessary code (HTML, CSS and Javascript)
is loaded in the browser. There are a number of Javascript frameworks that maintain
a single page when there is communication between the server and client:
  - AngularJS
  - Ember.js
  - Meteor.js
  - Ajax
```
