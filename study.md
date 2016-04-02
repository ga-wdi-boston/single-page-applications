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
A SPA is a web site or application that functions on a single page and loads the code it is composed of (HTML, JavaScript, CSS) just once, when the page is initially accessed.  If the application requires dynamic communication with a server, for example in the case of user input, technologies like AJAX fascilitate that interaction without the page needing to be reloaded.

(Source:
https://en.wikipedia.org/wiki/Single-page_application#Ajax)
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
I think users mean what they see in their browser.  I would've defined it similary.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
When developers refer to the view they mean the visual rendering of the application as opposed to the model layer which the view reads in the background and isn't visible to the user.  View-state refers to the visual rendering of a page in various stages when the page is being interacted with, such as when a menu on the page is opened and being scrolled through.  Front end routers help manage the view-state by allowing communication with the server in the background and eliminated visible disruptions to the application.


```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPA's create a better user experience because they don't require reloading and thus appear more streamlined and responsive.  They also separate the visual product rendered by HTML, CSS and JavaScript from the code that allows the page to interact with the server and generally be dynamic.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Ajax, JSON, Javascript frameworks (AngularJS, Ember.js, and Meteor.js), and browser plugins like Silverlight and Flash (although these are outdated for use with SPA's).
```
