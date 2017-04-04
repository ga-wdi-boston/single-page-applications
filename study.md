## Single-Page Applications Study

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
A SPA is a web application where a user is able to interact with a website without viewing multiple pages or refreshing the browser.  It is characterized as being able to update with user interaction with the application.

Source: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When a user refers to page, he or she is referring to a webpage (rather than an application).  But SPA isn't a webpage - it is an application.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?


```md

Most web applications can be broken into "regions" and contain multiple views.  These "regions" can be shown on the SPA at the same time.  For instance one type of view would involve clicking a button to display details.  Such a scenario is a nested view.

A view state is an instance of interacting with the web application (e.g. opening a menu) and how it affects server-sider rendering.  A view state plays three eseential roles in a SPA. First, it holds, rather than stores, values between postbacks during a specific user session.  Second, it can store defined values of a page.  Lastly, it gives a developer the abiity to store view state information into a server database (i.e. data store).

A front end router refers to mapping URLs to a specific action to a user.  By utilizing front-end routers, view states can be managed through comparing/manipulating URLs

Source: https://msdn.microsoft.com/en-us/library/1whwt1k7.aspx
Source: https://roots.io/routing-wp-requests/
Source: http://www.funnyant.com/angularjs-ui-router/

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
There are two primary benefits for using SPA.  First, pages do not need to be reloaded/re-rendered which makes the application more desireable for the user.  Next, SPA allows the page presentaiton to function independently from the application.  In other words, data can be sent separately and does not incorporate HTML files.

Source: http://singlepageappbook.com/goal.html
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
A list of tools used to create SPAs include (but are not limited to) the following: JavaScript, JSON, AJAX, XML, AngularJS, Ember.js, Meteor.js, Aurelia, and HTTP.

Source: https://en.wikipedia.org/wiki/Single-page_application#Server-sent_events
```
