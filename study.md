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
A single page application is a webview that remains on the same page (base html structure and url) and instead of updating by loading a completely different html file, it fills, replaces, removes, exitsting html content with new content received in json format. This json formatted data is retrieved from a server using ajax.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Page meaning a browser window with a unique url. If the url changes, a new page has been loaded as opposed to new information being served onto the existing page without navigating away.

Prior to the SPA study page just meant an open tab in my browser.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
View state refers to both what the user is looking at and what the model is listening for from the page. Front-end routers help manage the view state by structuring everything to be modular and separating and packaging assets to ensure code running in an organized manner.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Advantages of single page application: more fluidity to the user as information just needs to be retrieved and put into the view placeholders rather than completely reloading an entire html page.  Less data consumption because the client is only retrieving/sending information and updating rather than having to load an entire page
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Javascript frameworks: Angular.js, ember.js, meteor.js.
Ajax: using XMLHttpRequests + Jquery Library

```
