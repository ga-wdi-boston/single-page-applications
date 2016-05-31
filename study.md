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
Basically, a SPA is a single page application, which differs from other web pages
in that it does not refresh every time the user interacts with the web page. This
makes the web page more responsive and quicker to use, especially for simple tasks
that can rely on AJAX and JSON to update the page rather than repeated requests
to the server from the client.

Sources: https://en.wikipedia.org/wiki/Single-page_application#Search_engine_optimization
http://singlepageappbook.com/goal.html
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
To non-developers, a "page" is just a single page on a website. In general, the level of
functionality doesn't really matter as most websites offer the option to switch to other
pages on the same website. Before starting this search, I held roughly the same definition but was more or less aware that a single page could vary in functionality and that linking to another page or refreshing was not necessary to update and respond to events.
Source: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
In this context, view state refers to the updated data stored invisibly and then called upon later during some action. For instance, if a button is clicked on an SPA, the fact that the button was clicked and the resulting action is then stored. Front-end "routers" handle the logic necessary to implement the actions that impact view-state data and thus
view state is dependent on the logic involved in front-end routers.

Sources: https://msdn.microsoft.com/en-us/library/bb386448.aspx
https://www.quora.com/What-are-the-pros-and-cons-of-keeping-the-URL-routing-logic-at-front-end-vs-back-end
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
An SPA is generally more streamlined than a traditional application. Instead of waiting for the client to sent a resquest to the server and then receive and respond to the response, the JSON and AJAX can kind of take care of smaller, simple functions that don't
require the page to refresh, meaning the user experience is a lot more streamlined and
smooth.

Sources: https://en.wikipedia.org/wiki/Single-page_application#Search_engine_optimization
http://singlepageappbook.com/goal.html
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Some of the tools used to create an SPA are JavaScript, CSS, HTML, AJAX, JSON, and then
also applications/frameworks like Ember.js, AngularJS, and Magento. 

Sources: https://en.wikipedia.org/wiki/Single-page_application#Search_engine_optimization
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```
